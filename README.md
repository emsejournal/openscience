# EMSE Open Science Initiative


Openness in science is key to fostering progress via transparency, reproducibility, and replicability. Especially open data and open source are two fundamental pillars in open science as both build the core for excellence in evidence-based research. The Empirical Software Engineering journal (EMSE) has therefore decided to explicitly foster open science and reproducible research by encouraging and supporting authors to share their (anonymised and curated) empirical data and source code in form of replication packages. The overall goals are:
* Increasing the transparency, reproducibility, and replicability of research endeavours. This supports the immediate credibility of authors' work, and it also provides a common basis for joint community efforts grounded on shared data.
* Building up an overall body of knowledge in the community leading to widely accepted and well-formed software engineering theories in the long run.

This document describes the principles, the process, and the infrastructure that support this initiative.

This information is also available in the editorial [The open science initiative of the Empirical Software
Engineering journal](https://link.springer.com/epdf/10.1007/s10664-019-09712-x) (Published May 2019, [doi:10.1007/s10664-018-9632-7](https://doi.org/10.1007/s10664-019-09712-x))

## Open Science Principles at EMSE

As for any initiative in a research community, the success of the Open Science Initiative, too, depends on the willingness and the possibilities of authors to disclose their data. Therefore, we strive to implement the Open Science Initiative at EMSE as a community effort with services that aim at encouraging and supporting authors of EMSE articles in opening up their research. The steering and motivating principle is that only openness in empirical research increases the transparency of research in a way such that the authors' empirical analyses can be reproduced, fully understood, and ideally replicated by others not involved in the research. To this end, we aim at promoting a data-sharing culture where authors publicly archive their data and related material required to understand and reproduce the claims and analyses presented by them in their manuscripts. Our hope is to move our community as a whole forward to the point where open science becomes the norm.

All submissions to EMSE will undergo the same known review process regardless of whether authors decide to disclose their data or not. Yet, as the leading journal in empirical research methodologies and their application to software engineering, we strongly encourage all authors to make an effort in supporting this initiative by making data available upon submission (either privately or publicly) and especially upon acceptance (publicly). Authors who cannot disclose non-public data (e.g. industrial data sets that fall under non-disclosure agreements), are asked to please provide an explicit and short statement in their manuscript.

To make research data sets and research software accessible and citable, we encourage authors to:
* archive data on preserved archives such as [zenodo.org](https://zenodo.org/) and [figshare.com](https://figshare.com/) so that replication packages remain available in the very long term (on Zenodo, there is a [dedicated community for empirical software engineering](https://zenodo.org/communities/empirical-software-engineering/)).
* use an appriopriate license, eg the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/) for data and the MIT License for code.

Those *replication packages* disclosed by the authors will then undergo an additional, short, review by the open science board as described next. When archiving data as part of a replication package, we ask authors to attend to the [FAIR](https://www.force11.org/group/fairgroup/fairprinciples), i.e. data should be:
* Findable,
* Accessible,
* Interoperable, and
* Reusable.

Authors should therefore use archival repositories and avoid putting data and software on their own (institutional or private) websites or systems like Dropbox, version control systems (SVN, Git), or service like Academia.edu and ResearchGate. Personal websites are prone to changes and errors, and more than 30% of them will not work in a 4 year period. Moreover, nobody should have the ability to delete data once it is public. Finally, the package disclosed via an archival repository should link to the paper (DOI) upon final production of the manuscript.

## Open Science Board

* [Daniel Méndez](https://www.mendezfe.org) (Chair), Blekinge Institute of Technology, Sweden, and fortiss GmbH, Germany
* [René Just](https://homes.cs.washington.edu/~rjust/), University of Washington, USA
* [Daniel Graziotin](https://ineed.coffee), University of Stuttgart, Germany
* [Sira Vegas](http://www.grise.upm.es), Universidad Politécnica de Madrid, Spain
* [Neil Ernst](https://www.neilernst.net/), University of Victoria, Canada
* [Chakkrit Tantithamthavorn](http://chakkrit.com/), Monash University, Australia

If you are interested in joining the board and contributing to open science at EMSE, contact Daniel and Martin by email.

## Open Science Process

1. Once a manuscript gets "Minor revision" or "Acceptance", the decision email contains the following text:
    * "EMSE encourages open science and reproducible research. We are happy to invite your to submit your open data, open material, or open source code (in the folllowing referred to as "replication package") for an additional, short, review by the open science board. Provided you agree to participate, the board will then review the replication package and check its eligibility to publicly recognise your open science effort with an open science badge. The board will provide you with constructive feedback on content and documentation of the package. To submit your replication package, please send an email to mendezfe@acm.org. Should you have any questions, please do not hesitate to contact the open science chairs Daniel Mendez. Note that your decision to participate in the open science initiative will not affect the remaining reviewing and editorial process in any way."
1. The authors are given 2 weeks to submit their replication package after the final acceptance.
1. When the authors submit a replication package, the Open Science Chairs ask one member of the Open Science board to review the package.
    * The review is made according to transparent [review criteria](review-criteria.md)
    * The open science reviewer is given two weeks to accept or consolidate a list of questions to the authors
    * The open science review is blinded, the open science reviewer does not sign her review
1. If necessary, the open science reviewer asks for changes by sending an email to the authors
    * the authors are given another two weeks to make the changes.
1. The open science reviewer makes the final decision.
    * If the replication package is rated as insufficient, the manuscript is still accepted and the authors are given a list of constructive comments on how to improve their open science practices
	* If the replication package is considered to be of good or excellent quality, the authors can add in their final version. "Open Science Replication Package validated by the Open Science Board".

Throughout the whole communication process, the Open Science co-Chairs serve as mediator between the authors and the Open Science Board members in a, for now, single blind process.

The [Frequently Asked Questions](FAQ.md) provides additional information.

## EMSE papers with the Open Science Badge

When papers are awarded the "Open Science" badge, the following text is added as a separate title note, the badge note appears after the “Communicated by”-line
 
    “This paper has been awarded the Empirical Software Engineering (EMSE) open science badge.”

Springer maintains the ‘Open Science’ topical collection for papers that have been awarded the EMSE open science badge: <https://link.springer.com/journal/10664/topicalCollection/AC_deca3131734b61f9ddc593f577c02eb1/page/1>


## FAQ

**How should the replication packages be disclosed?**  
We encourage authors to archive their data as part of replication packages on preserved archives such as [zenodo.org](https://zenodo.org/) or [figshare.com](https://figshare.com/) so that the data will receive a [DOI](https://www.doi.org/) and become citable. Further, we recommend the authors to use the [CC0](https://creativecommons.org/publicdomain/zero/1.0/) dedication (or the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)) when publishing the data (automatic when using, for instance, zenodo.org or figshare.com).

Those archives allow updating published replication packages any time. We strongly recommend the authors to update the package information after the review process, once the manuscript is in production and receives a DOI, with a reference to the published manuscript so that the package is citable along the published article.

**In this EMSE open science process, what’s the difference between reproducibility and replicability?**  
There is no consensus across disciplines about the difference between reproducibility and replicability. Often, replicability is seen as the ability to repeat the same study under the very same conditions yielding same results.
Reproducibility is seen as the ability to independently reproduce the study yielding same or similar results with a given precision. In the EMSE open science process, we make no specific difference for now. The goal is to encourage open data and code so that researchers can reproduce the results (partially or completely), and/or perform further research using this data and code.

**What happens if the data violates one or more of the FAIR principles?**  
[FAIR](https://www.force11.org/group/fairgroup/fairprinciples) is an interesting initiative which we follow attentively. It’s good if authors get to know, and ideally follow those principles, but it’s not required.

**Is restricted access sharing allowed (e.g., data is stored online but the link is not public and provided only if the interested party explicitly asks for it or signs a formal agreement with the data owner)?**  
We certainly understand that in certain contexts, unconditional data disclosure to the public is not possible. Open science, however, means that data is publicly accessible by anyone which is why the open science badges cannot be granted when data is shared in a restricted manner.

**When it comes to data about the humans, do we want to encourage or adhere to some kind of privacy regulations such as GDPR?**  
Privacy is a very important concern taken seriously by the open science board. When it is required for the data, proper consent and anonymisation of data is mandatory, in compliance with existing ethical codes of conduct and regulations such as [GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation). Note that besides regional/local regulations and policies, also considering potential institutional entities such as an [IRB](https://en.wikipedia.org/wiki/Institutional_review_board) and necessary approvals of a study by such entities, sharing data about humans (e.g. interview or survey data) must always be based on the explicit consent given by the participants. That is, anonymizing the resulting data sets is not enough to meet our ethical standards. Further note that such consents may also be withdrawn by participants along a study (e.g., after presenting the results). While the open science board is advised to check for proper anomyzation when deemed necessary, it remains the sole responsibility of the authors to put careful considerations into privacy-related and ethical concerns, to obtain the necessary approvals and consents prior to submission of their data sets, and to ensure compliance of their actions with existing regulations.


**What happens if data or access to it are modified by the authors after the approval of the Open Science chairs?**
We count on the  authors’ ethics to avoid this inappropriate behaviour. Note that once data has been released on an archival website (e.g. Zenodo), later modifications are not possible anymore. This is also one of the reasons why we refrain from disclosing data sets only on institutional websites or personal webpages.

**What does replication mean for qualitative studies, say ethnography research or action research?**   
Complete replication of qualitative human studies is challenging, as human practices are rarely purely rational and reproducible. In our understanding, however, data sharing can at least support comprehending the analysis results yielded by the researchers and the conclusions they have drawn based on their data. We consider, therefore, a qualitative study to be (sufficiently) reproducible when the shared data allows other researchers to understand the claims and analyses presented by the authors. For interview research, for example, the shared data should include the instrumentation, transcripts (potentially anonymised), field notes, and codebooks so that others not involved in the study fully understand how the authors inferred their conclusions.

**What does replication mean for systematic reviews?**  
Similarly as for qualitative studies, secondary studies are difficult to fully reproduce. There exist multiple reasons for this, such as the different functionalities of different search engines yielding different results when repeatedly used in an independent manner. We consider a secondary study to be sufficiently reproducible when the reporting in the manuscript and the shared data and scripts allow to understand the claims and analyses presented by the authors.

**Why is the open science review process single blind?**  
It is for now single blind in order to be the least disruptive and to maximise acceptance (both from authors and from reviewers). We will consider alternatives in the near future.

**Will the absence of badges on research papers, as a result of confidential research data/artefacts, give the impression of a lower class science?**
No, the badge signals open data and open science. The absence of badge states does not mean that this is lower-class science, it only means that the authors cannot participate to the process or that the data was not open enough. In the presence of confidential research data or artefacts, authors will be encouraged to state in their paper the reasons for confidentiality in order to prevent misleading impressions.

**Will the absence of badges discourage research done on industrial proprietary datasets, that is potentially very valuable?**  
The journal does encourage and support high-quality research based on proprietary datasets which provides novel and unique insights.

**Are there multiple badges of different flavours? What is the connection to the [ACM badging](https://www.acm.org/publications/policies/artifact-review-badging) (used by [ROSE](https://2018.fseconference.org/track/rosefest-2018))?**  
First, there will be a single badge "Open science" in order to keep things simple. Then, multiple badges (up to the 5 levels of ACM) may be introduced. The badges are also being discussed with the publisher (Springer).

**Do artifacts need to be executable? What about models or diagrams?** 
Many areas of software engineering do not generate executable artifacts. Non-code artifacts such as UML diagrams/models, requirements text, design documents, etc. are all valid artifacts. If the artifact addresses the topic of the paper and supports replication, that's fine. See here for a lengthier, but not complete, [list of artifacts](https://github.com/researchart/all/blob/master/ListOfArtifacts.md). Finally, we prefer if such artifacts are machine-readable and open, e.g., using an open format such as JSON or XMI, as opposed to Visio, PNG, or PDF.

## See also

* [How to make a good open-science repository? (Martin Monperrus)](https://www.monperrus.net/martin/how-to-open-science-software-research)
* [Open Science in Software Engineering (Daniel Mendez, Daniel Graziotin, Stefan Wagner, Heidi Seibold)](https://arxiv.org/abs/1904.06499)
* [Reproducibility News Feed](https://vida-nyu.github.io/reproducibility-news/feed.rss)
* [Awesome open-science software](https://github.com/INRIA/awesome-open-science-software)

