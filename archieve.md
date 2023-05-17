### Accuracy
In some of the data segments, the model identified data segments that were indeed a part of the interview data, but identified them using the wrong interviewee number. For example, the following data segments:

>41\. Importance of room for innovation in schools (Interviewee 165)
>
>43\. Challenges in getting schools onboard with using the IT investment process (Interviewee 165)

Interviewee 165 (Karina), didn't know about the IT investment process and has nothing to do with schools. However, these statements were in fact given by one of the interviewees, Interviewee 163 (Søren). Therefore, this is not an example of classic LLM hallucination, but most likely a case of another type of output degradation. This is perhaps enabled by the fact that digits like 1, 6, and 3 are each identified as their own individual tokens, while a name, such as "Karina" or "Søren" would most likely have been one single token. This difference could have allowed the model to have written "16" and, having seen other numbers starting with 16 in the context, having a non-trivial chance of randomly choosing the wrong last digit, "5" instead of "3". Then, from here, the model merely continued pattern, which is one of the strengths of this type of language model coming to haunt us, continuing for the rest of the output to incorrectly refer to Søren as Interviewee 165.

To avoid this kind of output degradation, it is suggested to avoid using numbers to identify participants, instead giving the model only pseudonyms for this purpose. If it is absolutely critical to use numbers, then selecting single-digit numbers would be preferable.


### Completeness

The depth of the analysis in focus, rather than in sheer detail, did not reach the desired level. This shortfall can partially be attributed to the lack of explicit instructions to the model regarding the specific topic under investigation, beyond the following problem statement:

> The IT department at Vejle municipality has established an IT investment process that outlines a set of procedures for procuring new IT systems, software, and equipment. Despite these guidelines, employees do not always follow this process, leading to potential inefficiencies and discrepancies in IT investments. This study aims to explore the reasons why employees do not comply with the IT investment process and suggest strategies to improve compliance.

A dialogue-based approach to the analysis would have proved advantageous, inviting the model to engage with the researcher in a conversational style. This interaction would enable more detailed insights to be extracted and foster a deeper understanding of the case. Unfortunately, the implementation of such a methodology is currently restricted by the limitations of the available 8,000-token model, although it could conceivably be achieved with the larger 32,000-token GPT-4 model.

The analysis appears to lack a comprehensive understanding of the organisational context, particularly with regard to the IT investment process. Identifying these missing elements is a challenge, as they are deeply intertwined with my personal experiences gathered during the project's investigation. In this light, the dialogue approach could serve a dual purpose: it could act as a catalyst for the researcher to probe deeper into their contextual assumptions and simultaneously impart a richer understanding of the organisational context to the model.

A specific area of potential improvement lies in the definition of the IT investment process. The process could have been more explicitly described in the prompt. The term's inherent ambiguity may have clouded its actual function and significance within the context, thus constraining the model's focus and comprehension.

Creating an affinity diagram is a process that necessitates thoughtful contemplation of categorisations and their implications, infusing the data with meaning. However, as revealed in the model's simulated stream of consciousness, the model seemed to concentrate on the identification and thematic categorisation of data segments, without delving into their potential implications.

Despite the model's extensive data segmentation, it became clear to me, as the interviewer, that certain context and subtext did not make the transition from reality into the notes. As a result, a comprehensive understanding of these elements cannot be reasonably inferred from the notes alone. The dialogue approach, reiterated here, could potentially bridge this gap, paving the way for a deeper exploration and understanding of the data's underlying themes and complexities.

### Clarity

While the individual data segments are clear, the groupings of the data segments do not help much in finding meaning in the data. 

#### Repetition of data segments

A severe case of output degradation is showcased here:

> 22\. Difficulty in sticking to assigned roles in decentralized IT support (Interviewee 183)
>
> 34\. Difficulty in sticking to assigned roles in decentralized IT support (Interviewee 190)

The text includes the same data segment, which only serves to create a more messy affinity diagram. This same error repeated itself several times in the output, 

#### Group Quantity and Composition

A discernible tendency of the model is to generate lists with round numbers of items, reflecting human inclinations for 3, 5, and then 10 items. It appears that the optimal number of groups for this analysis would have been somewhere between five and ten. However, the model's performance seems to degrade at this juncture, opting to proceed with only five groups, likely due to the dominant probabilities at play in the training data. A potential refinement could involve incorporating checkpoints in the model's progress between each section, permitting human intervention to identify and rectify instances of performance degradation.

