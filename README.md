# Machine-Translation

Machine translation, sometimes referred to by the abbreviation MT, is a sub-field of computational linguistics that investigates the use of software to translate text or speech from one language to another.

**Benefits**: speed, less expensive, smart

**Applications**: text translation, speech translation

There are **four types** of machine translation[2]–

1. Statistical Machine Translation (SMT),
2. Rule-based Machine Translation (RBMT),
3. Hybrid Machine Translation,and
4. Neural Machine Translation

### Statistical Machine Translation

It works by alluding to statistical models that depend on the investigation of huge volumes of bilingual content. It expects to decide the correspondence between a word from the source language and a word from the objective language. ***A genuine illustration of this is Google Translate.***

Presently, [SMT](https://kantanmtblog.com/2019/04/02/a-short-introduction-to-the-statistical-machine-translation-model/) is extraordinary for basic translation, however its most noteworthy disadvantage is that it doesn't factor in context, which implies translation can regularly be wrong or you can say, don't expect great quality translation. There are several types of statistical-based machine translation models which are: ***Hierarchical phrase-based translation, Syntax-based translation, Phrase-based translation, Word-based translation.***

### Rule-based Machine Translation

RBMT basically translates the basics of ***grammatical rules***. It directs a grammatical examination of the source language and the objective language to create the translated sentence. But, RBMT requires broad editing, and its substantial reliance on dictionaries implies that proficiency is accomplished after a significant period.

### Hybrid Machine Translation

HMT, as the term demonstrates, is a mix of RBMT and SMT. It uses a translation memory, making it unquestionably more successful regarding quality. Nevertheless, even HMT has a lot of downsides, the biggest of which is the requirement for enormous editing, and human translators will also be needed. There are several approaches to HMT like multi-engine, statistical rule generation, multi-pass, and confidence-based.

### Neural Machine Translation(NMT)

NMT is a type of machine translation that relies upon neural network models (based on the human brain) to build statistical models with the end goal of translation. The essential advantage of [NMT](https://towardsdatascience.com/neural-machine-translation-15ecf6b0b) is that it gives a solitary system that can be prepared to unravel the source and target text. Subsequently, it doesn't rely upon specific systems that are regular to other machine translation systems, particularly SMT.

Between 2016 and 2017, more data was created than in the whole of human history prior[3]. Since 2013, companies like Google and Microsoft started testing and developing the use of neural networks.  [Neural networks](https://www.youtube.com/watch?v=yu9gLQtPySQ) are statistical learning models, that were first used in speech and image recognition technology. Neural networks enable MT engines to train themselves, through a process similar to the way the brain works: through trial and error (which is called deep learning).

# DATASETS
- [ACL 2014 NINTH WORKSHOP ON STATISTICAL MACHINE TRANSLATION](https://www.statmt.org/wmt14/translation-task.html)
- [Bilingual Sentence Pairs](http://www.manythings.org/anki/)
- [Indic Languages Multilingual Parallel Corpus Dataset](https://github.com/AI4Bharat/indicnlp_corpus)
- [IIT Bombay English-Hindi Corpus](https://www.cfilt.iitb.ac.in/iitb_parallel/)
- [Parallel Corpus Filtering for Low-Resource Conditions](https://www.statmt.org/wmt19/parallel-corpus-filtering.html)
- [THIRD CONFERENCE ON MACHINE TRANSLATION (WMT18)](https://www.statmt.org/wmt18/parallel-corpus-filtering.html)
- [The FLORES-101 Evaluation Benchmark for Low-Resource and Multilingual Machine Translation](https://github.com/facebookresearch/flores)
- [WikiMatrix: Mining 135M Parallel Sentences in 1620 Language Pairs from Wikipedia](https://github.com/facebookresearch/LASER/tree/main/tasks/WikiMatrix)
- [TDIL](https://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1069&lang=en)

# PAPERS

## Statistical Machine Translation

[4] Mikel Artetxe, Gorka Labaka, Eneko Agirre. 2018. **Unsupervised Statistical Machine Translation**

[5] Solomon Teferra Abate, Michael Melese, Martha Yifiru Tachbelie, Million Meshesha, Solomon Atinafu, Wondwossen Mulugeta, Yaregal Assabie, Hafte Abera, Binyam Ephrem, Tewodros Abebe, Wondimagegnhue Tsegaye, Amanuel Lemma, Tsegaye Andargie, Seifedin Shifaw. 2018. **Parallel Corpora for bi-Directional Statistical Machine Translation for Seven Ethiopian Language Pairs**

[6] Aloka Fernando, Surangika Ranathunga, Gihan Dias. 2021. **Data Augmentation and Terminology Integration for Domain-Specific Sinhala-English-Tamil Statistical Machine Translation**

[7] Xing Wang, Zhaopeng Tu, and Min Zhang. 2015. **Incorporating Statistical Machine Translation Word Knowledge into Neural Machine Translation**

[8] Maria Stasimioti, Despoina Mouratidis. 2020. **Machine Translation Quality: A comparative evaluation of SMT, NMT and tailored-NMT outputs**


## Neural Machine Translation

[9] Alberto Poncelas, Dimitar Shterionov, Andy Way, Gideon Maillette de Buy Wenniger and Peyman Passban. 2018. **Investigating Backtranslation in Neural Machine Translation**

[10] Surangika Ranathunga, En-Shiun Annie Lee, Marjana Prifti Skenduli, Ravi Shekhar, Mehreen Alam, Rishemjit Kaur. 2021. **Neural Machine Translation for Low-Resource Languages: A Survey**

[11]  Sahinur Rahman Laskar. 2021. **Neural Machine Translation for Low Resource Assamese–English**

[12] Xiao Pan, Mingxuan Wang, Liwei Wu, Lei Li. 2021. **Contrastive Learning for Many-to-many Multilingual Neural Machine Translation**

[13] Deng Cai, Yan Wang, Huayang Li, Wai Lam, Lemao Liu. 2021. **Neural Machine Translation with Monolingual Translation Memory**
