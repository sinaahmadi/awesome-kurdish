# Awesome Kurdish

(last updated on 01/07/2022)

**A curated list of awesome resources, tools and scientific papers for Kurdish language technology**

Although I do my best to keep this page as comprehensive as possible by including all projects, the list may not include all the fantastic small and big projects regarding Kurdish language processing. Please be kind and notify me by reaching out by email or through our community on [Gitter](https://gitter.im/KurdishNLP/community).

Are you interested in contributing to Kurdish language processing? Check out [this post](https://sinaahmadi.github.io/klpt/about/contributing/) to see how you can do so.

## Development 

### Resources

#### Corpora

- [Open Super-large Crawled ALMAnaCH coRpus (OSCAR)](https://oscar-corpus.com/) (Sorani and Kurmanji)
- [Pewan](https://sinaahmadi.github.io/resources/pewan.html) (Sorani and Kurmanji)
- [Kurdish folkloric lyrics corpus](https://github.com/KurdishBLARK/KurdishLyricsCorpus) (Sorani)
- [AsoSoft corpus](https://github.com/AsoSoft/AsoSoft-Text-Corpus) (Sorani)
- [Kurdish Textbooks Corpus](https://github.com/KurdishBLARK/KTC) (Sorani)
- [Zaza-Gorani corpus](https://github.com/sinaahmadi/ZazaGoraniCorpus) (Zazaki and Gorani)
- [Kurdish resources on Clarin](https://vlo.clarin.eu/search;jsessionid=61B467FE3D0D9F9787A01F0BC8E0EEAA?1&fq=languageCode:code:kmr&fq=languageCode:code:ckb&fq=languageCode:code:sdh&fq=languageCode:code:kur&fqType=languageCode:or)
- [University of Bamberg's corpora](https://multicast.aspra.uni-bamberg.de/resources/#kurdish) [Kurmanji & Laki]

#### Parallel corpora

- [Ataman's Bianet corpus](http://opus.nlpl.eu/Bianet.php) containing Turkish-English-Kurmanji aligned texts
- [Ahmadi et al's corpus](https://github.com/KurdishBLARK/InterdialectCorpus) containing English-Kurmanji-Sorani aligned texts
- [Tanzil](http://opus.nlpl.eu/Tanzil.php): one Qoran translation alignable with many other translations in other languages, including 11 in English (see [this project](https://github.com/sinaahmadi/KurdishMT))
- Bible translations in [Kurmanji-Latin](http://ibtrussia.org/en/projects?id=KKD) and [Kurmanji-Cyrillic](http://ibtrussia.org/en/media?id=KKD/cyrl&panel=text)
- [TED Talks subtitles](https://production-blue.amara.org/en/)
- [HLP Colloquial Corpus #1](https://md.taus.net/library/corpus/colloquial-corpus-1-human-language-project-data) (Sorani and Kurmanji (Latin and Arabic)) (*not free*)
- A [parallel corpus](https://github.com/mihemmed/Kurdish-Machine-Translation-Project-KMTP-) of Sorani-English text
- [FLORES-101 Evaluation Benchmark for Low-Resource and Multilingual Machine Translation](https://github.com/facebookresearch/flores) (Sorani)
- [AsoSoft Speech Corpus for Central-Kurdish Text-To-Speech](https://github.com/AsoSoft/AsoSoft-TTS-Speech-Corpus-for-Central-Kurdish) (Sorani)

#### Dictionaries, terminologies and ontologies
Check out [a comprehensive list of Kurdish dictionaries](https://sinaahmadi.github.io/posts/list-of-kurdish-dictionaries.html) and beware of copyright issues in the following projects:

- [Kurdish lexicographical resources in Ontolex-Lemon](https://github.com/sinaahmadi/KurdishLexicography) (Sorani, Kurmanji, Gorani and Southern Kurdish)
- Check [Dolan Hêriş](https://github.com/dolanskurd?tab=repositories)'s repositories for a list of Kurdish dictionaries and tools to extract words
- [KurdNet-the Kurdish wordNet](https://sinaahmadi.github.io/resources/kurdnet.html) (Sorani)
- [Kurdish annotated lexicon](https://github.com/sinaahmadi/KurdishHunspell/blob/main/ckb/ckb-Arab.dic) (Sorani)
- [Freedict](https://freedict.org/downloads/) word lists (Sorani and Kurmanji)
- [Translation Initiative for COVID-19](https://tico-19.github.io/terminologies.html) including Sorani and Kurmanji
- [MyMemory dictionaries](https://mymemory.translated.net/) with an open-access API (Sorani)

#### Datasets

- [Dataset of Kurdish poems with meter and form tags](https://github.com/AsoSoft/Vejinbooks-Poem-Dataset)
- [A Twitter dataset](https://github.com/ftkurt/kurdish-twitter-data) (Sorani and Kurmanji)
- [Datasets for text to Kurdish Sign Language](https://github.com/KurdishBLARK/KurdishSignLanguage) (Sorani)
- [A dataset for speech recognition](https://github.com/KurdishBLARK/BD-4SK-ASR) (Sorani)
- [Universal dependency](https://github.com/UniversalDependencies/UD_Kurmanji-MG) (Kurmanji)
- [Web Inventory of Transcribed and Translated Talks (WIT3)](https://wit3.fbk.eu/) (Sorani)
- [Sorani](https://github.com/unimorph/ckb) and [Kurmanji](https://github.com/unimorph/kmr) morphological datasets in UniMorph
- [FakeKurdNews](https://github.com/rania-azad/FakeKurdNews---Fake-Kurdish-News-Dataset), an annotated dataset for Sorani Kurdish fake news detection
- [profanity language](https://github.com/MohammedSardar/Bive) (Sorani)

### Benchmarks
- Morphological analysis:
    - [KurdishHunspell evaluation datasets](https://github.com/sinaahmadi/KurdishHunspell) (Sorani)
- Tokenization: 
    - [KurdishTokenization](https://github.com/sinaahmadi/KurdishTokenization) (Sorani, Kurmanji)
    - [A sentence-segmented dataset](https://github.com/KurdishBLARK/KTC-Segmented) (Sorani)
- Transliteration
    - [Wergor transliteration datasets](https://github.com/sinaahmadi/wergor)
    - [Evaluation datasets for Kurdish Grapheme-to-Phoneme Conversion systems](https://github.com/AsoSoft/Kurdish-G2P-dataset) (Sorani)
- Spelling error correction
    - [Central-Kurdish-Spelling-dataset](https://github.com/AsoSoft/Central-Kurdish-Spelling-dataset)
    

#### Other resources

##### Word Embeddings:

- [fastText word vectors](https://fasttext.cc/docs/en/crawl-vectors.html) (Sorani and Kurmanji)
- [Polyglot's word embeddings](https://polyglot.readthedocs.io/en/latest/Embeddings.html)


### Tools

#### Fundamental processing

- [Language identifier](https://github.com/DanielJDufour/language-detector) (Sorani and Kurmanji)
- [Wergor for transliteration](https://github.com/sinaahmadi/wergor) (Sorani and Kurmanji)
- [Kurdish Tokenization](https://github.com/sinaahmadi/KurdishTokenization)
- [Jedar stemmer](https://github.com/klpp/codes/tree/master/stemming)
- Apertium project for [Kurmanji](https://github.com/apertium/apertium-kmr) and [Sorani](https://github.com/apertium/apertium-ckb) morphological analysis
- [Kurdish Hunspell](https://github.com/sinaahmadi/KurdishHunspell) for Sorani morphological analysig, spell checking, stemming and lemmatization
- [A finite-state morphological analyzer for Central Kurdish](https://github.com/CKMorph) (Sorani)
- [Part-of-speech tagger](https://github.com/sinaahmadi/KurdishPOSTagger) (Sorani)
- [Alexina Framework](https://gforge.inria.fr/projects/alexina/): morphological analysis and POS-tagger for Sorani (`soralex`) and Kurmanji (`kurlex`)
- [Kurdspell](https://github.com/Kurdspell/Kurdspell) for Sorani spell checking
- [Apertium rule-based Sorani spell-checker](https://github.com/rezKamal/ckb-spellchecker)
- [Gende Stemmer](https://github.com/mhmd-azeez/GendeStemmer) (Sorani)
- [Conversion of numbers into words](https://www.kurd.cc/numbers-to-kurdish-words) (Sorani and Kurmanji)
- [Conversion of words into IPA](https://www.kurd.cc/kurdish-text-to-ipa-phonetics) (Kurmanji)

#### Machine translation
- [Apertium](https://github.com/apertium) ([Sorani](https://github.com/apertium/apertium-ckb-eng) and [Kurmanji](https://github.com/apertium/apertium-kmr-eng))
- [Kurdish MT](https://github.com/sinaahmadi/KurdishMT) (Sorani)

#### Named-entity recognition
- [Autoregressive Entity Retrieval](https://github.com/facebookresearch/GENRE) (Kurmanji)

#### Libraries
- [Kurdish Language Processing Toolkit](https://github.com/sinaahmadi/klpt): a natural language processing toolkit in Python
- [Kurdînûs](https://github.com/aso-mehmudi/kurdinus): pure JavaScript tools for transliteration, text conversion and normalization
- [Kurdish Language Library](https://github.com/dolanskurd/kurdish): converting characters and digits in Persian, English and Arabic to Kurdish and vice versa
- [AsoSoft's Library for Kurdish](https://github.com/AsoSoft/AsoSoft-Library): normalizer, numeral converter, grapheme-to-phoneme convertor in C# 


### Other
In addition to these, you can find further information in other repositories and pages as follows:

- [Developers Tree](https://devs.krd/)
- [Kurdish resources](https://github.com/DevelopersTree/KurdishResources)


## Research

These references are provided based on the data collected in the paper entitled [KLPT – Kurdish Language Processing Toolkit](https://sinaahmadi.github.io/docs/articles/ahmadi2020klpt.pdf). Note that references are provided in the [`bibliography`](https://github.com/sinaahmadi/awesome-kurdish/blob/main/bibliography.bib) file.


|               Reference              	| Year 	| Field                                 	| dialects                 	|
|:------------------------------------:	|------	|---------------------------------------	|--------------------------	|
|       `esmaili2013sorani`       	| 2013 	| Dialectology                          	| Sorani, Kurmanji         	|
|      `hassani2016automatic`     	| 2016 	| Dialectology                          	| Sorani, Kurmanji         	|
|    `malmasi2016subdialectal`    	| 2016 	| Dialectology                          	| Sorani                   	|
|         `al2017kurdish`         	| 2017 	| Dialectology                          	| Sorani, Kurmanji, Gorani 	|
|        `amani:hal-03262435`       | 2021  | Dialectology                              | Kurdish, Zazaki & Gorani  |
|     `mohammed2012automatic`     	| 2012 	| Information retrieval and Text mining 	| Sorani                   	|
|     `esmaili2012challenges`     	| 2012 	| Information retrieval and Text mining 	| Sorani                   	|
|        `littell2016named`       	| 2016 	| Information retrieval and Text mining 	| Sorani                   	|
|       `hassani2017method`       	| 2017 	| Information retrieval and Text mining 	| Sorani, Kurmanji         	|
| `esmaAl-Talabaniili2014towards` 	| 2014 	| Information retrieval and Text mining 	| Sorani, Kurmanji         	|
|         `jaf2016simple`         	| 2016 	| Information retrieval and Text mining 	| Sorani                   	|
|        `rashid2017robust`       	| 2017 	| Information retrieval and Text mining 	| Sorani                   	|
|      `rashid2017automatic`      	| 2017 	| Information retrieval and Text mining 	| Sorani                   	|
|       `saeed2018improving`      	| 2018 	| Information retrieval and Text mining 	| Sorani                   	|
|       `saeed2018improving`      	| 2018 	| Information retrieval and Text mining 	| Sorani                   	|
|       `mustafa2018kurdish`      	| 2018 	| Information retrieval and Text mining 	| Sorani                   	|
|      `saeed2018evaluation`      	| 2018 	| Information retrieval and Text mining 	| Sorani                   	|
|        `ahmadi2019wergor`       	| 2019 	| Information retrieval and Text mining 	| Sorani                   	|
|        `mahmudi2021automated`     | 2021  | Information retrieval and Text mining     | Sorani                    |
|        `abdulrahman2022lmspell`   | 2022  | Information retrieval and Text mining     | Sorani                    |
|      `esmaili2013building`      	| 2013 	| Lexical resources                     	| Sorani                   	|
|      `aliabadi2014towards`      	| 2014 	| Lexical resources                     	| Sorani                   	|
|        `aliabadi2014semi`       	| 2014 	| Lexical resources                     	| Sorani                   	|
|        `ataman2018bianet`       	| 2018 	| Lexical resources                     	| Kurmanji                 	|
|       `ahmadi2019towards`       	| 2019 	| Lexical resources                     	| Sorani, Kurmanji, Gorani 	|
|   `abdulrahman2019developing`   	| 2019 	| Lexical resources                     	| Sorani                   	|
|      `abdulrahman2020using`     	| 2020 	| Lexical resources                     	| Sorani                   	|
|        `veisi2020toward`        	| 2020 	| Lexical resources                     	| Sorani                   	|
|        `ahmadi2020corpus`       	| 2020 	| Lexical resources                     	| Sorani                   	|
|        `ahmadi-2020-building`    	| 2020 	| Lexical resources                     	| Zaza, Gorani             	|
|        `veisi2021jira`	    	| 2021 	| Lexical resources                     	| Sorani	            	|
|        `azin2021sk`               | 2021  | Lexical resources                         | Southern Kurdish          |
|       `hassani2017kurdish`      	| 2017 	| Machine Translation                   	| Sorani, Kurmanji         	|
|        `kaka2018english`        	| 2018 	| Machine Translation                   	| Sorani                   	|
|        `ahmadi2020machine`        | 2020 	| Machine Translation                   	| Sorani                    |
|        `goyal2021flores`          | 2021  | Machine Translation                       | 101 languages incl. Sorani|
|        `amini2021central`         | 2021  | Machine Translation                       | Sorani                    |
|        `ahmadi2022leveraging`     | 2022  | Machine Translation                       | Sorani                    |
|        `baban1995programmable`    | 1995  | Morphological and syntactic analysis      | Sorani                    |
|     `walther2010developing`     	| 2010 	| Morphological and syntactic analysis  	| Sorani                   	|
|        `walther2010fast`        	| 2010 	| Morphological and syntactic analysis  	| Kurmanji                 	|
|      `salavati2013stemming`     	| 2013 	| Morphological and syntactic analysis  	| Sorani                   	|
|         `jaf2014stemmer`        	| 2014 	| Morphological and syntactic analysis  	| Sorani                   	|
|         `jaf2016chapter`        	| 2016 	| Morphological and syntactic analysis  	| Sorani                   	|
|     `gokirmak2017dependency`    	| 2017 	| Morphological and syntactic analysis  	| Kurmanji                 	|
|      `salavati2018building`     	| 2018 	| Morphological and syntactic analysis  	| Sorani                   	|
|       `mustafa2018kurdish`      	| 2018 	| Morphological and syntactic analysis  	| Sorani                   	|
|       `ahmadi2020towards`       	| 2020 	| Morphological and syntactic analysis  	| Sorani                   	|
|       `ahmadi-2020-tokenization` 	| 2020 	| Morphological and syntactic analysis  	| Sorani, Kurmanji         	|
|       `ahmadi2021modelling`       | 2021  | Morphological and syntactic analysis      | Sorani                    |
|       `ahmadi2020Hunspell`        | 2021  | Morphological and syntactic analysis      | Sorani                    |
|       `naserzade2021ckmorph`      | 2021  | Morphological and syntactic analysis      | Sorani                    |
|     `mohammed2012uniqueness`    	| 2012 	| Optical character recognition         	| Sorani                   	|
|    `mohammed2013handwritten`    	| 2013 	| Optical character recognition         	| Sorani                   	|
|       `shaltookisentiment`      	| 2016 	| Optical character recognition         	| Sorani                   	|
|      `zarro2017recognition`     	| 2017 	| Optical character recognition         	| Sorani                   	|
|       `yaseen2018kurdish`       	| 2018 	| Optical character recognition         	| Sorani                   	|
|       `dinler2018kurdish`       	| 2018 	| Optical character recognition         	| Sorani                   	|
|        `app11209752`              | 2021  | Optical character recognition             | Sorani                    |
|        `kaka2017building`       	| 2017 	| Other                                 	| Sorani                   	|
|        `mahmudi2021automatic`     | 2021 	| Other                                 	| Sorani                   	|
|        `ahmadi2021ickl`           | 2021  | Other                                     | Sorani                    |
|       `hashim2018kurdish`       	| 2018 	| Sign language recognition             	| Sorani                   	|
|   `kamal-hassani-2020-towards`  	| 2020 	| Sign language recognition             	| Sorani                   	|
|  `daneshfar2009implementation`  	| 2009 	| Speech recognition                    	| Sorani                   	|
|     `barkhoda2009comparison`    	| 2009 	| Speech recognition                    	| Sorani                   	|
|  `bahrampour2009implementation` 	| 2009 	| Speech recognition                    	| Sorani                   	|
|       `hassani2011kurdish`      	| 2011 	| Speech recognition                    	| Sorani                   	|
|       `dinler2017formant`       	| 2017 	| Speech recognition                    	| Kurmanji                 	|
|      `dinler2018extraction`     	| 2018 	| Speech recognition                    	| Sorani, Kurmanji         	|
|        `qader2019kurdish`       	| 2019 	| Speech recognition                    	| Sorani                   	|
|        `ahmadi-2020-klpt`       	| 2020 	| Toolkits				                   	| Sorani, Kurmanji         	|
|        `de2021multilingual`       | 2021  | Named-entity recognition                  | Kurmanji                  |



### Cite this repository

If you find the provided data useful for your project, feel free to use it and please, cite the following paper, too:

```
@inproceedings{ahmadi-2020-klpt,
    title = "{KLPT} {--} {K}urdish Language Processing Toolkit",
    author = "Ahmadi, Sina",
    booktitle = "Proceedings of Second Workshop for NLP Open Source Software (NLP-OSS)",
    month = nov,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.nlposs-1.11",
    doi = "10.18653/v1/2020.nlposs-1.11",
    pages = "72--84"
}

```