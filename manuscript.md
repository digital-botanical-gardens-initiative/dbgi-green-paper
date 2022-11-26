---
title: The Digital Botanical Gardens Initiative
keywords:
- natural products
- metabolomics
- chemodiversity
- biodiversity
- linked open data
- knowledge graph
- biodiversity conservation
lang: en-US
date-meta: '2022-11-26'
author-meta:
- The Digital Botanical Gardens Initiative Consortium
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="The Digital Botanical Gardens Initiative" />
  <meta name="citation_title" content="The Digital Botanical Gardens Initiative" />
  <meta property="og:title" content="The Digital Botanical Gardens Initiative" />
  <meta property="twitter:title" content="The Digital Botanical Gardens Initiative" />
  <meta name="dc.date" content="2022-11-26" />
  <meta name="citation_publication_date" content="2022-11-26" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="The Digital Botanical Gardens Initiative Consortium" />
  <link rel="canonical" href="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/" />
  <meta property="og:url" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/" />
  <meta property="twitter:url" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/" />
  <meta name="citation_fulltext_html_url" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/" />
  <meta name="citation_pdf_url" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/28461f4d9bc0fe5ee79771783b273dcd48cd7462/" />
  <meta name="manubot_html_url_versioned" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/28461f4d9bc0fe5ee79771783b273dcd48cd7462/" />
  <meta name="manubot_pdf_url_versioned" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/28461f4d9bc0fe5ee79771783b273dcd48cd7462/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/28461f4d9bc0fe5ee79771783b273dcd48cd7462/))
