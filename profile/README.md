## Biomedical Data Architecture & Repository
 
 [Research](#Research) | [Members](#Members) | [Selected Publications](#selected-publications)
 
### Research
BioMed DAR is a SSSO (Standard Systems Support Office) that provides clinical research data management support and governance framework to strategic A*STAR BMRC programmes; Briefly, DAR manages the data life cycle of the cohort datasets through 3 operatives - data governance, data management operations (cleaning, integration, cataloguing, movement, usage) and s/w development. DAR builds and uses its own in-house data warehouse, data catalogue, data visualizers and secured data exchange API libraries. In-house s/w builds allow us to adapt and integrate data management or governance workflow into our systems easily. Currently, DAR helps to host IAF programs like ATTRaCT, CaLiBre, WCIT and GUSTO. 

On data security (See Figure 1), it is important to note that DAR does not store identifiable datasets and works with clinical data stakeholders to import only de-identified data into BII. Meanwhile, DAR operates within the BII ISO27001 certified environment for hosting its data warehousing, ETL processes and data sandboxes where strict SOP are in place to track data movement. Physically, the ISO27001 servers are located in designated server rooms where staff movement are logged and captured through CCTV. As an additional measure, the ISO27001 servers are caged up to pose further deterrence to the physical access of the disk drives.

| ![Figure 1. DAR - Data Architecture.](/images/Figure1-DAR-Data-Architecture.png)  | 
| :--------------: |
| *Figure 1. DAR - Data Architecture.*  |

On data governance (see Figure 2), data access of each cohort dataset needs to be approved by the respective cohort’s DAC (data access committee). This requires the project proposal to clearly define the purpose, scope and duration of the data usage and then subjected to a DAC review. Only upon DAC approval, the scoped dataset will then be ETLed (extract/transform/load) from DAR’s data warehouse to a designated VPN sandbox environment for its intended usage. Generally, no export of data will be allowed while the analysis results will need further approval by a data concierge team.


| ![Figure 2. Data governance.](/images/Figure2-Data-governance.png)  | 
| :--------------: |
| *Figure 2. Data governance.*  |




### Members

<details>

<summary>List of Members</summary>

| Designation  | Name |
| :-------------- | :-------------- |
| **Senior Principal Investigator**  | WONG Wing Cheong   |
| **Assistant Principal Investigator**  | TAN Ming Zhen  |
| **Project Manager**  | FUN Max  |
| **Assistant Systems Manager**  | LIM Aloysius  |
| **Software Engineer**  | KOH Zi Ying  |

</details>
<details>

<summary>Principal Investigator's Biography</summary>
Wing-Cheong received his undergraduate degree in Computer Engineering from NTU. He joined A*STAR under the joint MSc in Bioinformatics from A*STAR/NUS and subsequently completed his Dr. Rer. Nat (suma cum laude) in Computer Science from Leipzig University. He has been a Principal Investigator with BII since 2014 and is currently the Head/Principal Investigator of the BioMed DAR group since 2019.
</details>

### Selected Publications
1. Tay WH, Tantoso E, Eisenhaber F, Wong WC*. (2019) Translational Informatics Management System (TIMS): Towards OMICS based clinical data management for long term curation of clinical studies.  Journal of Open Source Software, 4(40), 1533. https://doi.org/10.21105/joss.01533
1. Yap CK, Eisenhaber B, Eisenhaber F, Wong WC*. (2016) xHMMER3x2: Utilizing HMMER3's speed and HMMER2's sensitivity and specificity in the glocal alignment mode for improved large-scale protein domain annotation.  Biol Direct.;11(1):63. PubMed PMID: 27894340; PubMed Central PMCID: PMC5126834.
1. Wong WC*, Yap CK, Eisenhaber B, Eisenhaber F. (2015) dissectHMMER: a HMMER based score dissection framework that statistically evaluates fold critical sequence segments for domain fold similarity; a pragmatic step towards homology inference.  Biology Direct, 10:39, doi: 10.1186/s13062-015-0068-3
1. Wong WC*, Maurer-Stroh S, Schneider G, Eisenhaber F. (2012) TMSOC (Transmembrane helix: Simple Or Complex).  Nucleic acid research (Web Server issue), doi: 10.1093/nar/GKS379
1. Wong WC, Cho SY, Quek C. (2009) R-POPTVR: A novel reinforcement-based POPTVR fuzzy neural network for pattern classification.  IEEE transactions on neural networks, 20(11), pp1740-55, doi:10.1109/TNN.2009.2029857
1. Wong WC, Loh M, Eisenhaber F. (2008) On the necessity of different statistical treatment for Illumina BeadChip and Affymetrix GeneChip data and its significance for biological interpretation.  Biology Direct, 3:23, doi:10.1186/1745-6150-3-23.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
