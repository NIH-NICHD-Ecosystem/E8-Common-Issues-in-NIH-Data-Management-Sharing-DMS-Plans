#### Library Main Navigation: &nbsp; &nbsp;  <b>  [Ecosystem Library Home](https://github.com/NIH-NICHD-Ecosystem) </b> &nbsp; | &nbsp;[User Stories](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/README.md) &nbsp; | &nbsp; [Efforts](https://github.com/NIH-NICHD-Ecosystem/Efforts/blob/main/README.md) &nbsp; | &nbsp; [Library Help](https://github.com/NIH-NICHD-Ecosystem/LibraryHelp/blob/main/README.md)


</br>

# E8 Common Issues in NIH Data Management & Sharing DMS Plans

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


#### 1. Missing details for data that will be generated and shared

When describing what data will be generated and shared, include details such as species (or other source), format, and amount.
Below are examples of how to complete the table in #6 of the updated DMS Plan Format page:

| Expected Data Type  | Established Repository or Example | 
| :----------| :---------- |
|human genomic sequence and variant data from 200 children (FASTQs, VCFs)|dbGaP and SRA (controlled access)|
|clinical data from 1000 patients (CSV) |NICHD DASH (controlled access)|
<br/>

| Expected Data Type  | Established Repository or Example | 
| :----------| :---------- |
|functional magnetic resonance images (DICOM) of 60 rat brains|DANDI (open access)|
<br/>

| Expected Data Type  | Established Repository or Example | 
| :----------| :---------- |
|qualitative surveys about 45 hospitals (CSV)|The Qualitative Data Repository (open access)|
<br/>

NICHD ODSS continues to receive plans that are ambiguous about whether the data will come from a human or a fish, but these details matter because they impact whether other aspects of the DMS Plan are appropriate. For example: Should the data be shared as controlled access in the repository (only needed for human data)? Is the data repository suitable? Will other researchers be able to use these data files? Is a [Genomic Data Sharing Institutional Certification](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/gds/institutional-certifications) required before award? 


#### 2. Sharing only publication-associated data

Many plans indicate the researcher will share only data associated with publications or that data will be shared as supplementary materials with publications. However, the DMS Policy expects that all scientific data will be shared, by the end of the award period, regardless of publication status.

The DMS Plan should encompass sharing publication-associated data and scientific data not related to publications.