was automatically generated
from [digital-botanical-gardens-initiative/dbgi-green-paper@28461f4](https://github.com/digital-botanical-gardens-initiative/dbgi-green-paper/tree/28461f4d9bc0fe5ee79771783b273dcd48cd7462)
on November 26, 2022.
</em></small>

## Authors



+ **The Digital Botanical Gardens Initiative Consortium**
  ^[✉](#correspondence)^<br>
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [digital-botanical-gardens-initiative](https://github.com/digital-botanical-gardens-initiative)
    <br>
  <small>
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/digital-botanical-gardens-initiative/dbgi-green-paper/issues)
or email to
The Digital Botanical Gardens Initiative Consortium \<dbgi@protonmail.com\>.


:::


## Abstract {.page_break_before}

The Digital Botanical Gardens Initiative (DBGI) ambitions to explore innovative solutions for the collection, management and sharing of digital information acquired on living botanical collections. A particular focus will be placed on the large scale characterization of the chemodiversity of living plants collections through mass spectrometric approaches. The acquired data will be structured, organized and connected with relevant metadata through semantic web technology. The gathered knowledge will then inform ecosystem functioning research and orient biodiversity conservation projects. The DBGI initially aims to take advantage of the readily available living collections of Swiss botanical gardens to establish robust and scalable chemo- and biodiversity digitisation workflows. The ultimate goal is to apply these approaches in the field and at the global scale in wild ecosystems. 

## Goals {.page_break_before}


![
**Main goals of the Digital Botanical Gardens Initiative.**
](images/dbgi-goals.svg "Workflow"){#fig:dbgi-goals width="100%"}

The main goals of the DBGI are resumed in Figure @fig:dbgi-goals Some details are given hereafter:

**1. Establish chemical extracts libraries of Swiss botanical gardens.** These chemical libraries can be considered as complementary to herbarium samples. They are easily conserved over time and in a reasonable space. They represent the chemical diversity of a sample. They can be easily aliquoted. They can be screened for bioassays.

**2. Digitize, through mass spectrometry, the chemodiversity of Swiss botanical gardens.** Here high-resolution mass spectrometry is considered as a digital scanner allowing to capture the chemical fingerprint of the profiled sample. State-of-the-art computational metabolomics solutions are used to organize and annotate the acquired spectra with molecular data.

**3. Gather chemical information and relevant samples metadata in a tailored knowledge graph.** Chemical information acquired at the previous step (spectra and chemical structures) are connected to relevant samples metadata (taxonomy, phenology, geolocalisation, time of collection etc.). For this semantic web technologies (namely the RDF data model) are employed and a tailored knowledge graph is established.

**4. Connect to existing ontologies (bio, chemo) and biodiversity digitization projects.** Chemical and biological objects of the graph are connected to relevant pre-established ontologies (e.g. [CHEBI](https://www.ebi.ac.uk/chebi/), [Plants Ontology](https://bioportal.bioontology.org/ontologies/PO)) and data graphs (e.g. [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page)). Connection with complementary biodiversity digitization efforts will be done (e.g [BiCIKL](https://bicikl-project.eu/), [Dissco](https://www.dissco.eu/))

**5. Establish web and programmatic interfaces for the query of the acquired knowledge.** A web interface will allow a convenient access to the data acquired within the framework of the project. A dashboard will allow simple visualizations (e.g pie charts, barplots, treemap) to interpret the data. In addition a SPARQL endpoint and an application programming interface (API) will allow retrieval of data programmatically.

**6. Illustrate the feasibility and advantages of an end-to-end Open Science project.** The DBGI will strictly follow the [Open Science](https://en.wikipedia.org/wiki/Open_science) guidelines by using open-source software and making available the acquired data and scripts under an open license agreement. In addition the DBGI results will be published at the moment they are acquired (previous to formal publication or even pre-prints) thus following the [Open Notebook Science](https://en.wikipedia.org/wiki/Open-notebook_science) concepts. 

**7. Establish robust and scalable workflows for the digitization of wild ecosystems biodiversity.** The DBGI, albeit ambitious, is a pilot project. The future objective is to propose digitization workflows for the characterization of the wild ecosystems chemodiversity, on a global scale. These workflow will be central to the future Earth Metabolome Initiative.

**8. Provide "molecular arguments" for biodiversity conservation policies.** The ultimate goal of DBGI is to use all the gathered metabolic information to support, extend or implement conservation efforts worldwide. We believe that by providing chemical maps of the landscape it will be possible to contribute to the prioritization of conservation and restoration targets . In other words, by establishing large scale chemical maps we expect to provide “molecular arguments” to biodiversity conservation endeavors (e.g. _“This piece of land has a high content of antibacterial scaffolds.”_ or _“This place might be poor in species diversity but rich in a rare chemodiversity”_.)

## Background and context {.page_break_before}


Biodiversity is a major determinant of ecosystem stability [@doi:10.1146/annurev-ecolsys-120213-091917]. Hundreds of studies spanning terrestrial and aquatic ecosystems support that higher levels of biodiversity, in all its forms, promote better ecosystem functions, such as carbon sequestration, underpinning human well‐being [@doi:10.1126/science.1064088;@doi:10.1007/s004420050035]. Sadly, earth is experiencing a major biodiversity crisis and of the estimated nine million species of fungi, plants, and animals have been described [@doi:10.1038/news.2011.498], about a million species are currently at risk of extinction and may go extinct before the end of the century [@doi:10.5281/zenodo.6417333]. One major issue is that more than 80% of the estimated biodiversity still awaits to be described. We are in fact facing what is now called the Anthropocene extinction (sixth mass extinction) [@doi:10.1126/science.aau0191]. In order to try to deviate from these alarming trends, all possible efforts must be made by the responsible (i.e. our species) for the conservation of biodiversity. For this, the characterisation and documentation of biodiversity is a fundamental prerequisite. 
Over 3.5 billion years of evolution, natural selection, the craftsman of biodiversity, has created an overwhelming array of molecular entities. Myriad compounds are produced by all living organisms from bacteria to whales, forming the backbone of the ever-growing tree of life. Through the lens of chemistry, every species, biotic interaction, and community, reveals a unique ensemble of molecular structures: the metabolome. These chemical assemblages are a valuable, yet largely unexplored reflection of biodiversity and ecosystem functioning. To go beyond the simple quantitative representation of biodiversity provided by species inventories, and to reinforce our understanding of links between biodiversity and ecosystem functioning, we see chemical diversity as an alternative and highly complementary view of the diversity of our planet’s ecosystems.




## Rationale {.page_break_before}

With these urgent biodiversity characterization objectives in mind we are setting up the Digital Botanical Gardens Initiative (DBGI), which aims to develop robust and scalable workflows for the digitization of botanical gardens using several approaches. The central one being the use of analytical chemistry strategies to build information-rich chemical maps that will guide researchers focusing on biodiversity characterization and conservation.

![
**Characteristics of three main plant biodiversity sources for the scientist.**
](images/dbgi-lab-botanical-wild.svg "Workflow"){#fig:dbgi-lab-botanical-wild width="60%"}

Sampling plants for chemical characterization can be done in three ways, either from natural living collections (botanical gardens), in the wild, or by growing plants in highly controlled settings (See Figure @fig:dbgi-lab-botanical-wild for an overview of the advantages and inconveniences of each biodiversity source). For this first project, the sampling in botanical gardens is the  chosen option, as within a very accessible location, thousands of species, which are already identified, labeled and organized,  can be readily sampled.


## Outline of the research {.page_break_before}

The aim of the DBGI is to characterize the chemodiversity of the all botanical gardens of Switzerland. This ambitious objective requires us to evaluate and test the entire workflow and methodology. For this, the initiators of the DBGI started gathering preliminary data from two botanical collections: the Jardin Botanique de l’Université de Fribourg ([JBUF](https://www.unifr.ch/jardin-botanique/fr/)) and the Jardin Botanique de Neuchâtel ([JBN](https://www.jbneuchatel.ch/)). This choice was made for practical reasons (these are the respective working places of the DBGI initiators) but also because these two gardens each offer their unique characteristics. On one hand the JBUF presents over 5000 species systematically organized to reflect the Angiosperm Phylogeny Group (APG) system. The JBUF researchers are specialized in conservation biology. On the other hand, the JBN presents over 2000 species organized in 8 sub-gardens. The JBN has a focus on ethnomedicinal plants.
Below, we will briefly outline the research workflow envisioned for the DBGI. The main steps have been schematized in Figure 3. The overall workflow can be divided into two main parts: one dealing with physical objects (upper part of Figure 3) and a second one dealing with data and metadata acquired from these objects (lower part of Figure @fig:dbgi-general-workflow). 

**_Physical objects._** Starting from a botanical garden (a living specimens collection), the aim is to sample each specimen and to build two libraries: a library of dried plant material and a library of chemical extracts. The dried plant material library will serve as a backup for extractions to be repeated, further characterization of compounds, or for orthogonal analysis (e.g. genetic sequencing). The chemical extracts library will be the source material for the mass-spectrometry digitization stage. This library will also be available for backups and orthogonal analysis (e.g. NMR profiling or bioassays campaigns). Complementary to herbarium, these two libraries offer an efficient way (reduced space, long term storage) to capture and conserve the chemistry of the botanical gardens.

![
**Data types and fluxes in the DBGI.**
](images/dbgi-general-workflow.svg "Workflow"){#fig:dbgi-general-workflow width="100%"}

**_Digital objects._** For all operations occurring on physical objects (sampling, conservation, extraction), metadata are collected to document the experiment. For each botanical garden, data collection is made at the species level. A species is collected for each garden, curated and taxonomically resolved (using the Open Tree of Life framework) in order to be compared across gardens. The [Botalista](https://botalista.community/) platform will also be exploited at this step. For each collected sample, data are acquired at a finer granularity (namely at the specimen level). Here we take advantage of the [iNaturalist](https://www.inaturalist.org/) platform and app. Using a smartphone, pictures of the sampled specimen (including eventual label in the botanical gardens, sampled organ and collection label), collector identity, date and geolocation are conveniently captured at the time of the collection. This data is then automatically collected by the [iNaturalist DBGI project](https://www.inaturalist.org/projects/digital-botanical-gardens-initiative). The data of the project can then be programmatically accessed via the [iNaturalist API](https://www.inaturalist.org/pages/api+reference). All species, specimens and experimental metadata will be collected and managed through an SQL database and accessed through a [NocoDB](https://www.nocodb.com/) instance for a convenient tracking of the samples by the DBGI participants.

The mass-spectrometry digitization then constitutes the core of the chemical information acquisition process. We use Ultra High Performance Liquid Chromatography coupled to High Resolution Mass Spectrometry (UHPLC-HRMS) to acquire fragmentation data in an untargeted fashion. Building on our computational metabolomics expertise we then organize and annotate the acquired pool of MS data. Here we will take advantage of five central tools (four of which were conceived by us). Molecular networking [@doi:10.1038/nbt.3597] will serve as a basis for spectral organization. The metabolite annotation will be performed by spectral matching against a theoretical natural products spectral database [@doi:10.1021/acs.analchem.5b04804] and via a taxonomically informed scoring process [@doi:10.3389/fpls.2019.01329] fed by the widest open resource of natural products biological occurrences ([LOTUS](https://www.wikidata.org/wiki/Wikidata:WikiProject_Chemistry/Natural_products) [@doi:10.7554/eLife.70780]).

## Dissemination of the results {.page_break_before}

The DBGI conducts this project following the Open Science principles, and by following the Open Notebook Science concept. This approach allows all research artifacts (e.g. research proposals, drafts, ideas, source code, raw and processed data etc.) produced in the frame of the DBGI to be publicly available immediately, from the moment of their production, and not only after peer-reviewed publication.
To implement the DBGI Open Notebook we employ Dendron, an open-source and lightweight note-taking and knowledge management software. Dendrons are built using an ingenious system of markdown files hierarchically organized based on their filename. This allows for extremely efficient note searching and refactoring of the hierarchies. Dendrons can be conveniently shared across members of the DBGI, versioned via git and automatically published as websites. The DBGI Dendron can be browsed at http://www.dbgi.org/dendron-dbgi/. 
Regarding raw data sharing, specimen-related information are hosted on the iNaturalist DBGI project  home page and pictures are shared under a permissive CC0 license allowing further reuse in Wikidata for example. Mass spectrometry profiles and metabolite annotation files will be hosted on the MassIVE data platform where they will benefit from a permanent DOI.  
All the code written in the frame of the DBGI will be publicly shared and versionned through the DBGI Github organization. Ideas, comments and issues will be collected using Github discussions.




## DBGI Consortium {.page_break_before}

Note: the DBGI is welcoming any researchers interested to join the initiative. We expect people to participate according to their ressource/time/interest at the level they suit.
Initiators
Pierre-Marie Allard (COMMONS Lab, University of Fribourg)
Emmanuel Defossez (Institute of Biology, University of Neuchâtel & JBN)
Core team 
You have ca. 2 hours / week to dedicate to the DBGI plus time for 6 meetings a year ? You are willing to lead a group of Collaborators (see below) or gather Expert knowledge (see below) for the following areas. We need you !

Sampling & Collections Management
Metabolomics & Computational Mass Spectrometry
Linked data & Knowledge management
Open Science & Dissemination
Fundamental & Applied Research (from functional ecology to drug discovery)
Biodiversity Conservation


Collaborators 
You are willing to put your hands in the dirt and concretely contribute to the DBGI under the following areas. We need you ! If you have expert knowledge to share but not that much time see Expert section 
Sampling & Collections Management
Edouard Bruelhart (COMMONS Lab, University of Fribourg)
Gregor Kozlowski (JBUF)
??? (to be contacted) Blaise Mulhauser (JBN)
Nadir Alvarez (Université de Genève)
Donat Agosti (Plazi)
Cyril Boillat (Botalista)
??? (to be contacted) Laurent Kneubuhl (Botalista)
??? (to be contacted) Brian Sedio (University of Texas at Austin)
Metabolomics & Computational Mass Spectrometry
Ming Wang (University of Riverside)
??? (to be contacted) Gaétan Glauser (University of Neuchâtel)
??? (to be contacted) Brian Sedio (University of Texas at Austin)
Linked data & Knowledge management 
??? (to be contacted) Philippe Cudré-Mauroux (University of Fribourg)
Christophe Dessimoz (University of Lausanne)
Donat Agosti (Plazi)
Cyril Boillat (Botalista)
??? (to be contacted) Laurent Kneubuhl (Botalista)
??? (to be contacted) Jakub Galgonek (Elixir Prague)
??? (to be contacted) Marco Pagni (SIB)
Tarcisio Mendes (SIB)
Ana-Claudia Sima (SIB)
Open Science & Dissemination
Christophe Dessimoz (University of Lausanne)
Donat Agosti (Plazi)
Henry Lütcke (ETHZ)
Bernd Rinn (ETHZ)
Caterina Barillari (ETHZ)
Fundamental & Applied Research (from functional ecology to drug discovery)
Sergio Rassmann (University of Neuchâtel)
Thomas Walker (University of Neuchâtel)
??? (to be contacted) Patrice Descombes (University of Lausanne)
??? (to be contacted) Nadir Alvarez (Université de Genève)
??? (to be contacted) Brian Sedio (University of Texas at Austin)
Biodiversity Conservation
Gregor Kozlowski (JBUF)
??? (to be contacted) Patrice Descombes (University of Lausanne)
Experts
You have expertise in the following areas and you are OK that we pick your brain for let’s say … a one hour meeting each month.
Sampling & Collections Management
Gregor Kozlowski (JBUF)
??? (to be contacted) Blaise Mulhauser (JBN)
Nadir Alvarez (Université de Genève)
Donat Agosti (Plazi)
Cyril Boillat (Botalista)
??? (to be contacted) Laurent Kneubuhl (Botalista)
Metabolomics & Computational Mass Spectrometry
Ming Wang (University of Riverside)
??? (to be contacted) Gaétan Glauser (University of Neuchâtel)
??? (to be contacted) Brian Sedio (University of Texas at Austin)
Linked data & Knowledge management 
??? (to be contacted) Philippe Cudré-Mauroux (University of Fribourg)
Christophe Dessimoz (University of Lausanne)
Donat Agosti (Plazi)
Cyril Boillat (Botalista)
??? (to be contacted) Laurent Kneubuhl (Botalista)
??? (to be contacted) Jakub Galgonek (Elixir Prague)
??? (to be contacted) Marco Pagni (SIB)
Tarcisio Mendes (SIB)
Ana-Claudia Sima (SIB)
Open Science & Dissemination
Christophe Dessimoz (University of Lausanne)
Donat Agosti (Plazi)
Henry Lütcke (ETHZ)
Bernd Rinn (ETHZ)
Caterina Barillari (ETHZ)
Fundamental & Applied Research (from functional ecology to drug discovery)
Sergio Rassmann (University of Neuchâtel)
Thomas Walker (University of Neuchâtel)
??? (to be contacted) Patrice Descombes (University of Lausanne)
??? (to be contacted) Nadir Alvarez (Université de Genève)
??? (to be contacted) Brian Sedio (University of Texas at Austin)

Biodiversity Conservation
Gregor Kozlowski (JBUF)
??? (to be contacted) Patrice Descombes (University of Lausanne)
Botanical Gardens
Jardin Botanique de l’Université de Fribourg (JBUF)
Jardin Botanique de Neuchatel (JBN)
??? Conservatoire et Jardins Botanique de Genève (CJBG)
??? Jardin Botanique de Lausanne (JBL)


This manuscript is a template (aka "rootstock") for [Manubot](https://manubot.org/ "Manubot"), a tool for writing scholarly manuscripts.
Use this template as a starting point for your manuscript.

The rest of this document is a full list of formatting elements/features supported by Manubot.
Compare the input (`.md` files in the `/content` directory) to the output you see below.

## Basic formatting

**Bold** __text__

[Semi-bold text]{.semibold}

[Centered text]{.center}

[Right-aligned text]{.right}

*Italic* _text_

Combined *italics and __bold__*

~~Strikethrough~~

1. Ordered list item
2. Ordered list item
    a. Sub-item
    b. Sub-item
        i. Sub-sub-item
3. Ordered list item
    a. Sub-item

- List item
- List item
- List item

subscript: H~2~O is a liquid

superscript: 2^10^ is 1024.

[unicode superscripts](https://www.google.com/search?q=superscript+generator)⁰¹²³⁴⁵⁶⁷⁸⁹

[unicode subscripts](https://www.google.com/search?q=superscript+generator)₀₁₂₃₄₅₆₇₈₉

A long paragraph of text.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Putting each sentence on its own line has numerous benefits with regard to [editing](https://asciidoctor.org/docs/asciidoc-recommended-practices/#one-sentence-per-line) and [version control](https://rhodesmill.org/brandon/2012/one-sentence-per-line/).

Line break without starting a new paragraph by putting  
two spaces at end of line.

## Document organization

Document section headings:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### A heading centered on its own printed page{.center .page_center}

<!-- an arbitrary comment. visible in input, but not visible in output. -->

Horizontal rule:

---

`Heading 1`'s are recommended to be reserved for the title of the manuscript.

`Heading 2`'s are recommended for broad sections such as *Abstract*, *Methods*, *Conclusion*, etc.

`Heading 3`'s and `Heading 4`'s are recommended for sub-sections.

## Links

Bare URL link: <https://manubot.org>

[Long link with lots of words and stuff and junk and bleep and blah and stuff and other stuff and more stuff yeah](https://manubot.org)

[Link with text](https://manubot.org)

[Link with hover text](https://manubot.org "Manubot Homepage")

[Link by reference][manubot homepage]

[Manubot Homepage]: https://manubot.org

## Citations

Citation by DOI [@doi:10.7554/eLife.32822].

Citation by PubMed Central ID [@pmc:PMC6103790].

Citation by PubMed ID [@pubmed:30718888].

Citation by Wikidata ID [@wikidata:Q56458321].

<!-- Citation by ISBN [@isbn:9780262517638]. -->

<!-- Citation by URL [@{https://greenelab.github.io/meta-review/}]. -->

Citation by alias [@deep-review].

<!-- Multiple citations can be put inside the same set of brackets [@doi:10.7554/eLife.32822; @deep-review; @isbn:9780262517638]. -->
Manubot plugins provide easier, more convenient visualization of and navigation between citations [@doi:10.1371/journal.pcbi.1007128; @pubmed:30718888; @pmc:PMC6103790; @deep-review].

Citation tags (i.e. aliases) can be defined in their own paragraphs using Markdown's reference link syntax:

[@deep-review]: doi:10.1098/rsif.2017.0387

## Referencing figures, tables, equations

Figure @fig:square-image

Figure @fig:wide-image

Figure @fig:tall-image

Figure @fig:vector-image

Table @tbl:bowling-scores

Equation @eq:regular-equation

Equation @eq:long-equation

## Quotes and code

> Quoted text

> Quoted block of text
>
> Two roads diverged in a wood, and I—  
> I took the one less traveled by,  
> And that has made all the difference.

Code `in the middle` of normal text, aka `inline code`.

Code block with Python syntax highlighting:

```python
from manubot.cite.doi import expand_short_doi

def test_expand_short_doi():
    doi = expand_short_doi("10/c3bp")
    # a string too long to fit within page:
    assert doi == "10.25313/2524-2695-2018-3-vliyanie-enhansera-copia-i-insulyatora-gypsy-na-sintez-ernk-modifikatsii-hromatina-i-svyazyvanie-insulyatornyh-belkov-vtransfetsirovannyh-geneticheskih-konstruktsiyah"
```

Code block with no syntax highlighting:

```
Exporting HTML manuscript
Exporting DOCX manuscript
Exporting PDF manuscript
```

## Figures

![
**A square image at actual size and with a bottom caption.**
Loaded from the latest version of image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/square.png "Square image"){#fig:square-image}

![
**An image too wide to fit within page at full size.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/wide.png "Wide image"){#fig:wide-image}

![
**A tall image with a specified height.**
Loaded from a specific (hashed) version of the image on GitHub.
](https://github.com/manubot/resources/raw/15493970f8882fce22bef829619d3fb37a613ba5/test/tall.png "Tall image"){#fig:tall-image height=3in}

![
**A vector `.svg` image loaded from GitHub.**
The parameter `sanitize=true` is necessary to properly load SVGs hosted via GitHub URLs.
White background specified to serve as a backdrop for transparent sections of the image.
](https://raw.githubusercontent.com/manubot/resources/main/test/vector.svg?sanitize=true "Vector image"){#fig:vector-image height=2.5in .white}

## Tables

| *Bowling Scores* | Jane          | John          | Alice         | Bob           |
|:-----------------|:-------------:|:-------------:|:-------------:|:-------------:|
| Game 1 | 150 | 187 | 210 | 105 |
| Game 2 |  98 | 202 | 197 | 102 |
| Game 3 | 123 | 180 | 238 | 134 |

Table: A table with a top caption and specified relative column widths.
{#tbl:bowling-scores}

|         | Digits 1-33                        | Digits 34-66                      | Digits 67-99                      | Ref.                                                        |
|:--------|:-----------------------------------|:----------------------------------|:----------------------------------|:------------------------------------------------------------|
| pi      | 3.14159265358979323846264338327950 | 288419716939937510582097494459230 | 781640628620899862803482534211706 | [`piday.org`](https://www.piday.org/million/)               |
| e       | 2.71828182845904523536028747135266 | 249775724709369995957496696762772 | 407663035354759457138217852516642 | [`nasa.gov`](https://apod.nasa.gov/htmltest/gifcity/e.2mil) |

Table: A table too wide to fit within page.
{#tbl:constant-digits}

|          | **Colors** <!-- $colspan="2" --> |                      |
|:--------:|:--------------------------------:|:--------------------:|
| **Size** | **Text Color**                   | **Background Color** |
| big      | blue                             | orange               |
| small    | black                            | white                |

Table: A table with merged cells using the `attributes` plugin.
{#tbl: merged-cells}

## Equations

A LaTeX equation:

$$\int_0^\infty e^{-x^2} dx=\frac{\sqrt{\pi}}{2}$$ {#eq:regular-equation}

An equation too long to fit within page:

$$x = a + b + c + d + e + f + g + h + i + j + k + l + m + n + o + p + q + r + s + t + u + v + w + x + y + z + 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9$$ {#eq:long-equation}

## Special

<i class="fas fa-exclamation-triangle"></i> [WARNING]{.semibold} _The following features are only supported and intended for `.html` and `.pdf` exports._
_Journals are not likely to support them, and they may not display correctly when converted to other formats such as `.docx`._

[Link styled as a button](https://manubot.org "Manubot Homepage"){.button}

Adding arbitrary HTML attributes to an element using Pandoc's attribute syntax:

::: {#some_id_1 .some_class style="background: #ad1457; color: white; margin-left: 40px;" title="a paragraph of text" data-color="white" disabled="true"}
Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
:::

Adding arbitrary HTML attributes to an element with the Manubot `attributes` plugin (more flexible than Pandoc's method in terms of which elements you can add attributes to):

Manubot Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot Manubot.
Manubot Manubot Manubot.
Manubot Manubot.
Manubot.
<!-- $id="element_id" class="some_class" $style="color: #ad1457; margin-left: 40px;" $disabled="true" $title="a paragraph of text" $data-color="red" -->

Available background colors for text, images, code, banners, etc:  

`white`{.white}
`lightgrey`{.lightgrey}
`grey`{.grey}
`darkgrey`{.darkgrey}
`black`{.black}
`lightred`{.lightred}
`lightyellow`{.lightyellow}
`lightgreen`{.lightgreen}
`lightblue`{.lightblue}
`lightpurple`{.lightpurple}
`red`{.red}
`orange`{.orange}
`yellow`{.yellow}
`green`{.green}
`blue`{.blue}
`purple`{.purple}

Using the [Font Awesome](https://fontawesome.com/) icon set:

<!-- include the Font Awesome library, per: https://fontawesome.com/start -->
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css">

<i class="fas fa-check"></i> <i class="fas fa-question"></i> <i class="fas fa-star"></i> <i class="fas fa-bell"></i> <i class="fas fa-times-circle"></i> <i class="fas fa-ellipsis-h"></i>

[
<i class="fas fa-scroll fa-lg"></i> **Light Grey Banner**<br>
useful for *general information* - [manubot.org](https://manubot.org/)
]{.banner .lightgrey}

[
<i class="fas fa-info-circle fa-lg"></i> **Blue Banner**<br>
useful for *important information* - [manubot.org](https://manubot.org/)
]{.banner .lightblue}

[
<i class="fas fa-ban fa-lg"></i> **Light Red Banner**<br>
useful for *warnings* - [manubot.org](https://manubot.org/)
]{.banner .lightred}


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
