---
title: "From raw data to a website for humans, with every AI step in the open"
subtitle: "DCC 2027 workshop submission - RDM Network, University of Basel"
title-block-banner: true
date: today
author:
  - name: Lars Schöbitz
    orcid: 0000-0003-2196-5015
    email: lars.schoebitz@ethz.ch
    affiliations:
      - name: ETH Zürich
        address: Clausiusstrasse 37
        city: Zürich
        postal-code: 8092
        url: https://ghe.ethz.ch/
    attributes:
      corresponding: true
format:
  html:
    toc: true
    toc-depth: 2
    number-sections: false
    embed-resources: true
    theme: cosmo
  docx:
    toc: false
    number-sections: false
---

## Submission metadata

- **Conference:** Data Curation Conference 2027, Research Data Management Network, University of Basel, 14 January 2027
- **Format:** Workshop session (50 min), hands-on and interactive
- **Presenter:** Lars Schöbitz
- **Discipline:** Global health engineering (water, sanitation and health)
- **Use case:** Survey and monitoring data from the water, sanitation and health sector, from the raw file to a published data package and website
- **Data curation aspect(s):** Presentation of data to humans, documentation, versioning, metadata, AI assisted curation with disclosure, sensitive data

## Abstract, version A (plain writing)

<!-- Max. 350 words including the title. The call asks for: discipline, use case, data curation aspect(s). Half-solved problems and open questions are welcome. -->

Title: From raw data to a website for humans, with every AI step in the open

At Global Health Engineering at ETH Zurich we have published research data with one workflow for five years and built our tools around it. We use it for our own data and, through openwashdata, for data from the wider water, sanitation and health sector. Raw data is cleaned with code, documented with a data dictionary and metadata, packaged as an R data package, archived with a DOI, and published as a website with a plain description and charts. All of it, including the cleaning and plot code, is on GitHub under an open licence. We publish for machines and for humans. I focus on the human side, because machines read data easily now and people still need to find, understand and trust it.

In this workshop I run the workflow live, from a messy raw dataset to a published data package. A coding agent does the mechanical steps and the room steers every step. Participants add to the documentation and review as we go, and leave with two free, open source tools, washr and pkgreview, for their own data.

I also bring the questions that keep me up at night, technical, organisational, societal and ethical:

- Oversight. Publishers now sell AI curated data publication for thousands of francs per dataset, with unclear author oversight and closed curation steps. In our workflow every AI step is visible.
- Disclosure. We record exactly how AI was used in everything we make. I show the record for this proposal, the slides and the workshop material, kept in one public repository from the start.
- Sensitive data. Our data comes from households in low income countries. What may enter a public repository, and when only aggregates can be published, is a half-solved problem for us.
- Rewards. With AI, a paper is written in a day once the data is curated and documented well. I think scientific credit should move to the data, and want to hear whether the room agrees.

## Abstract, version B (conventional)

Title: From raw data to a website for humans: a live workflow with every AI step disclosed

For five years, the Global Health Engineering group at ETH Zurich has practised a single data publishing workflow, supported by tools we built ourselves and applied to our own data and, through openwashdata, to data from the wider water, sanitation and health sector. Raw data is processed with documented code into an analysis ready dataset, described with a data dictionary and machine readable metadata, packaged as an R data package, archived with a DOI, and presented on a website with documentation and visualisations. Processing and plotting code are published with the data on GitHub under open licences. Data must be published for machines and humans alike. This contribution foregrounds the human side, since machines parse data with ease today whereas people must still discover, interpret and trust it.

The workshop is a live demonstration in which a messy raw dataset becomes a published, curated data package within the session, using washr (an R package for building and documenting data packages) and pkgreview (an automated review against a published standard). A coding agent performs the mechanical steps under the room's direction, participants contribute documentation and review as the work unfolds, and every intervention remains visible. They leave with free, open source tooling for their own data.

I also raise four unresolved questions from technical, organisational, societal and ethical perspectives. First, publishers now sell AI driven data curation at several thousand francs per dataset, with little transparency about author oversight or the curation process. Second, we record precisely how AI contributed to each output, and I will show that record for this proposal, the slides and the workshop material, kept in one public repository. Third, for sensitive data from households in low income countries, what may enter a public repository and when only aggregates should be released remains half-solved. Fourth, if AI can draft a paper in a day from well curated data, scientific credit should arguably shift towards the data. I invite the room to argue back.

## Session plan

<!-- Not part of the submission; for planning the 30 to 50 minutes. -->

| Time | Block | What happens |
|----|----|----|
| 0:00 to 0:05 | Why we publish for humans | The five year workflow in one picture, the three stages of data (raw, analysis ready, final), and what the room will see |
| 0:05 to 0:28 | Live run, part 1 | Raw dataset to a washr data package. The agent does the mechanical steps (folder structure, data dictionary, metadata, README). The room steers, and participants add documentation lines through a shared issue |
| 0:28 to 0:36 | Live run, part 2 | pkgreview checks the package, release, DOI, website. The disclosure trail (commit trailers, prompts archive) shown on the repository |
| 0:36 to 0:46 | Open questions | Publishers selling AI curation, disclosure, sensitive data, rewards moving to data. Short discussion per question |
| 0:46 to 0:50 | Take home | Where the repository lives, how to run washr on your own data, who to ask |
