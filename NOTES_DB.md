<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Anger, Michael, Christian Wendelborn, Eva C. Winkler, and Christoph Schickhardt. “Neither Carrots nor Sticks? Challenges Surrounding Data Sharing from the Perspective of Research Funding Agencies—A Qualitative Expert Interview Study.” Edited by Frederick Grinnell. PLOS ONE 17, no. 9 (September 7, 2022): e0273259. https://doi.org/10.1371/journal.pone.0273259.

Notes: 
- Interviews about the chalenges of data sharing from the perspective of funding agencies (see Table 1 in article for summary). 
  - Challenge I: Design of clear data sharing policies and concrete requirements
  - Challenge II: Monitoring of compliance with data sharing policies
  - Challenge III: Sanctions for non-compliance with data sharing policies
  - Challenge IV: Incentives for data sharing
  - Challenge V: Support and guidance for data sharing
  - Challenge VI: Limits to the capabilities of funders

Comments: 
- Interesting paper in the context of ArcticNet in particular
- Offer great insights into data sharing from a funder's perspective, which could be directly linked to ArcticNet's policy and practice with regars to data management. We could discuss each of these challenges and mention how ArcticNet is attempting to address them
- There are a lot of citations from interviews in the text that could be directly used in a webinar. 

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Aryani, Amir, Marta Poblet, Kathryn Unsworth, Jingbo Wang, Ben Evans, Anusuriya Devaraju, Brigitte Hausstein, Claus-Peter Klas, Benjamin Zapilko, and Samuele Kaplun. “A Research Graph Dataset for Connecting Research Data Repositories Using RD-Switchboard.” Scientific Data 5, no. 1 (May 29, 2018): 180099. https://doi.org/10.1038/sdata.2018.99.


Notes: 
- Seems to revolve around a network composed of links between datasets, publications, researchers and grants, and centered on datasets. 

Summary from ChatGPT: 
- The article “A Research Graph dataset for connecting research data repositories using RD-Switchboard” (Aryani et al., 2018) presents an open-access graph dataset that interlinks datasets, publications, researchers, and grants across multiple research data repositories using the RD-Switchboard platform. This initiative enhances research visibility, fosters collaboration, and facilitates data discovery and reuse. 
- RD-Switchboard creates a graph-based infrastructure that links research objects based on shared identifiers such as DOIs, ORCIDs, and grant PURLs.
- The Research Graph is built through:
	1.	Metadata Harvesting: Collects metadata from major data providers (e.g., Dryad, CERN, ANDS) using OAI-PMH, and integrates ORCID, CrossRef, and DataCite records.
	2.	Inference Engine: Establishes relationships between nodes using identifiers, Google API searches, and fuzzy title matching. Connections are labeled as either authoritative (“knownAs”) or inferred (“relatedTo”).
	3.	Metadata Harmonization: Merges nodes sharing identifiers to simplify the graph and resolve metadata conflicts, using trusted sources like CrossRef as authoritative.
- Graph Features
	-	Composed of over 4 million nodes: 2.8M publications, 1.08M researchers, 144k datasets, and 55k grants.
	-	Contains ~2.8 million bidirectional relationships.
	-	Enables tracing indirect links across entities (e.g., datasets linked via common authorship or shared grants).
	-	Structured using the Research Graph metamodel for compatibility with systems like VIVO and Scholix.
- Applications
	-	Enhances discoverability and reuse of data.
	-	Facilitates reproducibility and new interdisciplinary insights.
	-	Supports data visualization and network analysis using tools like Gephi.
	-	Enables filtering and querying based on metadata sources and relationships.

Comments:
- Interesting initiative, but it looks like it was not maintained at all. 

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Aurich, Dagny, and Aida Horaniet Ibañez. “How Can Data Visualization Support Interdisciplinary Research? LuxTIME: Studying Historical Exposomics in Belval.” Frontiers in Big Data 6 (September 29, 2023): 1164885. https://doi.org/10.3389/fdata.2023.1164885.

https://luxtimemachine.uni.lu/

