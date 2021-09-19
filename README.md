# A Catalog for Odia Language NLP Resources
The purpose of this catalog is to provide a one-stop solution for the researchers looking for Odia NLP resources. This is a collective effort and any contribution to enriching Odia NLP resource are welcome. All contributors are listed on the <a href="https://github.com/shantipriyap/Odia-NLP-Resource-Catalog/blob/master/CONTRIBUTORS.md">CONTRIBUTOR</a> list. 

Table of Contents
=================
* [NLP Repositories](#nlp-repositories)
* [Text Corpora](#text-corpora)
    * [Parallel Translation Corpus](#parallel-translation-corpus)
    * [Monolingual Corpus](#monolingual-corpus)
    * [Lexical Resources](#lexical-resources)
    * [POS Tagged corpus](#pos-tagged-corpus)
* [Models](#models)
    * [Language Model](#language-model)
    * [Word Embedding](#word-embedding)
    * [Morphanalyzers](#morphanalyzers)
* [Text Classification](#text-classification)
* [Libraries / Tools](#libraries--tools)
* [Speech Corpora](#speech-corpora)
* [Other Indian language NLP Resources](#other-indian-language-nlp-resources)

## NLP Repositories
* <a href="http://tdil-dc.in/index.php?lang=en">TDIL</a> : It contains language application, resources, and tools for Indian languages including Odia. It contains many language applications, resources, and tools for Odia such as Odia terminology application, Odia language search engine, wordnet, English-Odia parallel text corpus, English-Odia machine-assisted translation, text-to-speech software, and many more.  

## Text Corpora

### Parallel Translation Corpus
* <a href="https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3211">OdiEnCorp 2.0</a> : This dataset contains 97K English-Odia parallel sentences and serving in <a href="http://lotus.kuee.kyoto-u.ac.jp/WAT/WAT2020/index.html"> WAT2020</a> for Odia-English machine translation task. <a href="https://www.aclweb.org/anthology/2020.wildre-1.3.pdf">Paper</a> 
* <a href="http://opus.nlpl.eu/">OPUS Corpus</a> : It contains parallel sentences of other languages with Odia. The collection of data are domain-specific and noisy.  
* <a href="https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2879">OdiEnCorp 1.0</a> : This dataset contains 30K English-Odia parallel sentences. <a href="https://link.springer.com/chapter/10.1007/978-981-13-9282-5_47">Paper</a> 
* <a href="https://github.com/anoopkunchukuttan/indowordnet_parallel">IndoWordnet Parallel Corpus</a> : Parallel corpora mined from IndoWordNet gloss and/or examples for Indian-Indian language corpora (6.3 million segments, 18 languages including Odia). <a href="https://github.com/anoopkunchukuttan/indowordnet_parallel/blob/master/iwn_parallel_2020.pdf">Paper</a>
* <a href="http://data.statmt.org/pmindia/">PMIndia</a> : Parallel corpus for En-Indian languages mined from Mann ki Baat speeches of the PM of India. It contains 38K English-Odia parallel sentences.<a href="https://arxiv.org/abs/2001.09907">Paper</a> 
* <a href="http://preon.iiit.ac.in/~jerin/bhasha/">CVIT PIB</a> : Parallel corpus for En-Indian languages mined from press information bureau website of India. It contains 60K English-Odia parallel sentences. 

### Monolingual Corpus
* <a href="https://www.lancaster.ac.uk/fass/projects/corpus/emille/">EMILLE Corpus</a> : It contains fourteen monolingual corpora for Indian languages including Odia.<a href="https://www.lancaster.ac.uk/fass/projects/corpus/emille/MANUAL.htm">Manual</a> 
* <a href="https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2879">OdiEnCorp 1.0</a> : This dataset contains 221K Odia sentences.<a href="https://link.springer.com/chapter/10.1007/978-981-13-9282-5_47">Paper</a> 
* <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus">AI4Bharat-IndicNLP Corpus</a> : The text corpus not available now (will be available later). It used 3.5M Odia sentences to build the embedding. Vocabulary frequency files are available.<a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus/blob/master/ai4bharat-indicnlp-corpus-2020.pdf">Paper</a>
* <a href="https://oscar-corpus.com/">OSCAR Corpus</a> : It contains around 300K Odia sentences.

### Lexical Resources
* <a href="http://www.cfilt.iitb.ac.in/indowordnet/">IndoWordNet</a> : Wordnet for Indian languages including Odia.


### POS Tagged corpus
* <a href="http://sanskrit.jnu.ac.in/ilci/index.jsp/">Indian Language Corpora Initiative</a> : It contains parallel annotated corpora in 12 Indian languages including Odia (tourism and health domain). 

## Models

### Language Model
* <a href="https://github.com/goru001/nlp-for-odia">Language Model</a> : Pretrained Odia Language Model. 
* * <a href="https://colab.research.google.com/gist/satyapb2002/aeb7bf9a686a9c7294ec5725ff53fa49/odiabert_languagemodel.ipynb#scrollTo=xy_H5EjNTdRE">BertOdia</a> : Bert-based Odia Language Model.

### Word Embedding
* <a href="https://fasttext.cc/docs/en/crawl-vectors.html">FastText (CommonCrawl + Wikipedia)</a> : Pretrained Word vector (CommonCrawl + Wikipedia). Trained on Common Crawl and Wikipedia using fastText. Select the language "oriya" from the model list.
* <a href="https://fasttext.cc/docs/en/pretrained-vectors.html">FastText (Wikipedia)</a> : Pretrained Word vector (Wikipedia). Trained on Wikipedia using fastText. Select the language "oriya" from the model list.
* <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus">AI4Bharat IndicNLP Project</a> : Pretrained Word embeddings for 10 Indian languages including Odia. <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus/blob/master/ai4bharat-indicnlp-corpus-2020.pdf">Paper</a>

### Morphanalyzers
* <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus">IndicNLP Morphanalyzers</a> : Unsupervised morphanalyzers for 10 Indian languages including Odia learnt using morfessor.


## Text Classification
* <a href="https://www.kaggle.com/disisbig/odia-news-dataset">Odia News Article Classification</a> : This dataset contains approxmately 19,000 news article headlines collected from Odia news websites. The labeled dataset is splitted into training and testset suitable for supervised text classification. 
* <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus">AI4Bharat IndicNLP News Articles</a> : This datasets comprising news articles and their categories for 9 languages including Odia. For Odia language, it has 4 classes (business, crime, entertainment, sports) and each class contains 7.5K news articles. The dataset is balanced across classes. <a href="https://github.com/ai4bharat-indicnlp/indicnlp_corpus/blob/master/ai4bharat-indicnlp-corpus-2020.pdf">Paper</a>

## Libraries / Tools 
* <a href="https://github.com/anoopkunchukuttan/indic_nlp_library">Indic NLP Library</a> : It is a python based NLP library for Indian language text processing including Odia.
* <a href="https://indic-ocr.github.io/">Indic-OCR</a> : OCR tools for Indic scripts including Odia. Also, supports Ol Chiki (Santali).
* <a href="https://github.com/shantipriyap/odia_nlp">Odia Romanization Script</a> : The perl script "odiaroman" maps the Devnagri (Odia) to Latin.

## Speech Corpora
* <a href="https://www.iitm.ac.in/donlab/tts/index.php">IIT Madras IndicTTS</a> : The Indic TTS project develops the text-to-speech (TTS) synthesis system for Indian languages including Odia. The database contains spoken sentences/utterances recorded by both Male and Female native speakers.
* <a href="http://www.ldcil.org/resourcesSpeechCorpOriya.aspx">LDC-IL</a> :  It includes Odia annotated speech corpora which has voices of 450 different native speakers.


## Other Indian language NLP Resources
A comprehensive list of Indian language NLP resources can be found in the <a href="https://github.com/indicnlpweb/indicnlp_catalog">IndicNLP Catalog</a> 

