#### Poet mentions in PPA
- **mentions.csv** contains all the mentions of poets found in PPA, the structure is [book_id, page_id, poet_name, birth_year, gender, country_of_citizenship, wikidata_id]
- **visualizations.ipynb** produces some basic summary stats
- **simplified_countries.json** is used by **visualizations.ipynb** to produce "human readable" labels to country of origin (e.g., Republic of Genoa > Italy, Crown of Castile > Spain etc.)

 Mentions were extracted with [spaCy](https://spacy.io/) and linked using [GENRE](https://github.com/facebookresearch/GENRE).