Summary from ChatGPT
- The article presents the LuxTIME project, an interdisciplinary initiative in Luxembourg that investigates historical environmental exposures (“exposome”) through the lens of digital history, environmental sciences, and data visualization. The project uses data visualization not only for communication but as a central methodological tool for navigating complex, heterogeneous data and facilitating collaboration across disciplines.
- LuxTIME explores the exposome—a concept encompassing all non-genetic environmental influences on human health—within the industrial history of the Minett region. By combining historical records, environmental data, and social information, the project aims to study the long-term health effects of industrialization. The work involves researchers from digital history, cheminformatics, eco-hydrology, and data visualization.
- Rather than using data visualization solely for displaying results, LuxTIME adopts it as an exploratory and interpretative tool throughout the research process. Visualizations help define project scope, track progress, analyze metadata, explore interdisciplinary friction, and reflect on participant experiences.
- The team developed a data visualization toolbox that integrates:
	-	Standard and adapted statistical charts (e.g., line graphs, bar charts, treemaps)
	-	Concept maps for mapping interdisciplinary knowledge
	-	Visual rhetoric and metaphor (e.g., using a tree to depict project growth)
	-	Data humanism approaches that embrace visual complexity and imperfection
	-	Multivariate data glyphs for summarizing dataset attributes
	-	Non-representational visualizations for reflecting on participant experiences and evolving project scope
	-	Data storytelling, including timeline-based narratives of publication and collaboration
- The team explored how visualization could:
	1.	Map disciplinary knowledge and support scope definition
	2.	Track the project’s thematic evolution and interdisciplinary blending
	3.	Explore data and metadata with attention to disciplinary priorities
	4.	Monitor project deliverables and participant experiences, including publication timelines and collaboration patterns
- LuxTIME applied its toolbox in various phases: conceptual mapping, metadata exploration, project monitoring, and storytelling. Visualizations revealed how project priorities shifted over time, how disciplines merged around key themes, and how different participants experienced the project temporally and emotionally.
- The authors note that visualizations served not just to represent data but also to generate new insights, mediate disciplinary dialogue, and support epistemic reflection. They emphasize the importance of embracing diverse visualization paradigms, especially in interdisciplinary contexts where conventional data practices may fall short.
- LuxTIME demonstrates that an expanded, reflective use of data visualization can serve as a methodological and epistemological bridge in interdisciplinary research. The authors advocate for a flexible “toolbox” approach that accommodates diverse visual languages and fosters co-creation across disciplines. This model could inspire similar projects seeking to integrate complex historical and scientific data in collaborative frameworks.

Comments: 
- Could be useful to discuss how project management for large projects, whether interdisciplinary or not, could revolve around data visualizations and summaries. I fail to grasp how it applies to Research Centers that fund individual projects that may or may not be related, however. 
- Cool, but doubtful about its usefulness in the context of Sentinelle Nord or ArcticNet. 

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Aydinoglu, Arsev Umur, Todd Suomela, and Jim Malone. “Data Management in Astrobiology: Challenges and Opportunities for an Interdisciplinary Community.” Astrobiology 14, no. 6 (June 2014): 451–61. https://doi.org/10.1089/ast.2013.1127.

Summary from ChatGPT:
- The article examines the data-sharing practices, challenges, and opportunities within the astrobiology research community, especially in the context of the NASA Astrobiology Institute (NAI). It is based on a survey conducted in 2013 that garnered 194 responses (114 from NAI-affiliated scientists and 80 from a broader astrobiology Listserv).
1. Interdisciplinary Complexity: Astrobiology spans over 110 disciplines, making data sharing especially complex due to differing terminologies, methods, and data formats. This diversity complicates the establishment of shared repositories and standards, but also offers a unique opportunity to design robust interdisciplinary data infrastructures.
2. Barriers to Data Sharing: Despite widespread acknowledgment of the benefits of data sharing (e.g., improving reproducibility, reducing redundancy), several persistent barriers exist:
	-	Lack of time, funding, and incentives
	-	Limited institutional infrastructure and support
	-	Fear of misuse or lack of proper acknowledgment
	-	Competition and protection of intellectual property
  - Only 30% of respondents felt their data was easily accessible by others, and a minority used public or institutional repositories.
