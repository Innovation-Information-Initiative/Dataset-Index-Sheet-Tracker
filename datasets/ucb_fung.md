---
bigquery: https://console.cloud.google.com/bigquery?p=erudite-marker-539&d=JEMS16&page=dataset
citation: Balsmeier, B., Assaf, M., Chesebro, T., Fierro, G., Johnson, K., Johnson,
  S., Li, G., W.S. Lueck, O’Reagan, D., Yeh, W., Zang, G., Fleming, L. “Machine learning
  and natural language processing applied to the patent corpus.” Forthcoming at Journal
  of Economics and Management Strategy.
contributors: Balsmeier, B., Assaf, M., Chesebro, T., Fierro, G., Johnson, K., Johnson,
  S., Li, G., W.S. Lueck, O’Reagan, D., Yeh, W., Zang, G., Fleming, L.
cost: None
description: 'Drawing upon recent advances in machine learning and natural language
  processing, we introduce new tools that automatically ingest, parse, disambiguate
  and build an updated database using United States patent data. The tools identify
  unique inventor, assignee, and location entities mentioned on each granted US patent
  from 1976 to 2016. We describe data flow, algorithms, user interfaces, descriptive
  statistics, a novelty measure based on the first appearance of a word in the patent
  corpus, and an automated co-inventor network mapping tool. '
documentation: https://funginstitute.berkeley.edu/wp-content/uploads/2016/11/Machine_learning_and_natural_language_processing_on_the_patent_corpus.pdf
last_edit: 04/08/2022, 04:34:28
location: https://console.cloud.google.com/marketplace/product/google_patents_public_datasets/ucb-fung-patent
related_publications: ' https://doi.org/10.1111/jems.12259'
schema_fields:
- InventorID
- PrimaryExaminer
- GovernmentInterests
- AssistExaminer
- FutureUse
- Company
- Type
- PatentNo
- InventorFullname
- int64_field_0
- ApplNo
- Word
- State
- Title
- LawFirm
- assignee_disambiguated
- sequence
- ApplDate
- IssueDate
- PatentNo_citing
- FirstMiddleName
- Geography
- LastName
- CPC_Layer_1
- Sequence
- PatentNoOrNPL_cited
- CPC_Full
- id
- FamilyID
- CountryCodeOrNPL_cited
- City
- Abstract
- CPC_Layer_2
- string_field_1
- pdpass
- CurrentUse
- string_field_2
- FullName
- Country
- Self_Citation_Flag
shortname: ucb_fung
tags:
- patents
- machine learning
- disambiguation
- metrics
- novelty
terms_of_use: Creative Commons Attribution 4.0 International license
timeframe: 1976-2016
title: UCB Fung Institute Patent Data
uuid: e3d20ecd-fa26-4572-9c1f-2b26aa47e15d
---