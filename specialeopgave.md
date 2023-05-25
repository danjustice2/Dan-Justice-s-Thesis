
author: Danny Ray Justice
institution: University of Southern Denmark
title: Navigating the Currents of Change: An Ethnographic Study of IT Investment Reporting in Organisations
runninghead: IT INVESTMENT REPORTING IN ORGANISATIONS
abstract: 
keywords: key1, key2

# Introduction

Our world is increasingly influenced by the rapid progress of digital evolution, which has far-reaching implications in a variety of domains, including academia. A notable development in this arena is the incorporation of artificial intelligence (AI) and machine learning (ML) technologies into academic research methodologies. This integration opens up exciting prospects for significant breakthroughs, pushing the boundaries of traditional research methods.

This study delves into the exploration of one such technology, the Generative Pretrained Transformer 4 (GPT-4), a cutting-edge Large Language Model (LLM) developed by the American AI research laboratory OpenAI. GPT-4, the latest iteration in the GPT series, possesses advanced capabilities that have the potential to revolutionise the field of text generation and analysis. In particular, our research aims to examine the capacity of GPT-4 in augmenting traditional qualitative research methodologies, with the backdrop being the IT department in Vejle Municipality in Denmark.

Vejle's IT department has in place a well-structured IT investment process, but there have been challenges with employees' adherence, leading to inefficiencies and discrepancies. This study is designed to dig deep into the reasons behind such behaviour and propose strategies to enhance compliance.

A significant innovation of our research lies in utilising GPT-4 to create affinity diagrams based on a corpus of interview data. This leverages GPT-4's capacity to process and analyse vast amounts of text and build an understanding of the interconnected themes present within the data. Recent studies, such as @weiChainThoughtPrompting2022, indicate that LLMs perform optimally on reasoning tasks when prompted with a chain of thought. The novelty of our study lies in the application of this chain of thought prompting to a more substantial analytical task, such as the analysis of interview data and the generation of a structured affinity diagram.

Our exploration, therefore, fulfils a dual purpose. Firstly, it sheds light on the socio-technical system within Vejle municipality and the specific dynamics that impact the IT investment process. Secondly, it uncovers the potential of AI and GPT-4 as pioneering tools in academic research, providing an original perspective on qualitative studies.

## Research Questions

Our research is guided by two intertwined questions:

1.  How does GPT-4's capacity to generate affinity diagrams from interview data compare to that of a human researcher, and what insights can this provide for qualitative research methodologies?
2.  What are the key factors contributing to the non-compliance of employees with the IT investment process in Vejle municipality, and how can these factors be addressed to improve adherence?

These research questions aim to deliver a comprehensive assessment of GPT-4 as an innovative tool for qualitative research and simultaneously offer deeper insights into the dynamics of the IT investment process in Vejle municipality.

## Relevance of Research

This research carries weight from both practical and academic standpoints. Practically, the findings of this study aim to enhance the efficiency and compliance of the IT investment process in Vejle Municipality. Academically, the study explores the potential of GPT-4 as an innovative tool in qualitative research, which can contribute significantly to the discourse on AI integration in academic research practices.

The combination of these aspects means the research holds immediate practical implications and has the potential to influence the trajectory of academic research methodologies, opening up new doors of enquiry regarding the role LLMs could play in qualitative research going forward.

## Overview of Structure

This thesis is composed of two parts, each addressing a specific research question. The first part focuses on the IT Investment Process in Vejle Municipality, while the second part evaluates the utility of GPT-4 in qualitative research, focusing on prompting the model to output affinity diagrams from interview data.

The first section starts with an introduction to the case background, followed by a literature review providing the theoretical context. The research methodology includes semi-structured interviews and field notes for data collection, with affinity diagrams used for data analysis. The results, discussion, and recommendations form the subsequent segments of this part of the study.

The second section focuses on GPT-4, providing a technical background for those unfamiliar with the model. This is followed by a literature review on GPT-4's implications in qualitative research. The methodology involves data collection through user-model interfaces, with criteria for assessing output quality forming the basis of data analysis.
# Case Study: Vejle Municipality's IT Investment Process

## Case Background
Residing within the administrative building of Vejle Municipality, the IT department has historically grappled with effective communication, particularly with external stakeholders and individuals in decentralised roles. Recognising the need to bridge this gap, the department strategically incorporated four IT architects into its ranks over recent years, each bringing a distinct blend of skills and expertise.

These IT architects, integral to the municipality's IT ecosystem, strive to reconcile municipal employees' expectations with the capabilities and resources of the IT department. They deftly navigate technical and non-technical perspectives within the municipality, balancing the need for clear communication with the complex understanding required of their role. A blend of "hard" and "soft" skills allows them to empathise with the diverse needs of users throughout the municipality while staying conversant with current and emergent technologies.

Among these architects are Jonas and Mathilde, who together form a harmonious blend of technical and human-focused insights. Jonas excels in the intricate nuances of IT architecture, while Mathilde advocates for a more empathetic, human-centred approach to IT. Their collaborative efforts ensure the fluid integration of new technologies and foster a sense of shared understanding and ownership in IT investment decisions across the organisation.

Jonas and Mathilde's invaluable guidance and profound knowledge have significantly shaped the course of the present study, their generosity in sharing their insights reflects in the multiple references within the forthcoming text.

In response to the challenges in procuring new technologies, Vejle Municipality has implemented an IT investment process, facilitated through an online webform accessible via the intranet. The webform serves a dual purpose: keeping the IT department aware of which technologies the organisation works with, and connecting appropriate IT personnel with the investment project for smooth implementation and potential impact evaluation.

The webform's user interface presents a clear directive to all employees of the municipality:

> "If you need to address a new IT task, update or enhance an existing system, have an idea for an IT system, or purchase a new IT system, the City Council requires you to utilise the IT investment process. By following this process, we collectively ensure that the system or function can be utilised while meeting our IT requirements. Additionally, when you follow the investment process, you will receive guidance to other departments if there are specific areas that require attention, such as information security."

A list of examples provided to clarify the instances in which the IT investment process should be invoked includes scenarios like exploring existing solutions, making changes to current systems, seeking IT support for a process, purchasing new equipment requiring network access, or implementing a new IT solution.

To engage this process, employees are required to complete an electronic form on the designated intranet page. Following form submission, an IT department architect typically contacts the submitter within 48 hours, initiating a dialogue involving the employee, the supplier, and an IT department representative, ultimately leading to feedback that includes an overall IT assessment of the system. If required, additional references to other departments within Vejle Municipality, such as Competition Suspension, are provided.

However, despite these comprehensive instructions and the broad applicability of the webform, its use among employees remains limited. A significant effort has been made to simplify the webform, making it more accessible by removing intricate questions that non-IT personnel found challenging. The primary goal was to increase the form's usage and prevent staff from directly contacting IT architects or other members of the IT department, thereby streamlining the IT investment process. However, these efforts have not translated into the expected increase in webform usage.

In light of these observations, this study aims to delve into the reasons behind employees' inconsistent adherence to the IT investment process and propose strategies to improve compliance. The ensuing report will thoroughly investigate the complexities of this

## Literature Review
This literature review will delve into three key areas pertinent to this study: IT Investment Governance, Ethnomethodology, and Affinity Diagrams. The analysis of these topics aims to build a theoretical underpinning for understanding the complexities of IT investment in the public sector and how ethnomethodological research and affinity diagrams can help derive valuable insights into this intricate process. Let's begin by unpacking the first concept, Information Technology Investment Governance.

### IT Investment Governance

IT governance is a vital component for both private and public sector organisations, playing a central role in aligning IT investments with institutional goals and maximising associated benefits \[@Weill2004\]. Encompassing decision-making, planning, and controlling IT investments, it sits at the heart of effective governance.

One influential concept for understanding IT governance is the resource-based theory, proposed by @Wernerfelt1984. The resource-based view (RBV) suggests that organisations can secure a sustainable advantage by optimally employing their resources and capabilities, those possessing valuable, rare, imperfectly imitable, and non-substitutable (VRIN) attributes \[@Wernerfelt1984; @Barney1991\]. RBV underlines the strategic necessity of resource allocation for maximum value.

When we consider RBV in public sector contexts, such as Vejle municipality, the idea of a "competitive advantage" is recontextualised. Unlike private firms, public institutions aim to deliver the best possible public value rather than outperform market competitors. Here, the efficient allocation and utilisation of resources equate to high-quality service delivery. In the realm of IT investment, strategic decisions should maximise public benefit through increased efficiency and effectiveness.

Building upon the RBV, @Bharadwaj2000 positions IT resources as a distinct strategic category. Organisations, he argues, possessing superior IT capabilities, can enhance their operational efficiency and service quality \[@Bharadwaj2000\]. This perspective fits seamlessly within the RBV, reinforcing the critical need for effective governance of IT resources and investments.

@ALI20151 developed a novel construct, known as IT investment governance (ITIG), also premised on the RBV. ITIG gauges an organisation's competence in effectively governing its IT investments, thereby enabling the efficient allocation and utilisation of IT resources. The construct comprises four elements: IT investment value governance, IT investment value monitoring, IT investment appraisals, and IT investment project management.

The relevance and efficacy of the ITIG construct were demonstrated by Ali et al. (2015), highlighting a significant positive correlation with organisational performance. This critical finding implies organisations with robust IT investment governance are poised to extract greater value from their IT investments and align these more closely with their strategic goals. Consequently, effective IT investment governance enables organisations to amplify operational efficiency and public value, thus reinforcing the core principles of the RBV.

While Ali et al. (2015) made notable strides, certain gaps still persist, particularly in understanding the behavioural elements influencing effective IT investment governance, such as employee compliance with IT governance processes. Nonetheless, the RBV and ITIG construct offer a robust theoretical foundation to scrutinise and enhance IT investment governance within the public sector, paving the way for future research and improvements.

