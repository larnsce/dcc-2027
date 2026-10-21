# Earlier abstract versions with review notes

Two versions drafted on 20 October 2026 from spoken-draft.md and initial-prompt.md in this folder. Version A is the plain writing version and carries Lars's review notes as TODOs, written on 20 October. Version B is the conventional version. The final abstract in submission/abstract-workshop.qmd combines the shape of A with the terminology of B and resolves the TODOs. Kept for the record.

## Version A (plain writing), with the review notes as TODOs

Title: From raw data to a website for humans, with every AI step in the open

At Global Health Engineering at ETH Zurich we have (TODO: worked on a data curation and publishing workflow and related tiools) published research data with one workflow for five years and built our tools around it. We use it for our own data and, through openwashdata, for data from the wider water, sanitation and health sector. TODO: AI has given use the opportunity to invest further into the tools, so that we are getting closer to a general toolset that could be used by others). Raw data is cleaned with code, documented with a data dictionary and metadata, packaged as an R data package, archived with a DOI, and published as a website with a plain description and charts. All of it, including the cleaning and plot code, is on GitHub under an open licence. We publish for machines and for humans. I focus on the human side, because machines read data easily now and people still need to find, understand and trust it.

In this workshop I run the workflow live, from a messy raw dataset to a published data package. A coding agent does the mechanical steps and the room steers every step (TODO: the room doesn't steer. I need to find another way for people to contribute, either through sending a message through element, whatsapp, a QR comment field from supabase, the technical detail doesn't need to be clear, but I want people to contribute somewhat to the package and integrate those proposed changes live). Participants add to the documentation and review as we go, and leave with two free, open source tools, washr and pkgreview, for their own data. (TODO: I only want to show washr, pkgreview can be mentioned but not shown).

I also bring the questions that keep me up at night, technical, organisational, societal and ethical:

- Oversight. Publishers now sell AI curated data publication for thousands of francs per dataset, with unclear author oversight and closed curation steps. In our workflow every AI step is visible. (TODO: Verify this info from my vault and a brief web search through the Frontiers data article)
- Disclosure. We record exactly how AI was used in everything we make. I show the record for this proposal, the slides and the workshop material, kept in one public repository from the start.
- Sensitive data. Our data comes from households in low income countries. What may enter a public repository, and when only aggregates can be published, is a half-solved problem for us.
- Rewards. With AI, a paper is written in a day once the data is curated and documented well. I think scientific credit should move to the data, and want to hear whether the room agrees.

## Version B (conventional)

Title: From raw data to a website for humans: a live workflow with every AI step disclosed

For five years, the Global Health Engineering group at ETH Zurich has practised a single data publishing workflow, supported by tools we built ourselves and applied to our own data and, through openwashdata, to data from the wider water, sanitation and health sector. Raw data is processed with documented code into an analysis ready dataset, described with a data dictionary and machine readable metadata, packaged as an R data package, archived with a DOI, and presented on a website with documentation and visualisations. Processing and plotting code are published with the data on GitHub under open licences. Data must be published for machines and humans alike. This contribution foregrounds the human side, since machines parse data with ease today whereas people must still discover, interpret and trust it.

The workshop is a live demonstration in which a messy raw dataset becomes a published, curated data package within the session, using washr (an R package for building and documenting data packages) and pkgreview (an automated review against a published standard). A coding agent performs the mechanical steps under the room's direction, participants contribute documentation and review as the work unfolds, and every intervention remains visible. They leave with free, open source tooling for their own data.

I also raise four unresolved questions from technical, organisational, societal and ethical perspectives. First, publishers now sell AI driven data curation at several thousand francs per dataset, with little transparency about author oversight or the curation process. Second, we record precisely how AI contributed to each output, and I will show that record for this proposal, the slides and the workshop material, kept in one public repository. Third, for sensitive data from households in low income countries, what may enter a public repository and when only aggregates should be released remains half-solved. Fourth, if AI can draft a paper in a day from well curated data, scientific credit should arguably shift towards the data. I invite the room to argue back.
