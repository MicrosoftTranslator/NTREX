# NTREX
NTREX -- News Test References for MT Evaluation from English into a total of 128 target languages with document-level information.

## Data structure

`NTREX-128/newstest2019-src.eng.txt` - original source data<br/>
`NTREX-128/newstest2019-ref.*` - human translated references for the original 128 languages<br/>
`NTREX-additional/newstest2019-ref.*` - human translated references for additional languages<br/>
`LANGUAGES.tsv` - mapping between ISO codes and language names<br/>
`DOCUMENT_IDS.tsv` - line aligned document boundaries

## Updates
References for two Swiss German dialects (Bern and Zurich German) collected as part of [this work](https://aclanthology.org/2023.wmt-1.99/) have been added to the `NTREX-additional` folder.<br/>
Data package has been released on 11/24/2022. Enjoy!

## License
The NTREX-128 data set is released under the [CC BY-SA 4.0 license](https://github.com/MicrosoftTranslator/NTREX/blob/main/LICENSE.md).

## How to Cite

For the original NTREX-128 dataset, please cite:
```
@inproceedings{federmann-etal-2022-ntrex,
    title = "{NTREX}-128 {--} News Test References for {MT} Evaluation of 128 Languages",
    author = "Federmann, Christian and Kocmi, Tom and Xin, Ying",
    booktitle = "Proceedings of the First Workshop on Scaling Up Multilingual Evaluation",
    month = "nov",
    year = "2022",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.sumeval-1.4",
    pages = "21--24",
}
```
as well as the WMT 2019 paper that provided the English source data NTREX-128 is based on:
```
@inproceedings{barrault-etal-2019-findings,
    title = "Findings of the 2019 Conference on Machine Translation ({WMT}19)",
    author = {Barrault, Lo{\"\i}c  and
      Bojar, Ond{\v{r}}ej  and
      Costa-juss{\`a}, Marta R.  and
      Federmann, Christian  and
      Fishel, Mark  and
      Graham, Yvette  and
      Haddow, Barry  and
      Huck, Matthias  and
      Koehn, Philipp  and
      Malmasi, Shervin  and
      Monz, Christof  and
      M{\"u}ller, Mathias  and
      Pal, Santanu  and
      Post, Matt  and
      Zampieri, Marcos},
    editor = "Bojar, Ond{\v{r}}ej  and
      Chatterjee, Rajen  and
      Federmann, Christian  and
      Fishel, Mark  and
      Graham, Yvette  and
      Haddow, Barry  and
      Huck, Matthias  and
      Yepes, Antonio Jimeno  and
      Koehn, Philipp  and
      Martins, Andr{\'e}  and
      Monz, Christof  and
      Negri, Matteo  and
      N{\'e}v{\'e}ol, Aur{\'e}lie  and
      Neves, Mariana  and
      Post, Matt  and
      Turchi, Marco  and
      Verspoor, Karin",
    booktitle = "Proceedings of the Fourth Conference on Machine Translation (Volume 2: Shared Task Papers, Day 1)",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/W19-5301",
    doi = "10.18653/v1/W19-5301",
    pages = "1--61",
}
```

For the additional Swiss German dialect references, please cite:
```
@inproceedings{aepli-etal-2023-benchmark,
    title = "A Benchmark for Evaluating Machine Translation Metrics on Dialects without Standard Orthography",
    author = {Aepli, No{\"e}mi  and
      Amrhein, Chantal  and
      Schottmann, Florian  and
      Sennrich, Rico},
    editor = "Koehn, Philipp  and
      Haddow, Barry  and
      Kocmi, Tom  and
      Monz, Christof",
    booktitle = "Proceedings of the Eighth Conference on Machine Translation",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.wmt-1.99",
    doi = "10.18653/v1/2023.wmt-1.99",
    pages = "1045--1065",
}
```