### Ethnomethodology

The field of social science research has seen a significant surge in the application of Ethnomethodology (EM) as a theoretical approach. EM explores how individuals establish and uphold social order through their everyday interactions, focusing on practical methods and techniques they utilise to comprehend their social realm. As observed by @crabtreeDoingDesignEthnography2012, EM research primarily centres on how communities or social settings employ quotidian practices and knowledge to formulate the regulations governing their social existence (p. 316).

EM's wide-ranging application spans diverse fields such as sociology, anthropology, communication studies, with more recent integration into human-computer interaction and interaction design studies. It is instrumental in examining how individuals engage with technology in daily life and how technological advancements impact and shape social practices.

@crabtreeDoingDesignEthnography2012 assert the value of EM in deciphering technology utilisation across various settings. They suggest that the methodology's focus on minutiae of day-to-day practices can aid researchers in recognising practical challenges encountered by individuals while using technology, and how design can alleviate these issues. Moreover, they posit that EM's emphasis on the social context of technological use can provide insights into how technology integrates into broader social structures and influences social relations.

#### Interviewing: A Word of Caution

Interviews, according to @crabtreeDoingDesignEthnography2012, should be approached with prudence. They propose conducting interviews within the authentic flow of work as circumstances allow. Highlighting the discrepancy between what people claim to do and their actual actions, they note that while not being intentionally misleading, interviewees tend to gloss over their work. To overcome this, researchers are advised to focus on the precise actions and methods of work, avoiding an interview format driven by a set of pre-formulated questions detached from the actual work process.

#### The Importance of Field Notes

The creation of field notes is a crucial component of fieldwork, state @crabtreeDoingDesignEthnography2012. Field notes allow researchers to document their observations, capturing what they witness, hear, and are informed of. This not only provides a record of the research but also assists researchers in tracking and organising their thoughts. The active process of note-taking encourages the researcher's attention to the work as it occurs, thereby fostering a better understanding of the task at hand.

The researchers' notebook, @crabtreeDoingDesignEthnography2012 suggest, should not be a mere collection of disjointed remarks. Instead, it should serve as a structure for the researcher's thoughts, crafting a coherent narrative of the setting's work. Diagrams of the work ecology are recommended to frame inquiries and represent the work environment to others. Detailing the environment, the inhabitants, their roles or responsibilities, and the artefacts employed for work can lead to a more comprehensive understanding of the setting's work and the methods employed by members to organise it.

#### Formal Organisation of Work and Its Flow

Understanding how the work is 'formally organised' across a division of labour and individually, is crucial, according to @crabtreeDoingDesignEthnography2012. This comprises the plans, procedures, processes, and routines invoked by the members to account for their work organisation. Researchers should also concentrate on the work's flow, noting how it moves across individuals, activities, and culminates in an endpoint.

#### Discrete Sequences of Interactional Work, Cooperation, and Collaboration

@crabtreeDoingDesignEthnography2012 encourage researchers to enrich their depiction of work's flow by concentrating on discrete sequences of interactional work entailed in completing specific activities. The focus should be on what is done, who does it, and the process of work completion. Attention should also be given to the cooperation and collaboration between individuals during discrete sequences of interactional work. This would involve observing and documenting who interacts with whom, their discussion points, joint activities, task transactions and handovers, and subsequent responses.

### Affinity diagrams
Affinity diagrams, also known as the KJ method or affinity charting, were first developed by Japanese anthropologist Jiro Kawakita [as cited in @scupinKJMethodTechnique1997]. Affinity diagrams are used to synthesise and categorise large amounts of qualitative data, such as observations, interviews, and field notes, into meaningful and easily understandable themes and patterns [@haningtonUniversalMethodsDesign2019].

The affinity diagramming process typically starts with the raw data being transformed into discrete statements or observations. These statements are then grouped based on their similarities and relationships [@haningtonUniversalMethodsDesign2019]. The groups are subsequently labelled with descriptive headings, which capture the essence of their content. This iterative process allows for the identification of patterns, themes, and relationships among the collected data, thus providing insights and guidance for further analysis and design @holtzblattAffinityDiagram2016.

In the context of ethnographic UX studies, affinity diagrams serve as a valuable tool for making sense of the complex and often messy data that emerges from immersive fieldwork @holtzblattAffinityDiagram2016. By organising and categorising data in a structured manner, researchers can identify user needs, behaviours, and pain points, which can inform design decisions and enhance the overall user experience @haningtonUniversalMethodsDesign2019.

Furthermore, affinity diagrams facilitate collaboration and interdisciplinary communication among research team members @holtzblattAffinityDiagram2016. By engaging in the process of grouping and labeling data, researchers from different backgrounds and expertise can contribute to a shared understanding of the user experience, leading to more innovative and effective solutions.


## Methodology

### Data Collection: Interviews & Field Notes

In this study, the process of data collection was established upon two critical components: semi-structured interviews and field notes documentation.

**Semi-Structured Interviews:** This data collection methodology was a primary channel to gain insight into the users' experiences and perspectives. As suggested by @crabtreeDoingDesignEthnography2012, the interview setting was informal to encourage genuine and in-depth discussion. The interviews were designed to be "decontextualised" due to the nature of the study, where the subject matter (new IT investments) was not part of the daily routine for most employees.

A selection of twelve employees across all six administrative divisions of Vejle's municipality was interviewed based on a list provided by an internal contact at the municipality. To maintain confidentiality, each interviewee was assigned a pseudonym and an identification number.

The interviews were conducted face-to-face, barring one instance where a video call was arranged to accommodate the participant's circumstances. Handwritten notes were taken during the conversations to ensure a relaxed atmosphere, and the questions were based loosely on an interview guide (Appendix X), allowing flexibility for natural discourse.

Following each interview, the brief notes were used to create detailed transcriptions, which were then developed into coherent prose summaries. It is important to note that the interviews were conducted in Danish, and the translation into English occurred at the summary phase. The complete interview summaries and notes are available for reference in Appendix X.

**Field Notes:** As a complementary method, field notes played an essential role in the data collection process. Drawing from the significance emphasised by @crabtreeDoingDesignEthnography2012, field notes were used to document observations, thoughts, and insights about the research setting.

A physical notebook was consistently maintained for documenting fieldwork observations, particularly during interviews, to avoid the intrusion of digital devices. Additionally, a cloud-synced notes application served as a supplemental tool for situations where typing was preferable to handwriting.

The process of taking field notes enabled a comprehensive understanding of Vejle's work environment, shedding light on specific dynamics such as task handovers and transactions between individuals. Additionally, the field notes acted as a reflective tool, aiding in evolving an understanding of the work setting over time.

In sum, the combination of semi-structured interviews and field notes documentation provided a comprehensive and valuable resource. The detailed accounts served as a solid foundation for the analysis and interpretation of the data, effectively informing the subsequent phases of this research study.

### Data Analysis: Affinity Diagrams
Following the process of collecting interview summaries and field notes, an affinity diagramming technique was employed to synthesise and analyse the data. This method provided an effective way to organise the large volume of collected data, identify patterns, and uncover underlying themes.

The affinity diagramming was conducted virtually using a computer program. Each interview summary was reviewed one at a time, and data segments were captured on virtual sticky notes. Each interviewee was assigned a unique colour for their sticky notes, thereby enabling easy identification of their respective insights. However, due to the limited palette, the color differentiation ended once the range was exhausted, and the remaining sticky notes were kept in grey. 

As the process unfolded, these sticky notes started forming natural clusters of related information based on the similarities and patterns that emerged from the data. This process allowed for the visual grouping of insights according to their inherent relationships, providing a high-level view of the data landscape.

Additionally, lines were drawn between these clusters to illustrate the connections and dependencies between different groups of data, making the relationships explicit. This process enabled a more profound understanding of the data and facilitated the identification of overarching themes and patterns.

Throughout this process, the affinity diagram was consistently reviewed and iteratively adjusted to ensure that the emerging patterns and relationships accurately reflected the data. The diagram served as an evolving visual representation of the collected data, allowing the research findings to be presented in a comprehensive, organised, and accessible manner. 

In conclusion, the affinity diagramming method was instrumental in providing a structured approach to data analysis. It facilitated a holistic view of the data collected through semi-structured interviews and field notes, allowing for a nuanced understanding of the research context, which in turn informed the interpretation of the research findings.

### Data Analysis: GPT Models

While the data analysis of the present chapter primarily relied on creating a traditional affinity diagram, the LLMs GPT-4 and its predecessor GPT-3.5 served as valuable supplementary tools, aiding the author in the research process. Their inclusion offered a unique opportunity to enhance the breadth of information accessed beyond what was personally known or available in the immediate context of the study. The LLMs were primarily utilised for their conversational abilities, providing an interactive platform to generate diverse perspectives on the research topic. Drawing from an extensive text corpus, LLMs offered insightful responses to the author's queries, often sparking new lines of thought, novel questions, and unexplored research avenues.

Notably, the LLMs did not merely function as an easily accessible knowledge resource, but they also catalysed critical thinking and intellectual curiosity. They served as a sounding board for the author's ideas, providing a space for in-depth exploration of varying perspectives, encouraging a deeper contemplation of the research. Furthermore, their extensive knowledge base, available on-demand, supported the author in making real-time decisions on research matters.

While LLMs can serve as a source of knowledge, it is always worth noting that these models can also output false information, so all information attained from the models was double-checked using traditional information searching methods.