3. Benefits and Conditions for Sharing: Researchers recognized benefits such as data integrity, verification of results, and broader collaboration. Most were willing to share data under specific conditions:
	-	Proper citation and acknowledgment
	-	Embargo periods before public release
	-	Co-authorship or collaboration opportunities
  - These findings suggest cultural and reward system changes could increase sharing.
4. Practices and Tools: Researchers primarily stored data on personal or institutional computers. Portable hard drives were widely used, but institutional repositories and cloud storage were rare. A wide variety of data formats and metadata standards were reported, with many respondents uncertain whether they captured metadata at all.
5. Organizational and Policy Landscape: Agencies like NASA, NSF, and NIH require data management plans, aligning with broader U.S. federal policy promoting open science. However, only 28% of respondents reported their funder required a data management plan at the time of the survey.
6. Survey Implications: The study found a gap between willingness and actual practice in data sharing. While 71% shared data with others, only a small proportion shared data publicly or adhered to best practices. Researchers expressed a need for better tools, support, and training.
7. Conclusions and Recommendations:
	-	Policy and Infrastructure: There is a clear need for formal infrastructure and funding to support long-term, accessible, and interoperable data sharing systems.
	-	Training and Support: Education in data management best practices is crucial, especially given the youth of the astrobiology field—many respondents were early-career researchers.
	-	Incentives and Culture: Shifting the reward systems (e.g., citations, acknowledgments) and reducing fears of misuse could encourage openness.
	-	Collaborations: Stronger ties with information scientists and librarians may facilitate solutions like standardized metadata practices and user-friendly repositories.
  - The authors emphasize that the interdisciplinary and relatively young nature of the astrobiology community makes it an ideal testbed for progressive data-sharing initiatives, with the potential to serve as a model for other fields.


Comments: 
- The findings of this paper seem to broadly support the findings of Anger et al. 2022 (or the other way around), but from the perspective of the scientists. 
- Could be interesting to tie in together for the webinar. 
- Data management in general, does not really fit well with Sentinelle Nord's focus for the paper, although the content matter remains interesting.


<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Basalti, Chiara, Giulia Caldoni, Sara Coppini, Bianca Gualandi, and Mario Marino. “Mapping Research Data at the University of Bologna,” n.d.

Summary from ChatGPT: 
- This study analyzes how research data are managed at the University of Bologna (UniBO) by examining 29 Data Management Plans (DMPs) from Horizon 2020 and Horizon Europe projects where UniBO acted as coordinator or responsible partner. The work, led by institutional data stewards, aims to characterize the diversity of research data, assess cross-cutting data management challenges, and explore the presence of interdisciplinary data production.
1. Data Diversity and Practices
	-	Text and tabular data are the most common types across disciplines. Collaborative projects tend to manage a wider range of data types.
	-	Most datasets are initially planned as single-type (e.g., only tabular), although multi-type datasets (bundling e.g., text, image, software) are present.
	-	While most projects generate new data, data reuse is limited, suggesting underdeveloped practices in discovery or documentation of existing resources.
2. Cross-Cutting RDM Issues
	-	Half the projects involve personal data, requiring strategies like anonymization or controlled access. However, many DMPs lack detailed privacy management or rely on vague future decisions.
	-	Barriers to openness include privacy, ethics, intellectual property rights (IPR), and data size. These affect repository selection and access decisions.
	-	While most data are within manageable sizes (gigabytes), long-term preservation concerns persist.
	-	General-purpose repositories (e.g., Zenodo, AMS Acta) are preferred over discipline-specific ones, indicating potential gaps in domain infrastructure or awareness.
	-	Only 24% of projects used recognized data standards; most others do not mention any, underscoring a major interoperability challenge.
	-	DMP publication is generally supported, but some remain closed due to sensitive content or undecided policies.
3. Interdisciplinarity Signals
	-	Around 18% of datasets are produced in contexts where the data creator and principal investigator belong to different disciplinary sectors.
	-	Stronger signals of interdisciplinarity are found in collaborative projects compared to single-investigator ones.
	-	Nonetheless, disciplinary taxonomies (e.g., Italy’s SSD system) may underrepresent emerging or hybrid fields, complicating measurement of true interdisciplinarity.