The caveat with this approach is that it necessitates pausing the generation process each time, which means reintroducing the entire text, including the original prompt and the generated output, as a new prompt. This is especially true when dealing with large datasets, as users are charged both for the model's output tokens and then again when these tokens are used as input. In contrast, generating the entire response in one go only incurs charges for the input data and the associated prompt and output generated by the model. However, as will be covered in the later section discussing opportunities for further research, recent studies indicate that the model performs better at self-reflection when a new request is sent to the model.

#### Group Size and Distribution

An issue of concern is the model's third category, "Group 3: Challenges and Barriers in IT Investment Process," which seems to function as a catch-all group, accommodating many data segments. Optimally, this category could have been more evenly distributed. The model's bicameral dialogue approach appears to have been prematurely terminated, potentially contributing to this issue:

> # SORTING, GROUPING, AND LABELLING
>
> ## THINK
>
> Self 1: We have a good list of data segments now. Let's think about how we can group them together in a meaningful way to better understand the main themes and issues.
> 
> Self 2: We could start by grouping the segments related to awareness and understanding of the IT investment process. This would include segments like lack of awareness, bureaucratic nature, and uncertainty about when to use the process.
> 
> Self 1: That's a good idea. We could also group the segments related to communication and relationships between the IT department and other departments, as well as the role of IT architects in the organization.
> 
> Self 2: Yes, that makes sense. Another group could be the challenges and barriers faced by employees when it comes to the IT investment process, which would include segments like the lack of training, inaccessibility of the intranet, and double solutions issue.
> 
> Self 1: Great. We could also have a group for suggestions and improvements to the process, like making it more user-friendly, better promoting it, and having more fixed and transparent guidelines.
> 
> Self 2: That's a good group. Lastly, we could have a group for the specific contexts and considerations of different departments or facilities, like decentralized IT support, residential care facilities, and schools.
> 
> Self 1: I like that. Let's write down these groupings with appropriate names.

The model appears to favour a specific number of dialogue turns, likely influenced by examples from previous sections and the training data. This predisposition can result in excessively lengthy bicameral dialogues for straightforward matters and, more critically, dialogues that cease before adequate consideration has been given to the topic at hand. In this regard, less fine-tuned models (e.g., the older text-davinci-003) might have been more appropriate for the task. While models like GPT-3.5 and GPT-4 are optimised for chat applications, excel in structured tasks such as text summarisation, and produce concise outputs, they may not be ideal for more complex or nuanced tasks requiring long bouts of simulated thought.

#### Possible Solutions

One potential approach to enhancing the effectiveness of the model's operations could be to fine-tune GPT-4 to yield more detailed bicameral dialogues. This could be achieved by employing a method similar to Reinforcement Learning from Human Feedback (RLHF), as delineated in studies like @christiano2023deep and @NEURIPS2022_b1efde53. This approach would facilitate the generation of a multitude of bicameral dialogues, with the quality of the output subsequently assessed through human evaluation. However, as GPT-3.5 and GPT-4 do not currently allow for fine-tuning, implementing this strategy is not presently feasible.

An alternative solution could involve training or prompting GPT-4 to provide a status update after each bicameral turn. This would require the model to actively engage in self-reflection and reasoning about the adequacy of its outputs prior to proceeding. This way, the model could signal whether the groups generated through brainstorming adequately represent the data. However, to completely harness the potential of this methodology, fine-tuning may be a necessary step.

#### Re-evaluating the Bicameral Dialogue Approach

It might also be worthwhile to question the utility and efficacy of the bicameral dialogue within this context, as compared to a single stream of simulated thought. The initial rationale behind implementing the bicameral dialogue was to facilitate a dynamic where Self 2 could critique Self 1 and vice versa, thereby encouraging a more robust and diverse analysis. However, in practice, the two selves appeared to predominantly affirm each other's responses, only serving to degrade the output by restricting the length of the train of thought. Therefore, a more detailed investigation into the relative merits of bicameral dialogues versus single streams of thought could provide valuable insights for refining the analysis process.