#### Library Main Navigation: &nbsp; &nbsp;  <b>  [Ecosystem Library Home](https://github.com/NIH-NICHD-Ecosystem) </b> &nbsp; | &nbsp;[User Stories](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/README.md) &nbsp; | &nbsp; [Efforts](https://github.com/NIH-NICHD-Ecosystem/Efforts/blob/main/README.md) &nbsp; | &nbsp; [Library Help](https://github.com/NIH-NICHD-Ecosystem/LibraryHelp/blob/main/README.md)


</br>

# E8 Common Issues in NIH Data Management & Sharing (DMS) Plans

###  The _Eunice Kennedy Shriver_ National Institute of Child Health and Human Development (NICHD) Office of Data Science and Sharing (ODSS) identified nine issues common to many DMS Plans submitted to NICHD. Researchers should avoid these issues moving forward and revise existing DMS Plans to better align with the DMS Policy, as appropriate. 

<br/>

# Table of Contents
- [Effort Overview](#effort-overview)
- [Common Issues in NIH Data Management & Sharing (DMS) Plans (and how to address them)](#common-issues)
- [User Stories](#user-stories)

<br/><br/>

# Effort Overview 

The _Eunice Kennedy Shriver_ National Institute of Child Health and Human Development (NICHD) is committed to promoting data sharing to accelerate research and training to understand human development, improve reproductive health, enhance the lives of children and adolescents, and optimize abilities for all and to amplify the impact of the institute’s investments. Since the 2023 NIH Policy for Data Management and Sharing (DMS) took effect, the NICHD Office of Data Science and Sharing (ODSS), in collaboration with NICHD extramural and intramural staff, has been analyzing DMS Plans submitted to NICHD in comparison to the requirements and expectations described in public NIH DMS Policy materials. In this effort, NICHD ODSS identifies nine common issues across submitted DMS Plans and provides context for how to fix each issue. NICHD ODSS has also presented these findings to researchers and staff in multiple venues, including a presentation at the [Federal Demonstration Partnership (FDP) May 2024 Meeting](https://thefdp.org/wp-content/uploads/FDP-DMS-5-23-2024.pptx.pdf).
<br/>

#### Primary contact:</b> [NICHDecosystem@nih.gov](mailto:NICHDecosystem@nih.gov?subject=Ecosystem_Library) 

#### Details: 
* <b> Created by:</b> NICHD ODSS </br>
* <b> NIH contacts:</b>
    * Rebecca Rosen, Director, NICHD ODSS
    * Valerie Cotton, Deputy Director, NICHD ODSS
    * Elizabeth Clerkin, Data Science and Sharing Specialist, NICHD ODSS
    * Stephanie Tison, Data Science and Sharing Specialist, NICHD ODSS

<br/><br/>

## <a id="common-issues"></a>Common Issues in NIH Data Management & Sharing (DMS) Plans (and how to address them)
These issues apply to both intramural and extramural researchers unless otherwise noted and are relevant to all DMS Plan formats including the latest version described in [NOT-OD-26-046](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-26-046.html).
<br/>
<br/>

#### 1. Missing details for data that will be generated and shared

When describing what data will be generated and shared, include details such as species (or other source), format, and amount.
Below are examples of how to complete the table in #6 of the updated DMS Plan Format page: 

| Expected Data Type  | Established Repository or Example | 
| :--------------------| :-------------------- |
|human genomic sequence and variant data from 200 children (FASTQs, VCFs)|dbGaP and SRA (controlled access)|
|clinical data from 1000 patients (CSV) |NICHD DASH (controlled access)|

| Expected Data Type  | Established Repository or Example | 
| :--------------------| :-------------------- |
|functional magnetic resonance images (DICOM) of 60 rat brains|DANDI (open access)|

| Expected Data Type  | Established Repository or Example | 
| :--------------------| :-------------------- |
|qualitative surveys about 45 hospitals (CSV)|The Qualitative Data Repository (open access)|

NICHD ODSS continues to receive plans that are ambiguous about whether the data will come from a human or a fish, but these details matter because they impact whether other aspects of the DMS Plan are appropriate. For example: Should the data be shared as controlled access in the repository (only needed for human data)? Is the data repository suitable? Will other researchers be able to use these data files? Is a [Genomic Data Sharing Institutional Certification](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/gds/institutional-certifications) required before award? 
<br/>
<br/>

#### 2. Sharing only publication-associated data

Many plans indicate the researcher will share only data associated with publications or that data will be shared as supplementary materials with publications. However, the DMS Policy expects that all scientific data will be shared, by the end of the award period, regardless of publication status.

The DMS Plan should encompass sharing publication-associated data and scientific data not related to publications.

From its inception, sharing non-publication-associated data was built into the policy’s definition of [scientific data](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-013.html#:~:text=Scientific%20Data%3A,as%20laboratory%20specimens), which is tied to principles of data quality, reuse, and reproducibility regardless of publication. The concept was further emphasized by both the White House Office of Science and Technology Policy (OSTP) 2022 memorandum on [Ensuring Free, Immediate, and Equitable Access to Federally Funded Research](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-Access-Memo.pdf) (PDF 372 KB), and the NIH Plan to Enhance Public Access to the Results of NIH-Supported Research ([NOT-OD-23-091](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-23-091.html)).
<br/>
<br/>

#### 3. Not sharing data in established data repositories

The NIH DMS Policy expects that researchers will share scientific data through established data repositories. Sharing data through publications, local servers, or lab websites is not the same as using a repository and does not meet the Policy’s expectations.
Identifying, learning about, and committing to the repositories’ processes and features helps you plan your data generation strategy (e.g., required metadata, standard forms), anticipate your workload (will the repository help you with de-identification?), and plan your budget accordingly (for your team’s time and effort). NICHD created a [Data Repository Finder](https://data-repository-finder.ll.mit.edu/) ↗️ to help researchers select an appropriate repository; [other NIH resources](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/scientific) are also available.

Data repositories offer many benefits including fostering collaboration and building community. They leverage technical and scientific expertise to make data Findable, Accessible, Interoperable, and Reusable (FAIR), through use of common formats and search and visualization interfaces, and by providing continuous and refined processes for data submission, quality control, curation, harmonization, and release of multiple datasets over time. In addition, many repositories are actively working to adhere to all of the [White House OSTP’s Desirable Characteristics of Data Repositories for Federally Funded Research](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf) (PDF 373 KB), which will further improve data FAIRness, security, and the ability to track use of shared data.

You should not use a repository’s services  to mint Digital Object Identifies (DOIs) for data that are not shared through an established data repository; DOIs are meant to link to the location where scientific data are accessible to the research community. 
<br/>
<br/>

#### 4. Not using appropriate domain- or discipline-specific data repositories

NICHD ODSS’s analysis of DMS Plans submitted to NICHD found a clear over-reliance on generalist data repositories, which accept any data type or format. Although [generalist repositories](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/scientific#generalist-repositories), can be a tempting default for sharing data, NIH DMS Policy guidance emphasizes that domain- or discipline-specific data repositories are always preferred.

NICHD researchers should use the NICHD [Data and Specimen Hub (DASH)](https://dash.nichd.nih.gov/) for sharing human clinical and population health data and National Center for Biotechnology Information (NCBI) repositories, such as the database of Genotypes and Phenotypes ([dbGaP](https://www.ncbi.nlm.nih.gov/gap/)), the Sequence Read Archive ([SRA](https://www.ncbi.nlm.nih.gov/sra/)), and the Gene Expression Omnibus ([GEO](https://www.ncbi.nlm.nih.gov/geo/)), for sharing genetic data, unless approved to use an alternative NIH-designated data repository for example by the funding announcement. For other types of data, other discipline, domain, or data-type specific data repositories should be considered first, as they have services and features designed to serve the needs of their specific research communities, which ultimately increase the usability and overall value of shared data. 

Generalist repositories are useful, and [NIH is investing in making them better](https://datascience.nih.gov/data-ecosystem/generalist-repository-ecosystem-initiative), but you should only use them if there is not an appropriate domain-specific data repository available. 

Extra care should be taken when selecting data repositories that support controlled access sharing (note related issue #5). Controlled access data repositories must adhere to additional security and operational standards, such as those described in [Requirements for NIH Controlled-Access Data Repositories and Users](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/requirements) and the forthcoming requirements of the [Draft NIH Controlled-Access Data Policy](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-26-023.html).

Finally, it is unacceptable for researchers to propose to build a new data repository or to share data through a forthcoming data repository, as part of the DMS Plan.  
<br/>
<br/>

#### 5. Sharing data only “by request” or with “Principal Investigator (PI) control”

Proposing to share data “by request” or where the PI controls access to the data is generally not acceptable under the DMS Policy. Not only does a [growing body of literature](https://pubmed.ncbi.nlm.nih.gov/?term=35654271%3B+34315906%3B+34874005) demonstrate that this approach is not effective, but it also inhibits the ability to make the data accessible to the larger research community (i.e., hundreds or thousands of users). So, this approach is not aligned with the [Policy’s definition of data sharing](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-013.html#:~:text=Data%20Sharing%3A%20The%20act%20of%20making%20scientific%20data%20available%20for%20use%20by%20others%20(e.g.%2C%20the%20larger%20research%20community%2C%20institutions%2C%20the%20broader%20public)%2C%20for%20example%2C%20via%20an%20established%20repository.).

NICHD ODSS’s analyses revealed some confusion in the community about the difference between “by request” and the NIH definition of “[controlled access](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-22-213.html#:~:text=controlled%20(i.e.%2C%20measures%20such%20as%20requiring%20data%20requesters%20to%20verify%20their%20identity%20and%20the%20appropriateness%20of%20their%20proposed%20research%20use%20to%20access%20protected%20data)%2C),” which is a protection described in the DMS Policy privacy materials. 

Data should be considered for controlled access sharing through repositories when it:
* has limitations on use imposed by laws, regulations, policies, informed consent, or agreements, 
* is sensitive or involves risk of harm to individuals, groups, or populations (e.g., stigmatizing traits, illegal behaviors), or 
* cannot be sufficiently de-identified to established standards or has a unique risk of re-identification. 

Controlled-access data repositories have established processes for verifying appropriate use of shared data, including steps like confirming requestor identity, establishing centralized and standardized data use agreements, and obtaining approval of secondary use requests by a neutral and independent committee. Because these aspects are already managed by the repository, there is no need for researchers to manage access directly or establish data use agreements on their own—often burdensome and time-consuming activities that can delay data access for years and conflict with NIH requirements. 

By using a controlled-access data repository, you are leveraging established and “well-oiled” processes and agreements that can enable equitable data access in a matter of hours or days.

Some repositories do allow researchers to gatekeep access to their own data. While this may be appropriate for some purposes (e.g., granting another researcher access to data while collaborating on an analysis before data release), it does not meet the NIH definition of data sharing and thus does not alone meet the expectations of the DMS Policy.
<br/>
<br/>

#### 6. Providing vague reasons for not sharing, limited sharing, or delayed sharing

Researchers must provide a [clear and thorough justification](https://grants.nih.gov/faqs#/data-management-and-sharing-policy.htm?anchor=56549) for anything that deviates from NIH DMS Policy expectations. If you are not sharing all of your scientific data through an established data repository by the end of the award period, you need to clearly describe which data are impacted, how sharing is limited, and justify why for NIH staff to review. 
Rather than vaguely stating there are “legal reasons” or “policies,” cite the specific law, policy, agreement, or IRB determination, include an excerpt of a relevant language, and explain why and how that impacts sharing your data. In some cases, you may need to invoke a specific protection because some laws or policies  mean that you can delay data sharing, but you don’t necessarily have to. If you choose to invoke such a reason to delay sharing, you must explicitly state that in your plan and describe which data are impacted. Similarly, rather than claiming “privacy issues” or “ethical concerns,” describe how you engaged Institutional Review Board expertise to determine reasons for limitations, such as why you will redact certain elements from shared data.
NICHD has observed blocks of texts copy-and-pasted into DMS Plans citing the 2003 NIH Data Sharing Policy and other policies that are not relevant to DMS Plans. DMS Plans should only describe rules that impact the sharing of scientific data for the specific funding application. 
<br/>
<br/>

#### 7. Limiting the duration of data sharing to “local retention cycles”

Researchers should plan to share data for as long as possible within the repository’s data retention cycles. Researchers sometimes confuse data repository retention policies with their local record retention cycles and mistakenly state they will only share data for “5 years” or whatever time frame is specified in their records management policy.
Data repository retention cycles are usually much longer and will often host data “in perpetuity.” It is not appropriate for the researcher to take data down any sooner.
<br/>
<br/>

#### 8. Limiting reproducibility for secondary analysis projects

A primary goal of the DMS Policy is to foster validation, replication, and reproducibility of research findings. While researchers are not expected to re-share existing, shared primary data used to conduct secondary research, secondary research applications are expected to maximize appropriate sharing of any new, derived data generated as a result of their research. 

Secondary analysis DMS Plans are often lacking details that are critical for fostering reproducibility including a description of: 

* The primary data used in the project and where (e.g., through a controlled access repository or administrative data source) and how (e.g., after signing a data use agreement) other researchers can access that data.*    
* When, where, and how the documentation and/or code for processing and analyzing that data will be shared (e.g., a generalist repository, GitHub).  
* When, where, and how derived data, including aggregate or summary data, will be shared (e.g., a generalist repository for summary data, the original source repository for individual-level data derivatives [if compatible with data rules and approved by the source repository]).    

*If the primary data are not accessible to the research community, additional steps may be warranted to support the Policy’s reproducibility expectation, where allowable. 

For example, the table in #6 of the updated DMS Plan Format page, may include the following information:

| Expected Data Type  | Established Repository or Example | 
| :----------| :---------- |
|Primary data: VCFs from the PCGC study|Source repository: dbGaP study phs00XXXX.v4.p3|
|Derived data: VCFs harmonized to a new variant calling pipeline |Shared through dbGaP following the governance of the original study (if approved)|
|Variant calling pipeline documentation and code |GitHub|
<br/>
<br/>

#### 9. Missing or unclear DMS budget justifications (in extramural applications)

NICHD wants to make sure that researchers are requesting sufficient funds to support the DMS activities described in their DMS Plans throughout the life of the project, not just at the project’s end. The [DMS Budget Justifications](https://grants.nih.gov/grants/how-to-apply-application-guide/forms-i/general/g.300-r&r-budget-form.htm#L) should summarize all costs relevant to activities described in the DMS Plan. You should include a DMS Budget Justification even when you are not requesting DMS-specific costs, so that you can explain why funds are not needed.

NICHD ODSS expects that the majority of DMS costs will fall into the personnel categories for the time and effort required to prepare data for submission to repositories. Researchers can reduce this effort by designing data collection and analysis approaches that align with a data repository’s submission requirements (formats, metadata, documentation, etc.). 

Many established data repositories do not charge submission fees, or they charge a minimal one-time fee. Not having to worry about long-term storage costs after data are submitted is another reason to use established repositories.
<br/>
<br/>

# User Stories
The following User Stories motivated and informed this Effort:
<br>

| S#  | User Story | Current Problem | User Goal
| :-------------| :------------- | :------------ | :------------ |
|#38| [As NICHD ODSS, we are observing that researchers are over-relying on generalist repositories in the DMS Plans (i.e., defaulting to using generalist repositories instead of domain or data type specific repositories), we want to encourage researchers to use domain and data type specific data repositories as much as possible to take advantage of community-specific curation services and data repository features and align with DMS Policy expectations](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-38.md)  | When researchers are generating multiple data types in their research applications they often default to using one generalist repository, instead of multiple domain or data type specific repositories as expected under the DMS Policy | My goal is to get more researchers to use domain and data type specific repositories |
|#58 | [My project involves the secondary analysis of whole genome sequencing data currently available in dbGaP. I am planning to identify structural variants from these individuals, and would like to make the VCF files publicly available (if possible)](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-58.md)  | It's not clear how I can share these data since VCFs require controlled access, but the original data came from another researcher  | My goal is to identify structural variants in existing whole genome datasets and share the findings and data with other researchers |
|#81 | [As a program officer, I want to make researchers aware of common issues to avoid when writing their DMS Plans](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-81.md)  | Most DMS Plans come in with the same issues over and over again, causing delays in funding | My overall goal is to reduce the number of DMS Plan revisions required prior to making an award |
|#82  | [As NICHD ODSS, we want to educate researchers as to why they should not control access to their own data](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-82.md)  | Researchers often propose to serve as gate-keepers to their data in DMS Plans, but this is not a sustainable or equitable practice, and it does not align with NIH’s definition of data sharing | Overall, we want researchers to use controlled access data repositories for sharing sensitive data  |


</br>

<b>
