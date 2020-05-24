# Summarizing and Exploring Tabular Data in  Conversational Search


This repository contains resources developed within the following paper:

> S. Zhang*, Z. Dai*, K. Balog and J. Callan. Summarizing and Exploring Tabular Data in  Conversational Search. In: *Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval*, Jul 2020. (* Equal contribution)

# Benchmark

  - `data/01-query_tables.csv`: 200 querie-table pairs.
  - `data/02-raw_tables.json`: 200 raw tables parsed from Wikipedia. For each table, pageTitle, caption, headings, and rows are provided.
  - `data/03-table_type.csv`: manually identified table type. There are 64 Sport, 33 Place, 27 Music, 16 Film, 12 Culture, 11 Traffic, 8 Product, and 30Other tables (including Politics, TV series, Award, and Company).
  - `data/04-candidate_summaries.csv`: candidate summaries collected by a crowdsourcing task on Amazon Mechanical Turk.
  - `data/05-sentence_annotations.csv`: sentence-level relevance assessments by employing three judges. Each summary was split into sentences.
  - `data/06xxx.csv`: summary-level relevance assessments by employing seven judges.
  
## Citation
```
@inproceedings{Zhang:2018:AHT,
    author = {Zhang, Shuo and Zhuyun, Dai and Balog, Krisztian and Callan, Jamie},
    title = {Summarizing and Exploring Tabular Data in  Conversational Search},
    booktitle = {Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval},
    year = {2020},
    pages = {},
}
```

## Contact
If you have any questions, please contact Shuo Zhang at imsure318@gmail.com or Zhuyun Dai at zhuyund@cs.cmu.edu.