Relevance to Sentinelle Nord and the Perspective Paper Objective

- This article is directly relevant to the Sentinelle Nord perspective paper’s objective in the following ways:
	-	DMPs as Coordination Tools: The study illustrates how DMPs serve not only compliance purposes but also foster structured communication between partners, especially in multi-institution projects. This supports their potential use as coordination mechanisms in IDR programs like Sentinelle Nord.
	-	Metadata and Standardization Gaps: The low adoption of metadata standards despite institutional support highlights a key challenge for improving data visibility and interoperability—a central concern for programs seeking cross-domain integration.
	-	Infrastructure and Stewardship: UniBO’s centralized model, with data stewards guiding RDM practices, presents a valuable institutional approach to enhancing collaboration and research impact in IDR contexts.
	-	Early-stage DMP Limitations: The use of mostly month-6 DMPs reveals the gap between planned and enacted RDM practices. This underscores the importance of sustained follow-up and iterative DMP development—an insight relevant for Sentinelle Nord’s own data governance evolution.
	-	Interdisciplinarity Metrics and Constraints: The study provides a concrete, replicable method to identify interdisciplinary data production using institutional classification systems, but also cautions against relying solely on formal taxonomies.

Comments:
- This paper provides empirical support for the claim that upstream data management practices—especially DMPs and stewardship support—can shape collaborative behavior and infrastructure needs in interdisciplinary research. Its insights are well-aligned with the goals of the Sentinelle Nord perspective paper.


<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Pacharra, Marlene, Tobias Otto, and Nina Olivia Caroline Winter. “From Bench to Brain: A Metadata-Driven Approach to Research Data Management in a Collaborative Neuroscientific Research Center.” Data Science Journal 24 (January 8, 2025). https://doi.org/10.5334/dsj-2025-002.


Summary from ChatGPT: 
- This paper details the research data management (RDM) strategy implemented by the Collaborative Research Center (CRC) 1280 “Extinction Learning,” a multidisciplinary initiative involving 81 researchers from biology, psychology, medicine, and computational neuroscience across four institutions. The authors present a metadata-driven approach designed to enhance collaboration, data visibility, and research impact within an interdisciplinary research environment.
1. Metadata Schema Development
	-	Iterative Design: The team collaboratively developed a metadata schema comprising 16 fields tailored to the diverse needs of participating disciplines.
	-	Standards Integration: To promote interoperability, the schema includes mappings to established standards such as Dublin Core and DataCite.
	-	Controlled Vocabularies: Discipline-specific terminologies were incorporated to ensure consistency and clarity across datasets.
2. Tool Implementation
	-	Open-Source Applications: Custom tools were created to store metadata as local JSON files alongside research data, facilitating seamless integration into researchers’ workflows.
	-	Search Functionality: These applications enable efficient metadata search and retrieval, enhancing data discoverability within the CRC.
3. Data Sharing Practices
	-	Internal Collaboration: The RDM framework supports the sharing of neuroscientific data from over 3,200 human and animal subjects among CRC members.
	-	Sustainability Focus: Emphasis is placed on creating a sustainable RDM infrastructure that can adapt to evolving research needs.

Relevance to Sentinelle Nord’s Perspective Paper

- The methodologies and insights presented in this paper are directly applicable to Sentinelle Nord’s objective of examining how upstream data management practices can enhance interdisciplinary collaboration and research impact:
	-	Custom Metadata Frameworks: The development of a tailored metadata schema demonstrates how interdisciplinary teams can co-create standards that accommodate diverse data types and disciplinary requirements, aligning with Sentinelle Nord’s emphasis on enhancing data visibility.
	-	Integration of Established Standards: Mapping to Dublin Core and DataCite illustrates a practical approach to achieving interoperability, a key consideration for Sentinelle Nord’s data coordination efforts.
	-	Open-Source Tool Development: The creation of user-friendly applications for metadata management underscores the importance of accessible tools in facilitating effective RDM, resonating with Sentinelle Nord’s focus on improving collaboration through practical solutions.
	-	Sustainable RDM Practices: The paper’s emphasis on sustainability and adaptability in RDM infrastructure aligns with Sentinelle Nord’s goal of fostering long-term research impact through robust data management strategies.

