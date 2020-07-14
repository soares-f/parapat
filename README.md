# ParaPat: The Multi-Million Sentences Parallel Corpus of Patents Abstracts
This repository contains the pointers to the ParaPat paper, a corpora of parallel sentences from patents extracted from Google Patents.
The paper has been published in LREC2020.


## Paper
The ParaPat paper can be found here: https://www.aclweb.org/anthology/2020.lrec-1.465/  

For citation, please use the following BibTeX
<pre>
@inproceedings{soares-etal-2020-parapat,
    title = "{P}ara{P}at: The Multi-Million Sentences Parallel Corpus of Patents Abstracts",
    author = "Soares, Felipe  and
      Stevenson, Mark  and
      Bartolome, Diego  and
      Zaretskaya, Anna",
    booktitle = "Proceedings of The 12th Language Resources and Evaluation Conference",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://www.aclweb.org/anthology/2020.lrec-1.465",
    pages = "3769--3774",
    language = "English",
    ISBN = "979-10-95546-34-4",
}

</pre>


## Digital Object Identifier (DOI) and access to files

https://doi.org/10.6084/m9.figshare.12627632

## Corpus Statistics:

### Parallel corpora aligned into sentence level

|Language Pair|# Sentences|# Unique Tokens|  
|--------|-----|------|
|EN/ZH|4.9M|155.8M|                                                
|EN/JA|6.1M|189.6M|                                              
|EN/FR|12.2M|455M|                                            
|EN/KO|2.3M|91.4M|                                           
|EN/DE|2.2M|81.7M|                                          
|EN/RU|4.3M|107.3M|                                               
|DE/FR|1.2M|38.8M|                                              
|FR/JA|0.3M|9.9M|                                             
|EN/ES|0.6M|24.6M|                                               

### Parallel corpora aligned into abstract level

|Language Pair|# Abstracts|
|--------|-----|
|FR/KO|120,607|
|EN/UK|89,227|
|RU/UK|85,963|
|CS/EN|78,978|
|EN/RO|48,789|
|EN/HU|42,629|
|ES/FR|32,553|
|EN/SK|23,410|
|EN/PT|23,122|
|BG/EN|16,177|
|FR/RU|10,889|

## MT Experiments Results

<center>
  
|Source Language|Target Language|BLEU Score|
|--------|-----|------|
|ES|EN|57.71|
|FR|EN|49.60|
|EN|RU|49.10|
|EN|FR|48.39|
|DE|EN|48.35|
|EN|DE|46.77|
|RU|EN|46.73|
|EN|ES|44.98|
|DE|FR|42.13|
|FR|DE|36.56|
|KO|EN|23.23|
|JA|EN|17.78|
|EN|JA|13.15|
|ZH|EN|13.01|
|EN|KO|11.93|
|EN|ZH|10.29|
|JA|FR|9.52|
|FR|JA|7.10|
  
</center>