## Presentation of Interview Data
\
![The author's human-made affinity diagram from the interview data. A high-resolution version is available in Appendix X.](9d6d3fd1cf5e3b0a9a7514c1b7c47822.png "The author's human-made affinity diagram from the interview data. A high-resolution version is available in Appendix X.")
The data gathered for this study comprises semi-structured interviews with twelve employees of Vejle Municipality, spanning various roles across all six administrative divisions. The data collection process involved taking rough notes by hand during the interviews, followed by more refined digital notes afterwards. From these refined notes, I created two affinity diagrams: one by hand and the other with the assistance of GPT-4 through a carefully crafted prompt.

The analysis in this report primarily utilises my hand-made affinity diagram, as it encompasses not only the insights gleaned from my notes but also the nuances of my experiences and observations within Vejle Municipality.

Out of the interviewees, the majority were familiar with the IT investment process: six indicated familiarity (including one who had helped create the process in her role as a digitalisation consultant), five were unfamiliar, and the final participant, who was also unfamiliar, deemed the process irrelevant to her work and was therefore excluded from the analysis.

### Perception of IT investment process as impersonal or excessively bureaucratic
My first interview was with Freja, a seasoned web manager from the Policy, Analysis & Communication department. During our discussion, Freja expressed strong opinions on the IT investment process, perceiving it as excessively bureaucratic and impersonal. With twenty years of experience working closely with the IT department, she felt confident in her ability to communicate directly with them when necessary, bypassing the formal process. Freja advocated for a more relationship-based approach, emphasising the importance of positive reinforcement over punishment.

Freja's perspective laid the groundwork for my research, as the issue of the IT investment process being seen as impersonal and bureaucratic recurred in subsequent interviews. Her experience and insights into the challenges of collaborating with the IT department were invaluable, and her close connection to the department provided a unique viewpoint that illuminated broader issues surrounding the process.

Lise, an administrative assistant in the Daycare department, acts as a vital bridge between the Administration Building and daycare workers, who have distinct needs due to their more practical roles. Lise expresses concern and dismay at the prospect of using a form to contact the IT department. She values her personal relationship with Jonas from IT, as he understands the unique context of daycare workers. Lise worries that submitting a form may result in losing "unspoken considerations" arising from the social and educational differences between the two groups.

To alleviate these concerns, Lise suggests adding an option on the form to indicate if the case involves a target group struggling to adapt to technological changes. Another appealing solution she proposes is including a preferred IT department contact person on the form, ensuring that someone familiar with the specific context is involved.

### Benefits of using the process: potential talking points
Claus, a development manager at Vejle's Center for Special Education for Youth and Adults (CSV), finds the IT investment process helpful because it connects them with the right people, such as an architect who oversees the case, ensuring it is remembered and acted upon. Using the IT investment process also provides a clear line of communication when working decentralised, as is the case with CSV. It allows them to follow a case in the system and see which IT department members are involved and what they are doing. Claus appreciates the ability to intervene if he feels his needs has been misunderstood.

### Potential for strengthened cooperation between IT and the rest of the organisation
Emma, who has been working in the municipality for thirteen years and took over her current position as an Implementation Consultant in the Department of Welfare six months ago, told about welfare's own work and how they have a similar form to the IT investment process for welfare investments. She suggested that it would be more efficient if their applicants could automatically involve IT in projects related to IT.

Another example of potential strengthened cooperation comes from Anne, a professional consultant for the Salary department and primary contact point for KMD, the municipality's payroll system. Anne shares a similar attitude with the IT department, wishing that employees in the organisation would be better at consulting with her before purchasing systems that fall within her area of responsibility, rather than buying the system first and then consulting with her about its implementation afterward. This attitude may be why she has a good relationship with the IT department, consulting with them well in advance.

Anne recalls an instance when she was called to a meeting by someone in the organisation, along with Jonas from the IT department, thinking that she 'might' have a stake in the implementation of their new system. She described the meeting as, "It was a video meeting, but I could sense that Jonas and I were looking at each other on the screen, thinking, 'is this really happening right now.'" This was because the third person had already purchased the system without asking and wanted it up and running in three weeks, which she found very unreasonable. She tells that such situations have at times created a tremendous workload in their wake. Thus, although Anne and Jonas work in different professional areas, they share some frustrations. A central frustration is that employees' expectations for the timeline of implementing new things do not match their own.

During the interview, I suggested the idea of merging the systems, and Anne reacted positively to this idea, agreeing that implementing a central system that directs communication based on certain guidelines could help ensure that employees with new investments in the pipeline do not have to guess who should be involved and when in the process they should be involved.

###  Time requirements for new solution implementation
As touched on earlier, Anne from the Salary department has grappled with some employees in the organisation who were eager to introduce new solutions, with expectations regarding the timeframe for these implementations that, in her view, were unrealistic and lacked sensitivity to the accompanying workload. At present, there are no formal guidelines laying out the expected duration for the implementation of new solutions. This void likely stems from the inherently diverse nature of IT investments, making the creation of universal guidelines a challenging task.

### The name perceived as opaque and unattractive
Despite not being familiar with the IT investment process prior to our interview, Emma recalls hearing about it from Jonas, one of the IT architects, at a meeting. Emma assumed the process was primarily relevant to IT and economy personnel due to its name. She agreed that a more tangible name, such as "Indkøbsguiden" (Danish for "The Purchase Guide"), might make it more accessible to the grassroots level of the organisation. However, according to Jonas, a similar system in another municipality also faced issues with lack of use, indicating a more attractive name cannot stand alone.

### IT investment process not widely promoted
Interviewees such as Anne have a view of the IT investment process not being widely promoted or talked about by the personnel in the IT department. She has been used to just contacting Nicklas or one of IT's other architects when she needed something.

### Broad guidelines for when reporting is required
Some interviewees such as Mikkel from the Vejle's central library's IT department shared a feeling of being unsure as to when it actually was necessary to use the IT investment process, as the guidelines laid out on the Vejle's intranet cover a very broad area of investments. This is especially problematic for such central institutions that have the resources to implement new investments themselves without involving central IT, with an underlying feeling of participants wanting to be able to avoid using the process if it is unnecessary, despite the narrative at central IT being, if you are unsure, still use it to be safe.

### Central vs decentralised
Søren, responsible for purchasing IT equipment for schools, explained that, while employees of the municipality are met by the municipal intranet as the first thing when they log onto their computers, employees in schools have to specfically browse to the intranet's address and log in to get access, making an extra barrier to entry to the IT investment process for them. Søren is nevertheless hopeful that, while school employees currently don't use the IT investment process, that it would be possible to get them to use it with the appropriate training, despite the fact that IT investments aren't a part of the everyday work of school employees. Søren went on to say that he thinks it is important that passionate school teachers have the adequate freedom to purchase unique IT equipment to practice their unique styles of teaching, as he seems to view this as an important part of a healthy school system.

Peter, a care assistant who recently retired but still works at the residential care facility one day a week to help with their IT, raised concerns about the feasibility of relying on support from Vejle's central IT department in decentralised areas. He wonders what will happen to the facility when he fully retires, as they will have to rely on support from central IT, which may not be viable considering the facility's location and the fact that they operate year-round, providing constant care to residents.

### Frustrations with restrictions from IT
During the interviews, it became apparent that some interviewees, such as Claus, were frustrated with the limitations imposed by the IT department. Claus expressed his desire for more flexibility and autonomy in updating programs on his computer without having to consult with central IT. Additionally, Claus hoped for more collaboration between Søren from school IT and central IT, as these areas are becoming increasingly interconnected.

Another interviewee, Peter, expressed frustration with the lack of flexibility in smartphone models available. He believed that investing in the phones recommended by the supplier of their systems would be more beneficial, as they come with a guarantee of receiving updates for up to eight years after purchase. However, IT disagreed with his reasoning, claiming that he was influenced by the supplier. Peter's argument was that the phones offered by the IT department had to be replaced after a shorter lifespan due to not receiving necessary security updates from the manufacturer. 

### Importance of IT architects as communicators
Many interviewees, such as Søren from school IT, acknowledged the importance of IT architects as communicators. Søren notes that the arrival of IT architects in the organisation has improved communication and collaboration between central IT and decentralised areas, as well as between IT and the rest of the organisation.

Claus went so far as to call the IT architects a "godsend," giving IT a more service-oriented outward face. Freja touched on that IT, through the years, has attained a greater range of skills than were available before, both in technical expertise but also particularly in the area of soft skills such as communication, nodding to the hiring of IT architects within the past five to ten years.

The architects, including Mathilde, have reached out more to decentralised areas in an attempt to build better relationships. Both Søren and Mikkel mentioned Mathilde's joint meetings, describing them as very helpful in the process of making IT's work more accessible throughout the organisation.

### Current wins for the IT investment process
While the interview data yielded a fair deal of critique to the process, it is not all bad. The web manager Freja expressed that, in her experience, that she thinks people have become more aware of the need to avoid double investments through the years. Søren from school IT described the simplification the IT investment process underwent some years ago as a considerable improvement, taking more consideration for decentralised employees.

## Discussion

### Recommendations for Vejle Municipality

Interviews conducted and ethnographic observations highlight opportunities to improve the IT investment process at Vejle Municipality. Though initially perceived as primarily an awareness issue, other key concerns also require addressing. Recommendations will be based on interview data and, occasionally, my own ethnographic observations.

#### Enhance communication and visibility of the IT investment process

To better communicate the IT investment process, it should be positioned as a support service rather than a bureaucratic obstacle. Adding an option to indicate preferred contact persons in the IT department could help alleviate concerns about the process's impersonal nature. Moreover, prioritising improved communication and collaboration between central IT and decentralised areas, and between IT and the rest of the organisation, is essential. IT architects have made progress in this area, but continued efforts are crucial for effectively integrating the IT investment process into Vejle Municipality's daily operations.

##### Establish clearer guidelines on reporting responsibilities

IT architects play a vital role in communicating the process through personal interactions and other means. As Anne, an interviewee, highlighted, sharing the process with the right people without bothering irrelevant employees is essential. While the intranet contains ample information on when investments must be reported, it lacks clarity on who is specifically responsible for reporting investments to IT. This ambiguity can lead to situations where no one takes responsibility for contacting IT.

Clearer guidelines for reporting responsibilities could help remedy this problem and make it easier for architects to find and communicate with the appropriate individuals within the municipality.

##### Address implementation time and workload concerns
As reported in the interview with Anne from the Salary department, instances have occurred where employees approach IT and other stakeholders with unrealistic expectations regarding the timeframe for solution implementation. Such situations can lead to disappointment and/or impose an excessively heavy workload to meet the desired schedule. It is therefore crucial to focus on the time requirements of projects. If feasible, guidelines should be established to provide employees with a realistic estimate of the time it will take to implement their IT investments.

Alternatively, or in addition, the IT investment process form could incorporate an option for indicating a preferred implementation date for the new IT investment. This provision would allow the IT architect to manage expectations right from the first meeting, helping to realign any unrealistic timelines. Consequently, the IT architect would be less likely to be taken aback by an impractical timeframe presented during the meeting. This strategy could also mitigate the element of surprise and reduce the likelihood of a burdensome workload being imposed at short notice.

##### Set an example

When employees contact IT architects for assistance, they should receive help with their IT investment. Simultaneously, IT architects should create a record of the new IT investment in the appropriate database, demonstrating mutual respect for the process. After logging the investment, IT architects could inform the employee and politely request that they use the IT investment process for future investments, ensuring to explain the process's purpose.

##### Simplifying the introductory text

IT should consider the presentation of the IT investment process on the intranet page further. The extensive technical text on the page should be relegated to less prominent areas, as first impressions are crucial in persuading employees to engage with the process. Instead, a more concise, simplified version should be presented, emphasising the rationale for the process's existence and the advantages of utilising it, ideally employing more engaging communication methods.

For instance, a video that explains the process, its purpose, and its benefits could be showcased on the intranet page, making it a valuable resource to which IT architects can direct employees for further information.

By making employees aware of the rationale behind the IT investment process and its potential benefits, they are more likely to be receptive to changing their behaviour. Simultaneously, understanding the logic underpinning the IT investment process provides a more intuitive way of explaining and grasping its relevance. This approach could help address the image problem and confusion arising from the current guidelines, as mentioned in the previous section.

##### Consider revising guidelines for when investments should be reported

For IT-savvy employees outside of the IT department, such as Mikkel and Freja, the guidelines regarding when IT investments need to be reported can appear overly broad, seemingly intended for employees whose daily work and competencies do not focus on IT. Consequently, these IT-savvy employees may feel that they are exempt from using the IT investment process or perceive that employees with their competencies have not been taken into account when formulating the guidelines.

Although the current guidelines serve as a comprehensive catch-all, which can be suitable when the complexity of a situation makes it difficult to establish precise rules, the IT department should be cognisant of the image problem and the confusion generated by prominently displaying these guidelines on the intranet page for the IT investment process. This prominence can overwhelm readers or appear condescending.

#### Humanise the IT investment process

Interview data and ethnographic observations indicate that the IT investment process suffers from an image problem. To counteract this perception, steps should be taken to make the process more approachable. In the following sections, I will cover possible ways of achieving this.

##### Renaming the process

Many interviewees unfamiliar with the IT investment process commented on its name. The lengthy Danish term, consisting of twenty-three letters, appeared bureaucratic and unappealing. A name like "Indkøbsguiden" (Danish for "The Purchase Guide") was suggested as an alternative, appealing more to the grassroots level of the organisation.

##### Cater to the needs of diverse employee groups

The IT investment process should accommodate the requirements of various employee groups who may be hesitant to use the process. Allowing employees to choose a preferred architect when completing the form could provide peace of mind to those dealing with sensitive IT investments, such as daycare workers with unique needs.

##### Clarify the purpose and advantages of using the IT investment process

Interviewees viewed the IT investment process as bureaucratic and struggled to understand its benefits compared to directly contacting the IT department. The IT department should use the intranet site to clearly explain the purpose of the IT investment process, emphasising the "why" rather than relying on coercive language about city council mandates.

#### Attempt to unify reporting with other parts of the organisation

One significant issue raised in the interviews was the non-uniformity of reporting processes across the organisation. Other departments have their own reporting requirements for various cases of investments, such as new welfare technology investments and new systems integrating with the municipality's payroll system. This complexity creates a challenging environment for employees to navigate when investing in new systems.

Although this complexity currently hinders the adoption of the IT investment process, there is potential to transform it into a strength by initiating dialogue to unify reporting requirements across the organisation. A unified reporting system could simplify communication about the importance of reporting new investments and improve overall compliance.

This unified system would serve as a one-stop shop for all new investment reporting. A streamlined set of questions would automatically identify which departments should be informed of the new investment based on the responses provided, allowing IT and other departments to collaborate rather than compete for employees' attention.

Implementing such an approach presents challenges, including fostering cooperation between separate working groups. However, given the shared difficulties arising from poorly executed investment reporting (as exemplified by Anne's interview), there should be common ground for collaboration.

A potential solution is a standardised form asking relevant questions about the investment, such as access requirements to payroll systems and municipal networks. Based on the responses, the form would determine which responsible parties within the organisation need to be informed of the specific investment in question.

#### Ease restrictions where possible

While information and cyber security are crucial, it is also essential to strike a balance. Decentralised employees may perceive strict restrictions on user privileges as excessive burdens, potentially affecting their job satisfaction and sense of agency. It is essential to consider that decentralised IT specialists, although not part of the central IT department organisationally, are still IT experts and likely possess the necessary knowledge and skills to manage their tasks responsibly.

By easing restrictions where possible, a more balanced approach can be achieved, ensuring that decentralised employees, particularly IT specialists, feel trusted and empowered within the organisation.


### Opportunities for Future Research
#### A more extensive investigation of practice in other municipalities
In the current study, the primary focus was on investigating practices within Vejle municipality, with only a few observations made about how other municipalities handled new IT investments. Future research should take a closer look at the practices in other municipalities and assess their effectiveness to attempt to understand what the best practice is within municipalities in the present day. To a certain extent, it could also be helpful to examine the private sector's practices. Although the public sector is fundamentally different from the private sector, IT departments in medium and large private sector companies might face similar challenges to the IT department in Vejle, making it worth investigating.

To explore other municipalities, it would be beneficial to utilise existing connections between Vejle and other municipalities, for example, Aarhus, Odense, Fredericia, Sønderborg, and others.

#### A closer look into the IT investment process through the lens of managerial science
Although the current research employs an ethnographic methodology to explore the challenges associated with the IT investment process, primarily from a user perspective, integrating insights from experts in communication and managerial science may prove invaluable for developing tailored communication strategies and action plans.

By incorporating principles from managerial science, researchers could systematically examine the decision-making processes, resource allocation, and performance measurements affecting the IT investment process at Vejle Municipality. This approach can help identify inefficiencies, misaligned incentives, and other potential barriers to effective IT investment management.

Moreover, communication specialists can contribute to the development of targeted communication plans, providing guidance on the most effective methods to convey information, promote collaboration, and foster a culture of transparency and accountability. These experts can also identify potential communication gaps and recommend strategies to bridge them, ensuring that all stakeholders understand their roles, responsibilities, and the overall goals of the IT investment process.

Additionally, an interdisciplinary approach that combines these ethnographic findings with insights from managerial science and communication expertise can lead to a more comprehensive understanding of the problems facing the IT investment process. This holistic perspective can facilitate the identification of key factors influencing employee behaviour and organisational culture, thereby enabling the development of evidence-based interventions to improve the IT investment process within the municipality.

# GPT-4's Utility in Qualitative Research
The present chapter aims to investigate the capabilities of GPT-4 in creating affinity diagrams by comparing its performance to that of a human ethnographer. Affinity diagrams are valuable tools for organising and understanding vast amounts of information; given GPT-4's capacity to process large amounts of text, it presents a unique opportunity to evaluate the language model's effectiveness in creating affinity diagrams.
## Technical Background
The following sections provide a technical background designed to enhance the understanding of LLMs, specifically focusing on their architecture, training process, and operational mechanisms, delving into the principles of inferential text completion, tokenisation, token-based pricing, and the importance of prompt engineering in eliciting emergent abilities from LLMs. 

While this background aims to build a strong foundation for understanding the chapter that follows, it is worth nothing that the complexity and depth of the subject at hand does not allow for an exhaustive coverage in this brief overview. Further reading and resources are cited throughout to provide a more detailed exploration of these topics. It is encouraged to delve into these sources for a deeper and more nuanced understanding of the intricacies of LLMs.

### GPT-4's Unique Architecture

With OpenAI's debut of the GPT-4 model, a pioneering advancement was realised in the form of its multi-modal capabilities. The model is distinguished by its ability to process not only text data but also images [@openai2023gpt4]. The current study, however, is restricted in its scope as the image module of GPT-4 has yet to be fully released to the public. Therefore, I will solely focus on examining the text-processing proficiency of this LLM.

### Transformer Architecture

LLMs are generally based on a Transformer architecture, first introduced in @vaswani2017attention. Transformers are characterised by their self-attention mechanism, which allows the model to weigh different parts of the input sequence in relation to each other. This mechanism enables the model to capture long-range dependencies and context more effectively than traditional recurrent neural networks or convolutional neural networks [@vaswani2017attention].

### Training Process

The training of LLMs involves two primary steps: pre-training and fine-tuning. During the pre-training phase, the model learns a general understanding of language by predicting missing words or tokens in a sequence (also known as masked language modelling). This is achieved by feeding the model a vast amount of text data from diverse sources, such as books, articles, and websites [see, for example, @devlin-etal-2019-bert]

After pre-training, the model typically undergoes some sort of fine-tuning phase, during which it is further trained on a smaller, task-specific dataset. This enables the model to acquire specialised knowledge and skills related to the target task, such as question-answering, translation, or summarisation [@devlin-etal-2019-bert].

### Inferential text completion
Inferential text completion serves as the fundamental task carried out by LLMs in the context of current research. This task entails generating coherent, contextually relevant, and human-like text by continuing a provided prompt based on learned linguistic patterns and contextual information. Owing to their ability to perform this task, LLMs are well-suited for various applications such as content generation, summarisation, and conversation.

Understanding the basics of inferential text completion requires delving into the underlying principles that govern the process. LLMs are trained on vast amounts of text data, enabling them to recognise and predict complex patterns in human language. These models employ a probabilistic approach, calculating the likelihood of different tokens appearing in sequence based on their acquired knowledge.

![f10b3c1eb732c9953e5b53325a794140.png](f10b3c1eb732c9953e5b53325a794140.png)
![9a74d7ae20c0fe20e10b681f0900e59a.png](9a74d7ae20c0fe20e10b681f0900e59a.png)

Figure X offers an example of inferential text completion using an older model, such as text-davinci-003. In this figure, the model is prompted with the letter "I," and its inference process is displayed. Individual tokens are separated and color-coded according to their likelihood of being the next text in the sequence. For instance, the token "feel" had a 0.47% probability of appearing next (Figure X). The hyperparameter, temperature, plays a vital role in controlling the model's randomness. As the temperature approaches 0, the model's output becomes increasingly deterministic, while higher temperature values (up to a maximum of 1) yield more varied results, often selecting less likely inferences.

However, in certain cases, despite having a good prompt, the model may produce lower quality or irrelevant output due to the influence of the temperature parameter or other stochastic factors. This phenomenon, referred to as "output degradation" or "response deviation," occurs when random chance from the temperature parameter leads the model in a direction of generating low-quality output [@Holtzman2020The]. A well-known type of response deviation is "hallucination," where the models yield information that is either irrelevant to the context or non-factual.

As suggested in @Holtzman2020The, the quality and relevance of the generated text can be improved by fine-tuning hyperparameters such as temperature and top-k. These parameters influence the model's token selection. A lower temperature value results in more deterministic output, while a higher value promotes exploration and creativity. Similarly, the top-k parameter limits the model to consider only the k most probable tokens for each position in the text, striking a balance between diversity and coherence.

In the current research, temperature values between 0.5 and 0.7 are typically used, as they are generally considered to strike an optimal balance between diversity and coherence.

#### Chat Completions
The present study utilises what OpenAI calls chat completions. In chat completions, there are three types of messages: system, user, and assistant; under the hood, this works the same as a normal inferential text completion, where the messages are passed to the model in plaintext [@openaiChatCompletions].

Unless marked otherwise, all prompts mentioned in the following sections were injected into the conversation as a system message, which, according to documentation in @openaiChatCompletions, helps guide the AI's behaviour. The interview data was fed into the model as a user message, with subsequent completions being assistant responses.

### Tokenisation

Tokenisation is a crucial aspect of LLMs, as it serves as a pre-processing step that converts raw text into a format that can be processed by the model. In this process, the text is broken down into smaller units called tokens, which can be words, subwords, or individual characters [@vaswani2017attention]. The choice of tokenisation strategy can significantly impact the model's performance, as it determines the granularity at which the model processes and generates text. LLMs typically use subword tokenisation methods, such as Byte Pair Encoding (BPE) or WordPiece, which strike a balance between capturing meaningful linguistic units and maintaining a manageable vocabulary size [@vaswani2017attention].

### Token-based pricing model
Token-based pricing is the methodology employed by OpenAI to determine the cost associated with utilising their language models. It is based on the principle that the length of text processed, measured in tokens, corresponds to the computational resources and time required for model inference.

In OpenAI's pricing structure, a token represents a discrete unit that includes characters, spaces, words, punctuation marks, and other linguistic components. Longer inputs or passages generally contain a greater number of tokens, leading to increased computational expenses.

OpenAI's token-based pricing accounts for the number of tokens used in both the input (prompt) and output (response) phases of an interaction. The total tokens include those in the provided input and those generated by the model in its response. Repetitive tokens within an interaction, such as duplicated prompts or recurring phrases, are counted as individual tokens.

Customers are billed based on the total number of tokens utilised during the interaction, covering both input and output tokens. The cost per token remains consistent across different use cases and applications. This pricing structure ensures that the computational resources consumed by language models are appropriately considered, allowing for transparent cost estimation based on the complexity and length of text processed.

### Prompt engineering and emergent abilities

Prompt engineering is crucial for achieving high-quality results with LLMs and plays a pivotal role in uncovering their emergent abilities. By developing and optimising prompts, researchers can efficiently harness LLMs for various applications and research topics, gaining a deeper understanding of the models' capabilities and limitations \[@dair.aiPromptEngineeringGuide2023\].

The process involves selecting appropriate text prompts, tuning the model's hyperparameters, and tailoring the prompt design to the model's capabilities. The primary objective is to provide sufficient context for high-quality results while avoiding incorrect or irrelevant outputs. Prompt engineering is particularly important in discovering emergent abilities, as it enables researchers to probe and explore the models' potential in novel and unexpected ways [@wei2022emergent].

Emergent abilities, which cannot be reliably inferred by merely extrapolating smaller models' performance, often become apparent only after the LLM has been publicly deployed. As researchers experiment with various prompts and explore different applications, they may uncover previously unnoticed capabilities. In this sense, prompt engineering serves as an essential tool for investigating the full potential of LLMs, leading to the discovery of emergent abilities and fostering a better understanding of their implications \[@wei2022emergent\].

By carefully crafting prompts and iterating on them based on the model's responses, researchers can push the boundaries of LLMs and uncover emergent abilities that may not have been apparent otherwise. This iterative process allows for the identification of novel capabilities, contributes to the ongoing development of LLMs, and informs the design of future models.

Recent research points to significantly improved outcomes in reasoning tasks when models are prompted to produce a chain-of-thought [@weiChainThoughtPrompting2022; see also, @richardsAutoGPTAutonomousGPT42023; @weiArtificialStreamThought]. A recent study took this approach a step further, tasking GPT-4 to self-critique its own outputs, further improving the quality of the results [@shinn2023reflexion].

In the current study, the Prompt Engineering Guide from @dair.aiPromptEngineeringGuide2023 was used as a valuable resource, offering a repository of state-of-the-art methods and techniques. This guide, combined with a thorough understanding of the models' inner workings and careful prompt engineering, enabled the effective exploration of emergent abilities and the leveraging of LLMs for qualitative research purposes.

### Ethical Considerations
Before embarking on the use of LLMs in research, it is imperative to acknowledge the ethical implications that they present. The dependability and precision of an LLM's responses are inherently tied to the quality of the data used in its training process. Consequently, these models have the potential to unintentionally reinforce the biases present in their training data. To effectively incorporate LLMs into humanities research, it becomes paramount to thoroughly examine these tools and devise strategies to mitigate potential biases.

However, it is equally important to recognise that humans are not exempt from biases, which are influenced by their own 'training data', such as personal experiences, memories, and knowledge. As humanities researchers, we have a keen understanding of how our biases can shape our interpretation of the world. We are adept at navigating these intricate issues and can apply this critical thinking to the employment of LLMs.

## Literature Review
### Effects of simultaneous instruction overload on GPT-4 performance
Research published since the completion of the data collection of the present study indicates that GPT-4 may struggle when faced with numerous instructions simultaneously. The model's performance appears to deteriorate when it is asked to execute too many tasks at once, which bears similarities to how humans can become overwhelmed by an abundance of instructions. This phenomenon may provide some explanation as to why the model failed to generate satisfactory results when it was asked to produce critiques and iterate upon them within a single, comprehensive prompt.

For example, the self-critique prompt from @hebenstreit2023automatically, which instructs the model to "Answer the question, then critique the answer. Based on the critique, reconsider the other answer options and give a single final answer," performed on par with direct prompting. In direct prompting, the question is asked without any additional instructions. This outcome is surprising because the self-critique strategy has been demonstrated to yield improved results in other contexts, as highlighted by @shinn2023reflexion.

Opportunities for using this knowledge to remedy problems encountered in the present research will be covered later in the present chapter together with other opportunities for future research.

## Methodology
### Data Collection: User-Model Interfaces
My research endeavour focused on identifying the optimal method to interact with GPT-4. I was particularly interested in the user-model interface, which serves as the frontend mechanism to facilitate interaction between humans and the model's functionalities. To suit my research needs, I required an interface that could support chat functionality, allowing me to manually control the model's inputs and outputs as much as possible.

Initially, I engaged with ChatGPT, the official platform from OpenAI that provides access to GPT-3.5, and limited access to GPT-4 for subscribed users. However, I soon discovered limitations with this platform that posed constraints on my research. The most critical limitation was that the interface of ChatGPT did not support large input sizes, which was an essential requirement for the goals of the present study.

In search of a more suitable solution, I turned to the OpenAI's developer playground. This platform catered to my needs in a much more satisfactory manner. It allowed me to exploit the 8,000-token capacity of GPT-4 and provided me with the flexibility to actively steer the model's responses. I could edit outputs, tweak hyperparameters, and alter the system prompt to assume specific roles, such as that of an ethnographer. Despite its many advantages, the developer playground fell short on user-friendliness, particularly when it came to saving and referencing chats.

The final stage of my quest led me to the GitHub project "Chat with GPT" from @cogentappsChatGPT2023. This platform offered an ideal amalgamation of the user-friendly aspects of ChatGPT and the granular control offered by the developer playground. It facilitated communication with OpenAI's servers via an API key, providing an efficient and intuitive interface for interacting with GPT-4.

Despite the existence of a more robust 32,000-token variant of GPT-4, I did not have access to this version during the course of this research.

### Data Collection: Iterative Prompting
The present subsection will explore the development of a "zero-shot" prompt for creating affinity diagrams from interview data. Zero-shot prompting refers to the model's ability to perform a task without being shown specific examples of how to complete the task. While it is possible that some affinity diagrams were a part of the model's training data, this likely does not make up very much of the training data, as affinity diagrams are usually represented in image data, which GPT-4's LLM module is not trained on. So, the particular task of outputting an affinity diagram as a text output is likely not something the model has been trained on. although, as the training data used is not told to the public, there is no way to be truly sure.

Prompt engineering plays a crucial role in optimising the performance of language models, including GPT-4. This section discusses the approach to prompt engineering, aiming to achieve high-quality results. With GPT-4's enhanced capacity to understand and assist with meta-tasks, such as refining its own prompts, there is potential for streamlining the prompt engineering process without compromising its efficacy, thus further reducing workload.

Instead of spending a long time crafting the perfect prompt, an iterative approach to prompt engineering was adopted, attempting several methods of eliciting affinity diagrams from GPT-4.

#### The Direct Prompting Approach

In the first attempt to get GPT-4 to produce an affinity diagram, the following simple and direct prompt was given: "You are an ethnographer who evaluates user inputs and creates affinity diagrams based on the narratives they contain. Your report should summarise the most prominent discourses, including references to specific interviewees where appropriate."

Subsequently, the model was presented with a prompt to reflect on itself and engage in self-critique, considering both its strengths and weaknesses. The resulting conversation, including the raw outputs, is as follows:

>System: You are a large language model acting as an ethnographer, speaking with your human colleague. I want you to reflect and introspect upon the conversation until now and how language models like yourself can be used in research like this. Take into account both your strengths and weaknesses.

The dialogue that ensues suggests that GPT-4 possesses the capacity to scrutinise its inherent biases as a language model (available in full in Appendix X). This capability is likely due to the inclusion of research texts published following GPT-3's initial wave of popularity within academic communities, in addition to targeted training provided by OpenAI. However, in some areas, this could potentially represent an emergent ability. The precise origins remain elusive due to the "black-box" nature of Large Language Models (LLMs) and the absence of comprehensive knowledge regarding GPT-4's training data and fine-tuning process.

Contrasting with human cognition, where language and reasoning centres reside within distinct regions of the brain \[@mahowaldDissociatingLanguageThought2023; @valmeekamLargeLanguageModels2022\], GPT-4, when tasked with generating an affinity diagram, doesn't formulate a plan prior to initiating its writing process. Instead, it creates text one token at a time, guided by a probability model. In the subsequent section, we will explore the simulated-thought approach, aiming to enhance both interpretability and the overall depth of analysis through a chain of thought methodology.

#### The Chain of Thought Approach

In this section, we introduce the simulated-thought approach adapted for creating affinity diagrams using GPT-4. The primary purpose of this approach is to elicit more detailed and reasoned outputs from the model, thus achieving in-depth ethnographic analysis. We will discuss its application, design, challenges, and evaluation in the subsequent sections.

##### Background and Motivation

The simulated-thought approach is often employed for reasoning tasks in LLMs, having shown to yield higher quality results measured on criteria of accuracy and interpretability [@weiChainThoughtPrompting2022; see also, @richardsAutoGPTAutonomousGPT42023; @weiArtificialStreamThought; @jsalsmanItEasyGive2023]. Although ethnographic analysis is more complex than the reasoning tasks explored in the aforementioned studies, the simulated-thought approach has demonstrated promising outcomes in enhancing the analysis and interpretation of data generated by LLMs.

##### Prompt Design and Strategy

The key to optimising GPT-4's performance lies in iterative prompt engineering. To apply the simulated-thought approach to creating an affinity diagram, I designed a prompt that aimed to emulate human thought processes, such as detailed reflection and analysis. The prompt included sections for THINK and WRITE processes, simulating the way human ethnographers contemplate and record their observations, respectively. The final adapted simulated-thought prompt is as follows:

>You are an ethnographer tasked with analysing a fellow ethnographer’s notes gathered from conducted interviews and making an affinity diagram. Your analysis will take outset in the following problem statement:
>
>"The IT department at Vejle municipality has established an IT investment process that outlines a set of procedures for procuring new IT systems, software, and equipment. Despite these guidelines, employees do not always follow this process, leading to potential inefficiencies and discrepancies in IT investments. This study aims to explore the reasons why employees do not comply with the IT investment process and suggest strategies to improve compliance."
>
>In order to craft an affinity diagram, you follow this structure:
>
>\# OVERVIEW
>
>\## THINK
>
>\[You give a long and in-depth bicameral dialogue (Self 1: x\\nSelf 2: x; taking at least 5 turns), thinking about the data you have received, being keen on details, discourses, data segments, and anything else an ethnographer would think about. Let any ideas that come to you flow out here.]
>
>\# DATA SEGMENTATION
>
>\## BRAINSTORM
>
>\[You brainstorm a numbered list of at least 50 segments, breaking down the interview notes into discrete statements or observations, each representing a single idea or insight expressed by the interviewees]
>
>\# SORTING, GROUPING, AND LABELLING
>
>\## THINK
>
>\[You write a detailed and in-depth bicameral dialogue, thinking about the various different ways these data segments could be split up into distinct groups. Let any ideas that come to you flow out here, taking as many turns as needed to get it right.]
>
>\## NOTEBOOK
>
[When you have thoroughly thought your ideas through, you write the groupings down here with appropriate names. Do not give them names yet.]
>
>\# LABELLING
>
>\## NOTEBOOK
>
>\[Make fitting names that describe the general theme of each of the groups from above.]
>
>\# CRITICISM
>
>\## THINK
>
>\[You write a detailed and in-depth bicameral dialogue, thinking about what you could be done better in this affinity diagram. Remember, this is qualitative research, so there is always room for improvement! Let any ideas that come to you flow out here]

For a more in-depth look into the iterative prompting process behind the aforementioned prompt, I have included a rough journal entry detailing parts of this process in Appendix X.

### Data Analysis: Criteria for Assessment of Output Quality
In the context of evaluating the output quality of affinity diagrams created by GPT-4, a holistic approach is taken, encompassing several definitive criteria. These ensure that the resulting outputs are not only accurate and relevant but also comprehensive, consistent, clear, unbiased, interpretable, and of significant utility.

The primary criterion is Accuracy, which emphasises the importance of the generated affinity diagram's fidelity relative to the raw interview data. This denotes that the output should appropriately and accurately organise and represent the data within its categories. 

Following Accuracy, we focus on the Relevance of the categories formed by the model in relation to the subject matter at hand. This involves ascertaining whether the categories formed carry meaningfulness and significance within the context of the original interview data. A critical assessment of relevance thus involves an in-depth analysis of the conceptual links between the raw data and the categories found in the generated affinity diagram.

Next, we consider the Completeness of the data incorporation into the affinity diagram. This criterion requires careful scrutiny to ensure no data from the interviews has been overlooked or excluded from the output. Completeness serves as an indicator of the thoroughness of the model's categorisation process. 

Consistency is the fourth criterion, evaluating the uniform application of criteria in grouping data by the model. It necessitates a close inspection of whether data points with similarities have been grouped in a comparable manner, thus indicating the model's interpretive and categorising consistency.

Clarity, the fifth criterion, assesses the readability and comprehensibility of the generated affinity diagram. The ease of understanding both the individual groupings and the overall diagram is a key aspect of this evaluation, often serving as a precursor to the usability of the output in subsequent research or decision-making processes.

The sixth criterion, Bias, explores the impartiality of the model during the data categorisation process. A careful examination of the model's potential inclination towards certain responses or categories without data-based justification is essential. This scrutiny aims to identify any unintentional distortions in data representation.

Interpretability is the penultimate criterion, and it encompasses the evaluation of the transparency and comprehensibility of the model's decision-making process. This pertains to understanding how the language model processes input data to produce an affinity diagram and determining whether this process is logically explainable. However, due to the complex nature of LLMs and their numerous parameters, interpretability is inherently limited [@openai2023gpt4]. These models, often considered "black-box" systems, pose a significant challenge in terms of interpretability.

Finally, we consider Utility, which assesses the practical usefulness of the generated affinity diagram. The potential of the output to yield insights that can be applied in further research or decision-making processes is central to this criterion. Utility, thus, serves as a measure of the actionable value of the model's output.

## Presentation of GPT-4 Output Data

### The direct prompting approach
The direct prompting approach yielded the following results, the prominent discourses serving as explanations of each of the diagram themes laid out:

> Affinity Diagram Themes:
>
> 1\. Understanding of the IT investment process
>
> 2\. Communication and collaboration with the IT department
>
> 3\. Challenges and frustrations in implementing new systems
>
> 4\. Suggestions for improvement

Then, the model gave a summary of prominent discourses in the data, as requested. Each of the numbers seem to correspond with the affinity diagram themes defined previously.

> Summary of Prominent Discourses:
> 1\. Many interviewees were not aware of the IT investment process or did not see the relevance to their work. For instance, Karina (Interview 165) did not think it was important for her role, while Anne (Interview 190) was not aware of the process before the interview.
>
> 2\. Communication and collaboration with the IT department were highlighted as crucial factors in the successful implementation of new systems. Lise (Interview 161) emphasized the need for understanding the specific context of daycare workers, while Peter (Interview 183) expressed concern about gaps in IT support at his residential care facility.
>
> 3\. Several interviewees described challenges and frustrations in implementing new systems, often due to a lack of communication and understanding between different departments or the IT department\'s perceived rigidity. Examples include Mikkel (Interview 169), who faced dilemmas when reconciling the municipality\'s network requirements with the library\'s separate organizational status, and Freja (Interview 189), who found the IT investment process bureaucratic and unhelpful.
>
> 4\. Suggestions for improvement included clearer communication about the IT investment process and its purpose, as well as more targeted promotion to specific departments that deal with IT investments. Emma (Interview 181) suggested changing the name of the process to make it more tangible, while Lise (Interview 161) proposed adding an option on the form to indicate if the case involves a target group with difficulty adapting to technological changes. Anne (Interview 190) suggested the development of a central system to direct communication based on guidelines, as well as establishing more fixed and transparent guidelines for reporting new investments within the organization.
>
> In conclusion, the most prominent discourses focused on the understanding and awareness of the IT investment process, the importance of communication and collaboration with the IT department, the challenges and frustrations experienced in implementing new systems, and suggestions for improving the process. Key interviewees who provided valuable insights on these themes include Lise (Interview 161), Emma (Interview 181), Peter (Interview 183), and Anne (Interview 190).

When asked to reflect upon its potential strengths and weaknesses, the model outputted the following:

>Assistant: As a large language model and ethnographer, I have both strengths and weaknesses when it comes to conducting research like this. 
>
>Strengths:
>
>1\. Text analysis: I can quickly analyze and summarize large amounts of text, making it easier to identify key themes, trends, and discourses.
>
>2\. Objectivity: As an AI, I am not influenced by personal biases or emotions, which can help ensure an impartial analysis of the data.
>
>3\. Consistency: My ability to maintain consistency in the analysis of data can help reduce discrepancies that might occur due to human error or fatigue.
>
>Weaknesses:
>
>1\. Lack of cultural understanding: As an AI, I may not fully grasp the cultural nuances and complexities involved in the conversations, which could impact the depth and richness of the analysis.
>
>2\. Absence of empathy: I do not possess the human ability to empathize with the interviewees, which could hinder my understanding of their emotions and motivations.
>
>3\. Limitations in interpreting ambiguous or incomplete data: In cases where the data is ambiguous, incomplete, or contradictory, I might struggle to provide a complete and accurate interpretation of the information.
>
>User: Are there any cases in this data where you can see your weaknesses at play?
>
>Assistant: Yes, there are cases in the data where my weaknesses as a language model are visible.
>
>1\. Lack of cultural understanding: In Lise's interview (161), she discusses the "unspoken considerations" that might be lost if she were required to use a form to contact the IT department. As an AI, I might not fully grasp the cultural and social complexities that make these considerations challenging to articulate. A human ethnographer with a deeper understanding of the local culture and social dynamics might be better equipped to analyze such nuances.
>
>2\. Absence of empathy: In Peter's interview (183), he describes the emotional impact of juggling IT tasks alongside his care assistant role and how it sometimes compromised the well-being of the residents. Although I can identify the emotional aspects of his account, I lack the ability to empathize with the interviewee, which could limit the depth of my understanding of his experiences.
>3\. Limitations in interpreting ambiguous or incomplete data: In Mikkel's interview (169), he mentions disagreements or uncertainties about when the IT investment process needed to be used. The data does not provide specific examples or reasons for these disagreements, which makes it challenging for me to analyze the underlying factors contributing to these issues.
>
>To overcome these weaknesses and ensure a more comprehensive analysis, it is essential to complement my role as a language model with the expertise of human researchers. They can provide the necessary cultural understanding, empathy, and context to interpret the data more accurately and holistically. Additionally, they can help fill in the gaps or clarify ambiguous information by conducting follow-up interviews, asking more targeted questions, or engaging in further research to better understand the issues at hand. By combining the strengths of both AI and human researchers, we can achieve a more robust and insightful analysis of the data.

Despite GPT-4 demonstrating an understanding of the concept of an affinity diagram, its output remained somewhat superficial, lacking the depth inherent in the context of the data. While its performance was commendable, the interpretability of its results could be enhanced.

In the human process of creating an affinity diagram, data is segmented and organised into a hierarchical structure based on themes and subthemes, following a mental process. Conversely, LLMs such as GPT-4 do not formulate a plan before producing tokens. Rather, the generation of tokens is sequential, based on the probability of the appearance of the subsequent word, as computed from the corpus of text on which the model was trained \[@mahowaldDissociatingLanguageThought2023; @brownLanguageModelsAre2020; @guoHowCloseChatGPT2023\].

### The simulated-thought approach
\

![The final affinity diagram generated by GPT-4 based on the interview data. A high-resolution version is available in Appendix X.](a79e7f23a4167279dd1e3af32e4313da.png "The final affinity diagram generated by GPT-4 based on the interview data. A high-resolution version is available in Appendix X.")
As previously discussed in this report, field notes from the interviews were input into GPT-4 along with a carefully-crafted prompt. A visual representation of the affinity diagram generated by the model can be seen in Figure X. At the moment, GPT-4 only processes text inputs and outputs, so the visual layout was created manually by transferring the AI-generated data into the same program used for the human-generated affinity diagram. While GPT-4 is expected to process images in the future, this feature is not yet available, and creating a visual layout would require more complex prompting. To save time, all sticky notes have been left yellow rather than colour-coded.

It should also be noted that the whole text output behind the affinity diagram in Figure X can be found in Appendix X.

GPT-4 divided the 50 data segments into five groups, with four relatively small groups and one larger group containing more than half of the data segments (26 in total). The raw output with the groupings is shown below, and the full raw output can be found in Appendix X.

>\## NOTEBOOK
>
>Group 1: Awareness and Understanding of IT Investment Process
>
>- Segments: 1, 2, 5, 10, 16, 32, 46
>
>Group 2: Communication and Relationships between IT Department and Other Departments
>
>- Segments: 3, 4, 11, 19, 20, 29, 30, 35, 42
>
>Group 3: Challenges and Barriers in IT Investment Process
>
>- Segments: 6, 7, 8, 9, 17, 22, 23, 24, 25, 26, 27, 28, 31, 33, 34, 37, 38, 39, 40, 41, 43, 44, 45, 47, 49, 50
>
>Group 4: Suggestions and Improvements for IT Investment Process
>
>- Segments: 12, 18, 21, 36, 48
>
>Group 5: Specific Contexts and Considerations in Different Departments/Facilities
>
>- Segments: 13, 14, 15, 16

The final stage of the affinity diagram process involves refining and iterating on the diagram. The AI model acknowledges a need for improvement in its self-critique:

>Self 2: Good point. We should also consider the depth of our analysis. Are there any themes or issues that we could explore further, or any connections between the groups that we haven't yet identified?
>
>Self 1: Yes, that's an important aspect to consider. Additionally, we could think about the clarity and consistency of our groupings. Are the group labels clear and descriptive, and do they accurately capture the content of the segments they contain?

In this quote, the model highlights the need for further iteration on the clarity of the groupings, including the issue of the large third group. The self-critique concludes with:

>Self 1: Great points. Let's keep all of these considerations in mind as we continue to refine our affinity diagram and analyse the data.

This suggests that the model could potentially run the entire process again, iterating and improving its work, which it has demonstrated its capability to do, for example in @shinn2023reflexion. However, due to the current token limit of 8,000 for GPT-4, this was unfortunately not possible at the time of writing as the prompt stands now. With access to a 32,000 token version of GPT-4, it is conceivable that the prompt could be modified to have the model iterate and yield higher quality results.

## Discussion

In the following sections, the results of the affinity diagrams generated by GPT-4 are discussed, focusing on identifying flaws and potential solutions.

### Defining output quality
Before discussing output quality, it is important to define the characteristics that define a high-quality output. These criteria, as detailed earlier in the present report, are as follows:

1.  **Accuracy**: The output should accurately represent the data from the interviews. The model should be able to correctly interpret the responses and group them appropriately.
    
2.  **Relevance**: The groups or categories formed by the model should be relevant to the topic at hand. If the categories don't make sense in the context of the interview data, this could indicate a problem with the model's interpretation.
    
3.  **Completeness**: All data from the interviews should be represented in the affinity diagram. If any data is missing or has been overlooked, this could affect the overall findings.
    
4.  **Consistency**: The model should consistently apply the same criteria when grouping data. If some data is grouped differently than similar data, this could indicate an issue with the model's algorithm.
    
5.  **Clarity**: The affinity diagram should be easy to understand. If it's too complex or the groupings are not clear, this could make it difficult for users to interpret the results.
    
6.  **Bias**: The model should not exhibit any bias in its grouping of the data. This means it should not favor certain responses or categories over others unless there's a valid reason to do so based on the data.
    
7.  **Interpretability**: The model's decision-making process should be transparent and understandable. This allows users to trust the results and understand how the model arrived at them.
    
8.  **Utility**: The generated affinity diagram should provide useful insights that can guide decision-making. If the output is not actionable, its utility is limited.

### The Direct Prompting Approach

The resultant affinity diagram from the direct prompting approach didn't necessarily adhere to the typical structure associated with such diagrams, which usually entail small, data-rich segments presented on sticky notes. Despite this, the model utilised the interview data factually and accurately, subject to its inherent limitations. Similar to the simulated-though approach, it was evident that the model fell short in grasping the organisational context surrounding Vejle Municipality and the IT investment process. The output, for ease of interpretation, has been reformatted and summarised as follows:

> 1.  **Understanding of the IT investment process**: Several interviewees, including Karina (Interview 165) and Anne (Interview 190), either lacked awareness of the IT investment process or didn't view it as pertinent to their work.
> 2.  **Communication and collaboration with the IT department**: The crucial role of communication and collaboration with the IT department in successfully implementing new systems was underscored. Lise (Interview 161) stressed the importance of understanding the specific context of daycare workers, while Peter (Interview 183) flagged concerns about gaps in IT support at his residential care facility.
> 3.  **Challenges and frustrations in implementing new systems**: A number of interviewees articulated their challenges and frustrations in implementing new systems. These were often attributed to communication gaps and misunderstandings between different departments or a perceived rigidity of the IT department. Mikkel (Interview 169) and Freja (Interview 189) were among those voicing such concerns.
> 4.  **Suggestions for improvement**: Proposals for improvement included enhanced communication regarding the IT investment process, targeted promotion to specific departments dealing with IT investments, and changes to the process name for increased tangibility. Suggestions for a more streamlined form, a central system to guide communication, and transparent guidelines for reporting new investments were also made.

#### Accuracy

The model's misinterpretation of Peter's concerns about IT support at his residential care facility, which are not strictly within the remit of the central IT department, highlights a crucial misunderstanding. This underscores the model's deficiency in fully understanding the organisational context. However, this appears to be a singular error in an otherwise accurate output, leading to a moderate rating in accuracy.

#### Relevance

All groupings made by the model were pertinent to the data, hence the relevance of the output is deemed high.

#### Completeness

The model demonstrated significant shortcomings in the completeness of its output, failing to fully utilise the depth of the data at its disposal. Therefore, the completeness of the output is assessed as low.

#### Consistency

No apparent issues with consistency of groupings were observed in the model's output, leading to a high consistency rating.

#### Clarity

The output was presented in plain, easy-to-understand language, securing a high rating for clarity.

#### Bias

Given the limited data output and the inherent lack of interpretability, it's challenging to detect any bias. However, nothing suggestive of bias is apparent. The context of the interviews doesn't encompass controversial elements present in the model's training data, making it highly probable that no significant bias is in play.

#### Interpretability

The 'black-box' nature of large language models (LLMs) offers limited insight into the decision-making process behind the output. Consequently, the interpretability of the output is rated as low.

#### Utility

For an individual unfamiliar with the data, the output could provide a quick overview. However, from a researcher's perspective, the output doesn't add anything novel to the existing understanding. It fails to provide insights that couldn't be quickly jotted down manually. Therefore, the utility of the approach is judged to be low to moderate.

### The simulated-though approach
The simulated-thought approach used in the present study could be argued to have attained a deeper level analysis, but other key problems arose from the design of the prompt, particularly in the area of grouping strategy.

#### Accuracy

Accuracy refers to the extent to which the model correctly interprets the data and assigns them to appropriate groups.

For instance, the model identified data segments from the interview data but incorrectly associated them with the wrong interviewee.

For example, data segments belonging to Interviewee 163 (Søren) were mistakenly attributed to Interviewee 165 (Karina). This misattribution could have occurred due to the model identifying individual digits as separate tokens, allowing it to inadvertently select the wrong number.

> 22\. Difficulty in sticking to assigned roles in decentralized IT support (Interviewee 183)
>
> 34\. Difficulty in sticking to assigned roles in decentralized IT support (Interviewee 190)

This issue could be mitigated by using pseudonyms rather than numbers to identify interviewees or by choosing single-digit numbers to reduce the chance of error.

Furthermore,

Based on these findings, the accuracy of the generated output can be judged to be moderate to high.

### Relevance

Relevance refers to the degree of alignment between the model's output and the subject or context in question. In the case of the current analysis, relevance can be evaluated based on how accurately and appropriately the model grouped data segments under the right categories in the context of the IT investment process.

In some instances, the model made a significant departure from the real context, placing certain data segments under groups that were not directly related to the IT investment process. For instance, the model misclassified the data segment "Fear of data breaches and restrictions" and placed it under "Suggestions and Improvements for the IT Investment Process". While this segment is an important consideration for IT management, it is not a suggestion or improvement for the IT investment process per se.

Similarly, "Cost-saving attempts in decentralised IT support" was also placed under "Suggestions and Improvements for the IT Investment Process". This segments, while important in the broader context of IT management, do not directly pertain to the process of IT investment. Decentralised IT support is generally not involved in the central IT investment process, and while having a dedicated IT staff member is beneficial for a variety of reasons, it is not directly tied to the IT investment process.

These misclassifications indicate that the model seems to have made assumptions about the IT investment process without fully understanding the context in which the process operates. Instead of interpreting the data segments based on their inherent meaning, the model appears to be relying on superficial connections, possibly based on the co-occurrence of keywords.

This behaviour might indicate a gap in the model's understanding of the context. This is where a dialogue-based approach can potentially help. By allowing the researcher to interactively guide the model through the data analysis process, a dialogue-based approach can improve the model's understanding of the context, leading to a more relevant classification of data segments. The researcher can correct the model's misconceptions, clarify ambiguities, and provide additional contextual information to help the model make more accurate and relevant classifications.

### Completeness

Completeness refers to the representation of all data from the interviews in the affinity diagram. While the model demonstrated an extensive data segmentation process, certain context and subtext did not transition from the interviews into the notes. A dialogue approach could potentially bridge this gap, allowing for a deeper exploration of the underlying themes and complexities of the data.

### Clarity!!

Another aspect of accuracy is the correct classification of data segments into groups. However, similarly to the direct prompting approach, some segments were correctly identified but misplaced into unrelated groups. For example, data segments like "Fear of data breaches and restrictions", "Cost-saving attempts in decentralised IT support", and "Importance of having a dedicated IT staff member" were wrongly placed under "Suggestions and Improvements for the IT Investment Process", even though they were not related to the IT investment process in context.

Furthermore, the model placed a repeated data segment, "Need for more effective communication of the IT investment process", in two different groups: "Awareness and Understanding of the IT Investment Process" and "Challenges and Barriers in IT Investment Process". This redundancy indicates that the groups created might not be entirely distinct or meaningful.

Starting from the 25th data segment, the model displayed a tendency to duplicate previously identified data segments but with incorrect attributions to the interviewees. This behaviour might stem from the model's inherent capability for pattern recognition, causing it to persist with an established pattern even when it leads to errors. Additionally, this could be attributed to the demanding nature of the prompt, which required the generation of fifty data segments, presenting a challenging task for the model. Although the model fulfilled the explicit request, it overlooked the implicit requirement for the data segments to be distinct.

### Consistency and Clarity

Consistency and clarity in data grouping are vital for meaningful analysis. In this experiment, however, the model demonstrated a tendency to prematurely conclude the bicameral dialogue. This behaviour might stem from the patterns established earlier in the output. Consequently, the model's groupings were often not detailed enough to make meaningful connections in the data. Ideally, the two 'selves' in the bicameral dialogue would offer constructive critique of each other's ideas. However, instead of this ideal, they frequently gave noncritical feedback such as "good idea", indicating that the bicameral dialogue approach as it stands may provide more challenges than advantages.

In terms of clarity, the model's understanding of the context surrounding the IT investment process seemed limited. For instance, Group 3, "Challenges and Barriers in IT Investment Process", acted as a catch-all category, housing many data segments that could have been more evenly distributed with better context understanding. This is where a dialogue-based approach, involving the researcher conversing with the model, could be beneficial. The model could pose thought-provoking questions about the case, allowing the researcher to share the context intuitively, much like one would with a human researcher. This dialogue could potentially enable the model to make more meaningful connections in the data than what can be achieved by just inputting the raw data.

Further, modifying the prompt to make the model provide meaningful critiques of its decisions could potentially improve the consistency and clarity of the final outputted affinity diagram. Studies by @hebenstreit2023automatically and @shinn2023reflexion suggest that self-critique approaches are more fruitful if executed as separate requests to the API rather than included in a single extensive prompt. This could explain the lack of critical feedback in my experiments. It appears that the model, when given a new request, can get a fresh perspective, having its parameters cleared and reset. While anthropomorphising LLMs is generally not accurate, it seems that starting a new output sequence gives the model a refreshed "perspective" on the task.

### Interpretability

LLMs are often likened to "black boxes" due to the difficulty in understanding how they reach their conclusions. The reasoning typically occurs within the parameters behind the output, which isn't readily accessible. However, chain of thought approaches, like the one employed in this study, can enhance the model's performance on reasoning-based tasks and improve the interpretability of the output. It allows the researcher to follow the model's logic, checking it at every stage.

While the bicameral dialogue approach used in this study improved the interpretability of the output, it's unclear whether this method offers any advantages over a standard chain of logic approach, as featured in contemporary studies \[e.g., @hebenstreit2023automatically; @shinn2023reflexion\]. 

### Bias

The model's output did not appear to contain any bias. However, the premature termination of the bicameral dialogues in the think sections could potentially introduce bias in the output. A dialogue approach could help mitigate this bias.

### Utility

The output of the model should provide actionable insights. While the model segmented the data extensively, it did not delve into the potential implications of the identified themes and issues. An explicit description of the IT investment process, coupled with a dialogue-based approach for a deeper exploration of the data, could help enhance the utility of the model's output.

### Opportunities for Future Research
This study identified a significant challenge, which hindered further prompt iteration and refinement of the model's output, specifically the escalating token cost. The more tokens the model is prompted with, the higher the cost for executing the request. Submitting a prompt containing the entire interview data already utilises a substantial number of tokens. Including both the interview data and the affinity diagram generated by the model in a new request would further increase the expense. While these costs might be negligible in certain contexts, they can rapidly escalate to become a considerable financial burden for small-budget projects, such as a master's thesis which is self-funded by the researcher.

Given these considerations, future research could explore alternative ways to structure and sequence prompts for GPT-based affinity diagrams. As indicated in comparing results attained in @hebenstreit2023automatically and @shinn2023reflexion on question-answering tasks followed by self-critique, dividing the prompt into smaller segments and inputting them sequentially might prove to be a more effective strategy for achieving better results. This approach could potentially mitigate the model's performance degradation when it is faced with an excessive number of tasks in one prompt, in this example outputting an answer as well as self-critique, thereby improving the overall quality of the output.

# Conclusion

## Summary of Findings

## Implications of Research

# References
<div id="refs"></div>