Comments: 
- Seems like a targeted example of research network Research Data Management approaches that can be directly linked to what SN did during their tenure. Could likely be used as an example in the paper and lessons learned from that paper are likely directly applicable. 
- The idea of a metadata schema with mandatory and optional fields seems interesting as well, perhaps more in the context of ArcticNet's webinar and future DMPs. 



<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Baker, K.S., S.J. Jackson, and J.R. Wanetick. “Strategies Supporting Heterogeneous Data and Interdisciplinary Collaboration: Towards an Ocean Informatics Environment.” In Proceedings of the 38th Annual Hawaii International Conference on System Sciences, 219b–219b. Big Island, HI, USA: IEEE, 2005. https://doi.org/10.1109/HICSS.2005.565.

Summary ChatGPT:

- This paper introduces the concept of an Ocean Informatics Environment (OIE) to address the challenges of managing heterogeneous data and enabling interdisciplinary collaboration in ocean science. Drawing from social science, participatory design, and computer-supported cooperative work (CSCW), the authors propose strategies to build information systems that are adaptive, socially grounded, and technically integrated.
- Key insights:
	-	Oceanography involves complex, heterogeneous datasets produced by diverse disciplines with different epistemic cultures.
	-	Successful collaboration demands mindfulness of disciplinary differences and support for boundary objects—shared tools, grids, languages, or metaphors that bridge gaps.
	-	The authors advocate for “collaborative care”, an ethic acknowledging the social and emotional labor of maintaining trust and respect across disciplines.
	-	They propose a vision of “thick infrastructure”: sociotechnical systems that evolve with the practices and relationships they support.
	-	Their approach emphasizes designing for diversity, encouraging reflexivity, iterative development, and inclusive participation.

Relevance to Sentinelle Nord Perspective Paper

This paper is highly relevant to Sentinelle Nord’s goal of exploring how upstream data practices enhance interdisciplinary research:

Sentinelle Nord Focus	Baker et al. Contribution
Upstream data management	Describes how collaborative planning, data heterogeneity, and local practices shape design of RDM systems.
Metadata & coordination tools	Introduces adaptive metadata strategies, local glossaries, and semantic integration to enable data reuse across disciplines.
Interdisciplinary collaboration	Offers detailed analysis of sociotechnical strategies to bridge epistemic and organizational divides.
Research visibility & impact	Encourages infrastructure that supports both scientific productivity and learning, including open-source tools and public repositories.
Case-based insight	Provides a real-world model (OIE) that parallels SN’s ecosystem-scale, distributed, interdisciplinary context.

Bottom Line:
Baker et al. (2005) delivers a foundational, conceptually rich example of how data infrastructures can be intentionally designed to foster collaboration, mutual understanding, and knowledge integration—precisely the kinds of capacities that Sentinelle Nord aims to cultivate.

Comments:
- Unsure whether this paper really has relevance in the context of SN. We are not talking about creating a unified knowledge system for SN, but rather how a research network can structure data management to foster collaborations and interdisaciplinary work. 
- This paper is also much older, so might be outdated for the purpose of our work. 

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Zimmerman, Ann. “Not by Metadata Alone: The Use of Diverse Forms of Knowledge to Locate Data for Reuse.” International Journal on Digital Libraries 7, no. 1–2 (October 2007): 5–16. https://doi.org/10.1007/s00799-007-0015-8.

Comments: 
- Has to do with data reuse
- Older paper
- Not relevant for the purpose of our work with SN and AN

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Spichtinger, Daniel, and Susanne Blumesberger. “FAIR Data and Data Management Requirements in a Comparative Perspective: Horizon 2020 and FWF Policies.” Mitteilungen Der Vereinigung Österreichischer Bibliothekarinnen Und Bibliothekare 73, no. 2 (June 5, 2020): 207–16. https://doi.org/10.31263/voebm.v73i2.3504.

Summary ChatGPT:

- This article compares the data management policies of the European Union’s Horizon 2020 framework and Austria’s FWF national funding agency. Both require submission of Data Management Plans (DMPs), encourage FAIR data principles, and promote open data, though with nuanced implementation differences.
- Key Points:
	-	Horizon 2020 mandates DMPs for all funded projects (unless opting out for IPR, ethics, etc.), requires updates during the project, and emphasizes FAIR and open access to data needed to validate publications.
	-	FWF mandates DMPs for all approved projects since 2019, structured around Science Europe’s DMP core requirements (data characteristics, metadata, access, legal/ethical issues). The DMP must be updated and included in the final report.
	-	Both policies allow for controlled access when justified, require use of persistent identifiers, and encourage deposit in certified repositories (e.g., Zenodo, re3data).
	-	FAIR data principles are integrated structurally in Horizon 2020 and as a subset in FWF templates.
	-	The article highlights the need for alignment between funders to reduce researcher burden and promote interoperable data governance.


Relevance to Sentinelle Nord Perspective Paper

This article provides a concrete comparative framework that is directly relevant to Sentinelle Nord’s aim of improving upstream data practices in interdisciplinary research programs:

Sentinelle Nord Objective	Article Contribution
Enhance collaboration	Emphasizes harmonization of funder policies to reduce friction for transnational/interdisciplinary research.
Improve data visibility	Encourages repository use, metadata standards, and licensing for discoverability and reuse.
Increase research impact	Advocates for FAIR compliance and open access to maximize reuse and validation of findings.
Examine upstream practices	Provides clear, actionable descriptions of DMP structure and evolution as living documents.
Use SN as a case	Enables SN to benchmark its policies and practices against EU and national models.

The article offers language, structure, and policy-level insights that could inform recommendations in the SN paper for building a harmonized, flexible data management framework across disciplines and institutions.

Relevance for ArcticNet Webinar on Data Management in Multidisciplinary Networks

Highly relevant. This article:
	-	Provides practical examples of what funders require and why.
	-	Can structure a webinar module comparing Canadian funder expectations (e.g., NSERC) with European ones.
	-	Offers material for a discussion activity or case study: “Design a DMP for a multidisciplinary project under multiple funders.”
	-	Can inform a policy session on aligning ArcticNet practices with international norms to foster data sharing and collaboration across Arctic science communities.


Bottom Line: This article is a strong resource for both the SN perspective paper and a foundational webinar for ArcticNet researchers seeking to align their data practices with international standards.

Comments: 
- Seems highly relevant to ArcticNet webinar
- I do not think that it is really relevant to Sentinelle Nord


<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Kaufmann, David, Johanna Kuenzler, and Fritz Sager. “How (Not) to Design and Implement a Large-Scale, Interdisciplinary Research Infrastructure.” Science and Public Policy 47, no. 6 (April 25, 2021): 818–28. https://doi.org/10.1093/scipol/scaa042.

Summary from ChatGPT:

- This reflective article analyzes the design and implementation of a large-scale, interdisciplinary research infrastructure in Austria: the Earth System Sciences (ESS) program. Drawing on participant observation and interviews, the authors critically assess its governance, coordination, and data management strategies.
- Key Findings:
	-	The program aimed to integrate diverse disciplines (natural sciences, social sciences, humanities) and institutions, but struggled with coordination, accountability, and interdisciplinary synthesis.
	-	Lack of shared vision, unclear roles, and uneven distribution of responsibilities undermined cohesion.
	-	There was no centralized data management plan, and data sharing remained siloed, with varying standards and practices.
	-	Governance was top-down, which hindered adaptability and co-ownership by researchers.
	-	The authors propose design principles for future interdisciplinary programs:
	-	Establish clear governance and facilitation structures.
	-	Create shared frameworks for data interoperability and planning.
	-	Support mutual learning through structured interactions and reflexivity.
	-	Ensure resource allocation for coordination and integration work.

Relevance to Sentinelle Nord Perspective Paper

Sentinelle Nord Objective	Article Contribution
Upstream coordination tools	Illustrates the risks of omitting coordinated planning (e.g., DMPs, common vocabularies).
Data visibility & research impact	Highlights how fragmented data practices reduce reuse, collaboration, and synthesis.
Enhancing collaboration in IDR	Offers governance and facilitation insights to support inclusive, adaptive interdisciplinary work.
Illustrative case value	Acts as a cautionary tale and provides actionable “lessons learned” that SN can proactively address.

