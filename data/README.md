# Data for GESIS Workshops course "Going cross-lingual"

## Climate-realted news articles

`[To be described]`

## Coded party manifesto sentences

The tab-seperated file 'dupont+rachuj_2021_coded_manifesto_sentences.tsv' contains labeled manifesto sentences stemming from the [MARPOR](https://manifesto-project.wzb.eu/) project
which have been enriched with machine translations by Düpont and Rachuj ([2021](https://doi.org/10.1017/S0007123420000617))
and cleaned, harmonized, and analyzed by Licht ([2023](https://doi.org/10.1017/pan.2022.29)).

Sentences are labeled on two dimensions:

1. policy area/domain: 7 MARPOR categories
2. stance indicator ("left", "right", "none" + "uncoded") derived from granular 52+-category MARPOR codings


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

## European election candidate tweets

The tab-separated file 'teocharis_et_al_2016_labeled_tweets.tsv' records tweets posted by candidates running for the European Parliament elections in Spanish, Greek, German, and the U.K. in 2014.

Tweets are labeled on several dimensions:

- 'filter': categories to filter our spam tweets, "none" if non-spam tweet
- if 'filter' == "none"
	- 'communication': "broadcasting" or "engaging" communication? 
	- 'polite': "polite" or "impolite"
	- 'sentiment': "positive", "netural", "negative"
	- 'political': "political", "personal", "unclear"
	- if 'political' == "political"
		 - 'level' (multi-label): "eu", "national", and/or "subnational" or "unclear" or "none"
		 - 'issue' (multi-label): 14 categories (e.g., "campaign" or "economic")

The data stems from the paper Teocharis *et al.* ([2016](https://doi.org/10.1111/jcom.12259)).
The raw data is available through [Dropbox](https://www.dropbox.com/s/te40bb141rkoybe/tweet-codings.csv?dl=0)and was kindly shared by Pablo Barberá on request by Hauke Licht on January 9, 2021.
