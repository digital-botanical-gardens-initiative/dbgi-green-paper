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
date-meta: '2022-11-07'
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
  <meta name="dc.date" content="2022-11-07" />
  <meta name="citation_publication_date" content="2022-11-07" />
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
  <link rel="alternate" type="text/html" href="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/2511715121a53a10bc795095b505f4c291bef6df/" />
  <meta name="manubot_html_url_versioned" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/2511715121a53a10bc795095b505f4c291bef6df/" />
  <meta name="manubot_pdf_url_versioned" content="https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/2511715121a53a10bc795095b505f4c291bef6df/manuscript.pdf" />
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
([permalink](https://digital-botanical-gardens-initiative.github.io/dbgi-green-paper/v/2511715121a53a10bc795095b505f4c291bef6df/))
was automatically generated
from [digital-botanical-gardens-initiative/dbgi-green-paper@2511715](https://github.com/digital-botanical-gardens-initiative/dbgi-green-paper/tree/2511715121a53a10bc795095b505f4c291bef6df)
on November 7, 2022.
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
](images/dbgi-goals.pdf "Workflow"){#fig:dbgi-goals width="100%"}

The main goals of the DBGI are resumed in Figure @fig:dbgi-goals Some details are given hereafter:

1. Establish chemical extracts libraries of Swiss botanical gardens. These chemical libraries can be considered as complementary to herbarium samples. They are easily conserved over time and in a reasonable space. They represent the chemical diversity of a sample. They can be easily aliquoted. They can be screened for bioassays.

2. Digitize, through mass spectrometry, the chemodiversity of Swiss botanical gardens. Here high-resolution mass spectrometry is considered as a digital scanner allowing to capture the chemical fingerprint of the profiled sample. State-of-the-art computational metabolomics solutions are used to organize and annotate the acquired spectra with molecular data.

3. Gather chemical information and relevant samples metadata in a tailored knowledge graph. Chemical information acquired at the previous step (spectra and chemical structures) are connected to relevant samples metadata (taxonomy, phenology, geolocalisation, time of collection etc.). For this semantic web technologies (namely the RDF data model) are employed and a tailored knowledge graph is established.

4. Connect to existing ontologies (bio, chemo) and biodiversity digitization projects. Chemical and biological objects of the graph are connected to relevant pre-established ontologies (e.g. CHEBI, Plants Ontology) and data graphs (e.g. Wikidata). Connection with complementary biodiversity digitization efforts will be done (e.g BiCIKL https://bicikl-project.eu/, Dissco https://www.dissco.eu/ )

5. Establish web and programmatic interfaces for the query of the acquired knowledge. A web interface will allow a convenient access to the data acquired within the framework of the project. A dashboard will allow simple visualizations (e.g pie charts, barplots, treemap) to interpret the data. In addition a SPARQL endpoint and an application programming interface (API) will allow retrieval of data programmatically.

6. Illustrate the feasibility and advantages of an end-to-end Open Science project. The DBGI will strictly follow the Open Science guidelines by using open-source software and making available the acquired data and scripts under an open license agreement. In addition the DBGI results will be published at the moment they are acquired (previous to formal publication or even pre-prints) thus following the Open Notebook Science concepts. 

7. Establish robust and scalable workflows for the digitization of wild ecosystems biodiversity. The DBGI, albeit ambitious, is a pilot project. The future objective is to propose digitization workflows for the characterization of the wild ecosystems chemodiversity, on a global scale.

8. Provide "molecular arguments" for biodiversity conservation policies. The ultimate goal of DBGI is to use all the gathered metabolic information to support, extend or implement conservation efforts worldwide. We believe that by providing chemical maps of the landscape it will be possible to contribute to the prioritization of conservation and restoration targets . In other words, by establishing large scale chemical maps we expect to provide “molecular arguments” to biodiversity conservation endeavors (e.g. “This piece of land has a high content of antibacterial scaffolds.” or “This place might be poor in species diversity but rich in a rare chemodiversity”.)

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

Citation by ISBN [@isbn:9780262517638].

Citation by URL [@{https://greenelab.github.io/meta-review/}].

Citation by alias [@deep-review].

Multiple citations can be put inside the same set of brackets [@doi:10.7554/eLife.32822; @deep-review; @isbn:9780262517638].
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