This article is particularly valuable for its critical lens—unlike idealized case studies, it showcases pitfalls that SN can avoid by strengthening upstream data planning and coordination.


Relevance for ArcticNet Webinar on Data Management
	-	Serves as a teaching example of what can go wrong in multidisciplinary networks without proper planning.
	-	Supports a webinar module on infrastructure design pitfalls, emphasizing:
	-	The importance of shared language and data interoperability.
	-	The need for funded coordination roles (e.g., data stewards, liaisons).
	-	The risks of over-centralization without grassroots engagement.
	-	Can prompt discussion on how ArcticNet can improve governance, integration mechanisms, and DMP practices across projects and institutions.


Bottom Line:
This article is essential reading for any interdisciplinary program like Sentinelle Nord or ArcticNet. It offers a rare, honest reflection on structural design failures in large-scale research initiatives—and suggests how upstream planning, data coordination, and inclusive governance can make or break collaborative science.

Comments: 
- This paper states a few arguments that could be used to justify the absence of a common data repository for research programs. 

<!-- -------------------------------------------------------------------------------------------------------------------------- -->
===> Mittal, Deepti, Rebecca Mease, Thomas Kuner, Herta Flor, Rohini Kuner, and Jamila Andoh. “Data Management Strategy for a Collaborative Research Center.” GigaScience 12 (December 28, 2022): giad049. https://doi.org/10.1093/gigascience/giad049.

Summary ChatGPT:

- This article presents the development and implementation of a data management strategy for CRC 1333, a large, interdisciplinary German research center focused on understanding molecular heterogeneity. The strategy was developed collaboratively and tailored to the project’s evolving needs.
- Key Components:
	-	The strategy is built on the FAIR principles and designed to accommodate multiple disciplines, each with its own data types, formats, and workflows.
	-	A central metadata framework was created to support semantic annotation across disciplines using ontologies and controlled vocabularies.
	-	The team employed a bottom-up, participatory approach by engaging researchers in the design of DMP templates and metadata schemas.
	-	The implementation was supported by custom-built and open-source tools (e.g., GitLab, Dataverse), integrated into the research workflows.
	-	A dedicated data steward coordinated training, user support, and technical integration, reinforcing data quality and documentation.



Relevance to Sentinelle Nord Perspective Paper

This article aligns closely with Sentinelle Nord’s aim to improve upstream data practices in interdisciplinary research:

Sentinelle Nord Objective	Article Contribution
Use of DMPs	Shows how DMPs were co-designed and iteratively developed across teams, encouraging engagement and alignment.
Metadata standards	Demonstrates ontology-based metadata design to harmonize data from different disciplines.
Coordination tools	Emphasizes the use of shared platforms and tools (e.g., GitLab, Dataverse) to support reproducible and transparent collaboration.
Interdisciplinary collaboration	Provides a real-world example of participatory infrastructure-building that supports diverse workflows and epistemologies.
Data visibility and impact	Encourages standardized, semantically rich documentation that increases reusability and discoverability.

This article serves as an ideal positive model for how to proactively manage complexity in interdisciplinary data ecosystems.


Relevance for ArcticNet Webinar on Data Management
	-	Offers a model case for presenting best practices in data stewardship and metadata harmonization.
	-	Can support a module on building participatory, sustainable data infrastructures in ArcticNet-style networks.
	-	Highlights how tools, training, and coordination roles can operationalize FAIR in distributed, multidisciplinary teams.
	-	Encourages reflection and dialogue among webinar participants about how to scale similar strategies to ArcticNet’s context (e.g., ecological, social, health data).


Bottom Line:
This article is a blueprint for designing FAIR-aligned, researcher-driven data strategies in large, interdisciplinary research settings. It directly supports the goals of both the Sentinelle Nord perspective paper and a data management webinar for ArcticNet.

Comments: 
- This paper also presents challenges and solutions to RDM in the context of large interdisciplinary research networks. 
- This paper would be highly relevant for AN webinar.