From its inception, sharing non-publication-associated data was built into the policy’s definition of [scientific data](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-21-013.html#:~:text=Scientific%20Data%3A,as%20laboratory%20specimens), which is tied to principles of data quality, reuse, and reproducibility regardless of publication. The concept was further emphasized by both the White House Office of Science and Technology Policy (OSTP) 2022 memorandum on [Ensuring Free, Immediate, and Equitable Access to Federally Funded Research](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/08/08-2022-OSTP-Public-Access-Memo.pdf) (PDF 372 KB), and the NIH Plan to Enhance Public Access to the Results of NIH-Supported Research ([NOT-OD-23-091](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-23-091.html)).


#### 3. Not sharing data in established data repositories

The NIH DMS Policy expects that researchers will share scientific data through established data repositories. Sharing data through publications, local servers, or lab websites is not the same as using a repository and does not meet the Policy’s expectations.
Identifying, learning about, and committing to the repositories’ processes and features helps you plan your data generation strategy (e.g., required metadata, standard forms), anticipate your workload (will the repository help you with de-identification?), and plan your budget accordingly (for your team’s time and effort). NICHD created a [Data Repository Finder](https://data-repository-finder.ll.mit.edu/) ↗️ to help researchers select an appropriate repository; [other NIH resources](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/scientific) are also available.

Data repositories offer many benefits including fostering collaboration and building community. They leverage technical and scientific expertise to make data Findable, Accessible, Interoperable, and Reusable (FAIR), through use of common formats and search and visualization interfaces, and by providing continuous and refined processes for data submission, quality control, curation, harmonization, and release of multiple datasets over time. In addition, many repositories are actively working to adhere to all of the [White House OSTP’s Desirable Characteristics of Data Repositories for Federally Funded Research](https://bidenwhitehouse.archives.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf) (PDF 373 KB), which will further improve data FAIRness, security, and the ability to track use of shared data.

You should not use a repository’s services  to mint Digital Object Identifies (DOIs) for data that are not shared through an established data repository; DOIs are meant to link to the location where scientific data are accessible to the research community. 

#### 4. Not using appropriate domain- or discipline-specific data repositories

NICHD ODSS’s analysis of DMS Plans submitted to NICHD found a clear over-reliance on generalist data repositories, which accept any data type or format. Although [generalist repositories](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/scientific#generalist-repositories), can be a tempting default for sharing data, NIH DMS Policy guidance emphasizes that domain- or discipline-specific data repositories are always preferred.

NICHD researchers should use the NICHD [Data and Specimen Hub (DASH)](https://dash.nichd.nih.gov/) for sharing human clinical and population health data and National Center for Biotechnology Information (NCBI) repositories, such as the database of Genotypes and Phenotypes ([dbGaP](https://www.ncbi.nlm.nih.gov/gap/)), the Sequence Read Archive ([SRA](https://www.ncbi.nlm.nih.gov/sra/)), and the Gene Expression Omnibus ([GEO](https://www.ncbi.nlm.nih.gov/geo/)), for sharing genetic data, unless approved to use an alternative NIH-designated data repository for example by the funding announcement. For other types of data, other discipline, domain, or data-type specific data repositories should be considered first, as they have services and features designed to serve the needs of their specific research communities, which ultimately increase the usability and overall value of shared data. 

Generalist repositories are useful, and [NIH is investing in making them better](https://datascience.nih.gov/data-ecosystem/generalist-repository-ecosystem-initiative), but you should only use them if there is not an appropriate domain-specific data repository available. 

Extra care should be taken when selecting data repositories that support controlled access sharing (note related issue #5). Controlled access data repositories must adhere to additional security and operational standards, such as those described in [Requirements for NIH Controlled-Access Data Repositories and Users](https://grants.nih.gov/policy-and-compliance/policy-topics/sharing-policies/accessing-data/requirements) and the forthcoming requirements of the [Draft NIH Controlled-Access Data Policy](https://grants.nih.gov/grants/guide/notice-files/NOT-OD-26-023.html).

Finally, it is unacceptable for researchers to propose to build a new data repository or to share data through a forthcoming data repository, as part of the DMS Plan.  





# User Stories
[Instructions] [Delete before publishing] - At least one User Story is required for every Effort. A User Story is an informal, general explanation of a desired ecosystem feature or process written from the perspective of a specific end user. The purpose of a User Story is to articulate how a piece of work will deliver a particular value back to the user. Its basic form follows Agile development guidance with the template: As a (user), I (want to), (so that). Library user stories are gathered from the NICHD community and are used to initiate Ecosystem efforts. Library documents should each link back to origin user stories.

The following User Stories motivated and informed this Effort:

| S#  | User Story | Current Problem | User Goal |
|----|----|----|-----|
|#| [Insert User Story here](https://github.com)</li></ul> | Insert Current Problem here| Insert User Goal here |


<br>

| S#  | User Story | Current Problem | User Goal
| :-------------| :------------- | :------------ | :------------ |
|#38| [As NICHD ODSS, we are observing that researchers are over-relying on generalist repositories in the DMS Plans (i.e., defaulting to using generalist repositories instead of domain or data type specific repositories), we want to encourage researchers to use domain and data type specific data repositories as much as possible to take advantage of community-specific curation services and data repository features and align with DMS Policy expectations](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-38.md)  | When researchers are generating multiple data types in their research applications they often default to using one generalist repository, instead of multiple domain or data type specific repositories as expected under the DMS Policy | My goal is to get more researchers to use domain and data type specific repositories |
|#58 | [My project involves the secondary analysis of whole genome sequencing data currently available in dbGaP. I am planning to identify structural variants from these individuals, and would like to make the VCF files publicly available (if possible)](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-58.md)  | It's not clear how I can share these data since VCFs require controlled access, but the original data came from another researcher  | My goal is to identify structural variants in existing whole genome datasets and share the findings and data with other researchers |
|#81 | [As a program officer, I want to make researchers aware of common issues to avoid when writing their DMS Plans](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-81.md)  | Most DMS Plans come in with the same issues over and over again, causing delays in funding | My overall goal is to reduce the number of DMS Plan revisions required prior to making an award |
|#82  | [As NICHD ODSS, we want to educate researchers as to why they should not control access to their own data](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-82.md)  | Researchers often propose to serve as gate-keepers to their data in DMS Plans, but this is not a sustainable or equitable practice, and it does not align with NIH’s definition of data sharing | Overall, we want researchers to use controlled access data repositories for sharing sensitive data  |


</br>

<b>
