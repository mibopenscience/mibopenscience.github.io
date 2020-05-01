---
layout: uvparagraphs
author: NvU
date: 01-05-2020
version: 0.3
status: concept
title: FAIR data preservation and publishing
fontawesome: fa fa-check-square-o fa-stack-1x fa-inverse
permalink: datapackage
---

#### Preservation of research data serves two purposes. It facilitates verification and replication of your research (results), and it facilitates the reuse of research data. The [FAIR principles](https://www.go-fair.org/fair-principles/) (Findable, Accessible, Interoperable, Reusable) provide a useful framework for enabling maximum (re)use of data within ethical and legal (privacy) boundaries.

---

### What?
AUAS, following the [Netherlands Code of Conduct for Research Integrity](https://doi.org/10.17026/dans-2cj-nvwu), requires that research data and related documentation are stored for the required amount of time to ensure that they can be consulted efficiently and at short notice. Furthermore, research data must, to the extent possible, meet the FAIR principles. By creating a data package and depositing this package in a data repository like UvA/HvA figshare you already fulfill most of the preservation and FAIR requirements, although making (meta)data interoperable and machine-readable asks for additional FAIR-expertise (at the start of your project). It is important to realize that preservation applies to both quantitative and qualitative research data, and that preservation refers to (static) research data 
> factual records (numerical scores, textual records, images and sounds) used as primary sources for scientific research, and that are commonly accepted in the scientific community as necessary to validate research findings. A research data set constitutes a systematic, partial representation of the subject being investigated.(7)

In preserving data you have to think about what data to preserve, which information is necessary (for others and computers) to understand what happened with the data from collection to the final results and tables in an article (e.g. log books, syntax, codebooks), what to do with a key file (linking table) with personal information and identification numbers, where to store paper (non-digital) data, how to name different files (so you know for example what syntax file belongs to what data file), and under what conditions others may (be granted) access to the data. 

---

### Why is preserving research data important and what are benefits for you?
- Just like publications, data that you have collected is research output too. By depositing it in a data repository you increase your research output (via UvA/HvA figshare the dataset will be automatically registered in PURE)
- You increase the visibility of your work
- More and more journals and funders ask how you will make the research data findable, accessible, interoperable and reusable
- By describing your data (via metadata) and providing conditions for reuse you clarify what other can and cannot do with the data
- The data you collected are protected against corruption and loss
- You facilitate verification of your research results and reuse of your data
- You could get more credit for your work because besides citing your article other could also site the dataset
- You prevent ad hoc hassle when you fall ill or accept another job, enabling colleagues to efficiently take over
- Probably, in the informed consent you promised participants to take care of their (sensitive) data in a certain (careful and responsible) way
- - Attracting new partnerships with researchers, business, policy and broader communities
- Enabling new (more data-driven) research questions to be answered. In the field of AI the issue is not computing power or algorithms but the availability and accessibility (under the right conditions) of data

---

### What are the FAIR principles?
The FAIR principles provide guidelines for creating digital resources such as datasets, code, workflows, and other research objects, in a way that makes them Findable, Accessible, Interoperable, and Reusable for both humans and machines (computers). Note that FAIR data is not the same as open data. Rather, you specify under which conditions others may access the data and you can make transparent why (part of) the data is not openly available.

![alt text]({{ site.baseurl }}/img/fairplaatje2.png "FAIR principles from Foster Open Science")

To some extent you could apply the FAIR principles to software that you developed in a research project. Check (this website)[ https://fair-software.nl/] for five FAIR recommendations for software. Another development is the interoperability (machine-readability) of the informed consent form so that it is immediately clear for both humans and computers which data or records may be reused.

#### How FAIR are you?
You could be more or less FAIR. Below we describe a way, by creating a data package and using UvA/HvA figshare, to become ‘FAIR enough’. Becoming even more FAIR, especially in terms of interoperability and machine-readability, requires FAIR-expertise from the start of your project. The steps below are based on:
- [How FAIR are your data checklist](https://doi.org/10.5281/zenodo.3405141)
- [Guidelines to FAIRify data management and make data reusable](https://doi.org/10.5281/zenodo.3368858)
This chapter will be updated when more results of the ‘UV zaaigeld’ project [FAIR: geen woorden maar data](https://www.hva.nl/urban-vitality/gedeelde-content/projecten/overkoepelende-projecten/fair-data.html) are available.

--- 

### How and when?

#### Starting points / prerequisites
- Every scientific publication and PhD-dissertation is accompanied by a data package
- Other situations where preservation could be relevant:
1. Upon completion of a research project, regardless of whether or not the data were used in a publication (especially when the data may be of use for a new project)
2. Upon completion of raw data collection to ensure secure storage and prevent loss or modification of the raw data (i.e. a locked or frozen version of your raw data)
3. Storing copies of datasets from long-lasting cohort studies or registries that were used in a publication
- These steps apply to research projects for which AUAS bears formal responsibility
1. Falling under Dutch law (‘WMO-plichtige’) studies, the sponsor (‘verrichter’) of the study bears responsibility unless otherwise agreed (in writing)
2. Concerning PhD-projects: this depends on the arrangements made between AUAS and the university/institution where the doctorate is obtained
- The data package will be deposited in UvA/HvA figshare before publication of a scientific article so the data package can be cited in the article via the persistent identifier (DOI) of the data package

#### Findability
The first step in (re)using data is that it should be possible for other to find (the description of) the data. By using the data repository UvA/HvA figshare you achieve this to a large extent. UvA/HvA figshare gives you a persistent identifier (DOI) for the dataset and uses standard metadata fields (known as Dublin Core) to describe the data.
- [UvA/HvA figshare](https://uvaauas.figshare.com/auas) 
- For more information about UvA/HvA Figshare, see [here](https://rdm.uva.nl/uva-hva-figshare/introductie.html)

#### Accessibility
Once someone finds the required data, (s)he needs to know if and how can they be accessed, under which conditions and restrictions. FAIR does not mean that data need to be open!
- If access is restricted, provide contact information in UvA/HvA figshare to discuss access to the data and to prepare a data user agreement
- (Raw) datasets should not contain directly identifying personal (contact) information not needed for analyses. This information is stored in a ‘key file’ and should be preserved separately from the research data (if preservation of this key file is necessary at all). Actually, this is something to think about before you start collecting data rather than at the end 
- For more information about key file preservation, see here

#### Interoperability
(Meta)data should conform to recognized formats and standards to allow them to be combined and exchanged efficiently. This is the most difficult part of FAIR because it requires the use of vocabularies and ontologies such as SNOMED and LOINC. In the project [FAIR: geen woorden maar data](https://www.hva.nl/urban-vitality/gedeelde-content/projecten/overkoepelende-projecten/fair-data.html) we explore how this could be implemented eventually. For now, it is good to think about the format in which you store your data. 
- The aim is to use open, preferred formats as much as possible. Data repositories can ensure the long-term preservation in terms of readability and accessibility of the data. See [here](https://dans.knaw.nl/en/about/services/easy/information-about-depositing-data/before-depositing/file-formats?set_language=en) for the preferred formats according to DANS

#### Reusability
The ultimate goal of FAIR is to optimize the reuse of data. To achieve this, metadata and data should be well-described and documented so that they can be replicated, understood and/or combined in different settings. Think of variable labels, codebooks, protocols and instruments used, attaching a license, etc. This helps to avoid these issues:
[![Reuse video](https://www.youtube.com/watch?v=N2zK3sAtr-4 "Reuse")

- Create a data package to deposit in UvA/HvA figshare. See <a href="/files/UV_Datapackage_v02_concept.pdf" download="Checklist datapackage">the checklist</a> for more information about what to include in a data package
- This checklist may not be complete yet for falling under the Dutch law ('WMO-plichtige') studies
- The components of the data package should all be in English
- UvA/HvA figshare provides the possibility to attach a license to the data
- For reuse it is important for others to know what was stated in the informed consent about reuse of data for other (similar) purposes. This information should be included in the data package. 

---

#### More information and credits
- This chapter is based on:
1. [HvA RDM richtlijnen 2018 (intranet, Dutch)](https://beleid.mijnhva.nl/nl/PublishingImages/Paginas/default/Onderzoeksdatamanagementbeleid%20%28Research%20Data%20Management%29.pdf), article 8-12
2. [Netherlands Code of Conduct for Research Integrity 2018](https://www.vsnu.nl/files/documents/Netherlands%20Code%20of%20Conduct%20for%20Research%20Integrity%202018.pdf), article 3.3.25, 3.4.25, 3.4.45 and 4.4
3. The data package checklist is largely based on [Guidelines for the archiving of academic research for faculties of behavioural and social sciences in the Netherlands](https://www.universiteitleiden.nl/binaries/content/assets/sociale-wetenschappen/pedagogische-wetenschappen/ethiek-commissie/gedragscodes/guidelines-for-the-archiving-of-academic-research-for-faculties-of-bss.pdf) and the [local implementation guidelines of the Faculty of Behavioural and Movement Sciences](https://www.fgb.vu.nl/nl/over-de-faculteit/facultaire-commissies/vaste-commissie-wetenschap-en-ethiek/index.aspx)
4. [How FAIR are your data checklist](https://doi.org/10.5281/zenodo.3405141)
5. [Guidelines to FAIRify data management and make data reusable](https://doi.org/10.5281/zenodo.3368858)
6. GO FAIR website, FAIR principles. https://www.go-fair.org/fair-principles/
7. OECD (2007). Principles and Guidelines for Access to Research Data from Public Funding. OECD Publishing, Paris. https://www.oecd.org/sti/inno/38500813.pdf
8. Image FAIR data principles from: https://book.fosteropenscience.eu/en/

 



