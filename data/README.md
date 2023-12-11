# Data for GESIS Workshops course "Going cross-lingual"

## Climate-realted news articles

`[To be described]`

## Immigration/integration issue mentions and position in party manifestos

The files 

- 'lehmann+zobel_2018_labeled_manifestos.tsv'
- 'lehmann+zobel_2018_pimpo_positions.tsv'
- 'lehmann+zobel_2018_pimpo_positions_translated.tsv'

are tab-seperated files recordings party manifesto quasi-sentences coded on two dimensions

1. whether they mention the issues of integration or immigration
2. if so, whether they express a supportive, neutral, or sceptical stance.

The original labeled data comes from the [PimPo](https://manifesto-project.wzb.eu/information/documents/pimpo) dataset contributed by the Pola Lehmann and Malisa Zobel ([2018](https://doi.org/10.1111/1475-6765.12266)).

**_Notes:_**

- 'lehmann+zobel_2018_pimpo_positions.tsv' is the subset of 'lehmann+zobel_2018_labeled_manifestos.tsv' where issue in ["integration", "immigration"]
- 'lehmann+zobel_2018_pimpo_positions_translated.tsv' contains the same data as 'lehmann+zobel_2018_pimpo_positions.tsv' and only adds English machine translations of quasi-sentences

## Manifesto sections about immigration/integration

The data in folder ruedin_and_morales_2019/ records data taken from the replication materials of of Ruedin and Morales ([2020](https://doi.org/10.1177/1354068817713122)) obtained from [OSF](https://osf.io/bj27x/).

- 'ruedin_and_morales_2019/parties.tsv': tab-separated file tabulating party abbreviations used in their data 
- 'ruedin_and_morales_2019/party_codes.tsv': tab-separated file mapping party abbreviations used in their data to [CHES](https://www.chesdata.eu/) party IDs
- 'ruedin_and_morales_2019/ruedin_and_morales_2019_manifest_sections.csv': comma-separated file with raw text of party manifesto sections about integration/immigration
- 'ruedin_and_morales_2019/ruedin_and_morales_2019_manifest_section_sentences.csv': comma-separated file with text of party manifesto sections about integration/immigration splitted into *natural* sentences
