Thank you for stopping by!

**(PDF) Codebook_TEK Study_REDCAP.pdf**  
Codebook exported directly from REDCap, containing variable definitions, terms, record_id
structures, and coding descriptions.

**(CSV) 2025NEPATEKStudy_DATA.csv**  
Raw data exported from REDCap. Includes all variables and metadata available to authorized
project users. Provided for transparency and reproducibility.

**(Rmd) KRC_Final_TEK_Analysis.Rmd**  
R Markdown file used to run all data cleaning, analysis, and figure generation.

**(Rmd) RenderedPDF_Final_TEK_Analysis.Rmd**  (extra)

To reproduce results, download the following supporting datasets into your environment:  
- `AGENCY_NEPAccess_Final.csv`
- `tek_feis_total_counts.csv`  
- `tek_term_code.csv`  
- `Proc_code.csv`  
- `subject_tek_use_code.csv`

Research Study

This study examines how TEK is engaged within Final Environmental Impact Statements (FEISs), NEPA’s most detailed review documents, across time, regions, agencies, and the sovereign nations to whom TEK belongs. 
Specifically, this study investigates: 
(a) How frequently TEK is referenced in FEISs, 
(b) How TEK is used in FEISs, 
(c) Which subject areas are most often associated with TEK, 
(d) How has the frequency of references to TEK changed between 2000 and 2022?

About the Research:
What is Traditional Ecological Knowledge?
Traditional Ecological Knowledge (TEK) is the cumulative body of knowledge, practices, and beliefs developed by Indigenous communities through generations of close interaction with the environment [@berkes1993traditional]. 
It encompasses ecological relationships, resource use, and spiritual connections to place, transmitted through oral tradition and cultural practice [@montag2014climate],[@huntington2000using]. 
Holistic and relational, TEK emphasizes reciprocity and balance among all life forms [@mcgregor2004coming; @kimmerer2024serviceberry].

TEK entered academic discourse in the early 1990s [@berkes1993traditional], at a time when U.S. land and wildlife management philosophies were shaped by thinkers such as Leopold, Muir, and Roosevelt. 
Their books and documentation of environment largely excluded Indigenous ecological practices and existing communities in the area [@werdel2024state]. 
Indigenous communities were often engaged only for data extraction rather than as partners [@nadasdy1999politics]

NEPA and TEK

The National Environmental Policy Act (NEPA) provides one arena where TEK could inform governance. 
Section 101 of NEPA specifically calls upon federal agencies to use “all practicable means and measures… to create and maintain conditions under which man and nature can exist in productive harmony” 
for the benefit of future generations of Americans (National Environmental Policy Act of 1969, 42 U.S.C. § 4331). 
Traditional Ecological Knowledge (TEK), representing generations of Indigenous understanding and stewardship of natural systems, 
is one critical form of knowledge that has been overlooked but may help achieve this vision of harmony between man and nature [@souther2023integrating; @usher2000traditional].

Methods

To examine how frequently Traditional Ecological Knowledge (TEK) is referenced in Final Environmental Impact Statements (FEISs) by federal agencies, we used NEPAccess (nepaccess.org), a knowledge and discovery platform for NEPA documents, 
to search FEISs completed between 2000–2022. As of May 2024, NEPAccess houses over 18,000 documents, including Environmental Assessments, Draft and Final EISs, and Records of Decision, and is recognized as the most comprehensive NEPA document database that currently exists (Council on Environmental Quality, 2024). 
NEPAccess provides a structured repository of documents categorized by project title, lead agency, location, date, and other characteristics [@bethard2019inferring]. Its automated classification system allows for scalable, 
cross-agency comparisons of TEK references across the dataset, and prior evaluation of NEPAccess has shown no statistical bias in agency representation [@stava2025quantifying].

Full-text search for TEK

We applied Natural Language Processing (NLP) techniques to conduct a large-scale text search across 3,945 FEISs. 
Recent advancements in ecological text mining have made it possible to extract and analyze terms in this manner, allowing for content-level insights across thousands of documents [@farrell2024changing]. 
NLP enabled the efficient analysis of extensive text found in grey documents, FEIS documents can include hundreds to thousands of pages and allowed for the identification of TEK terms and contextualize TEK references on a large scale. 
We used text-mining methods to extract TEK-related terms along with 300 words of surrounding context (150 words before and after each match), allowing a contextual analysis of each individual mention of how TEK is discussed. 
Mentions of TEK were analyzed at the excerpt level rather than across the entire FEIS documents; therefore, this study assesses how TEK is referenced, not how it is fully integrated into the overall environmental review. 
Due to the study design, the presence of TEK or Local Knowledge does not necessarily imply meaningful incorporation or endorsement by the agency. 
Coders evaluated the content and context of each excerpted mention but were limited to the information presented within the extracted text segments.

Rubric Overview

To evaluate how Traditional Ecological Knowledge (TEK) is mentioned within these environmental review documents, we developed two rubrics to guide systematic coding and analysis. Rubric 1: “Coding Rubric for Types of TEK Integration in FEISs” 
includes ten context-based categories capturing how TEK was referenced in documents, including: boilerplate, glossary/index, citation, table of contents, baseline data collection, impact assessment, ecological modeling, consultation, monitoring and adaptive management, and mitigation strategies. 
Rubric 2: “Coding Rubric of TEK Subject Categories in FEISs”, includes 34 subject-specific categories derived from the textual language in the FEIS and include references into ecological, wildlife, cultural, and social themes associated with TEK. 
For analytical clarity, both rubrics were further stratified into groupings to support pattern recognition and interpretation. (See table in Supplemental S1: Rubric 2 “Coding Rubric of TEK Subject Categories in FEISs” for formal definitions.)
