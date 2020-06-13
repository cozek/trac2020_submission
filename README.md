# trac2020_submission
[TRAC 2020](https://sites.google.com/view/trac2/) Models code team **abaruah**

Paper: https://www.aclweb.org/anthology/2020.trac-1.12/

Please find the model and example training scipt for the
Transformer with AttentionHead Classification Layer in the `notebooks` directory.
The notebook can be easily modified to use any of the transformers used in the paper,
or any available transformer/classifier in the HuggingFace library. 

The same directory contains notebook for 
- HINDI Task B (Contains complete code with Checkpoint Ensembling)
- Dataset Analysis
- Error Analysis on the RoBERTa models.

Credits:

- RAdam : https://github.com/LiyuanLucasLiu/RAdam
- LookAhead: https://github.com/lonePatient/lookahead_pytorch
- Transformers: https://github.com/huggingface/transformers


If our code/paper was helpful, please cite:
```
@inproceedings{baruah-etal-2020-aggression,
    title = "Aggression Identification in {E}nglish, {H}indi and Bangla Text using {BERT}, {R}o{BERT}a and {SVM}",
    author = "Baruah, Arup  and
      Das, Kaushik  and
      Barbhuiya, Ferdous  and
      Dey, Kuntal",
    booktitle = "Proceedings of the Second Workshop on Trolling, Aggression and Cyberbullying",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association (ELRA)",
    url = "https://www.aclweb.org/anthology/2020.trac-1.12",
    pages = "76--82",
    abstract = "This paper presents the results of the classifiers we developed for the shared tasks in aggression identification and misogynistic aggression identification. These two shared tasks were held as part of the second workshop on Trolling, Aggression and Cyberbullying (TRAC). Both the subtasks were held for English, Hindi and Bangla language. In our study, we used English BERT (En-BERT), RoBERTa, DistilRoBERTa, and SVM based classifiers for English language. For Hindi and Bangla language, multilingual BERT (M-BERT), XLM-RoBERTa and SVM classifiers were used. Our best performing models are EN-BERT for English Subtask A (Weighted F1 score of 0.73, Rank 5/16), SVM for English Subtask B (Weighted F1 score of 0.87, Rank 2/15), SVM for Hindi Subtask A (Weighted F1 score of 0.79, Rank 2/10), XLMRoBERTa for Hindi Subtask B (Weighted F1 score of 0.87, Rank 2/10), SVM for Bangla Subtask A (Weighted F1 score of 0.81, Rank 2/10), and SVM for Bangla Subtask B (Weighted F1 score of 0.93, Rank 4/8). It is seen that the superior performance of the SVM classifier was achieved mainly because of its better prediction of the majority class. BERT based classifiers were found to predict the minority classes better.",
    language = "English",
    ISBN = "979-10-95546-56-6",
}
```

The Data is under Creative Commons Non-Commercial Share-Alike 4.0 licence CC-BY-NC-SA 4.0
If you used the data please cite
```
@InProceedings{trac2-dataset,
author = {Bhattacharya, Shiladitya and Singh, Siddharth and Kumar, Ritesh and Bansal, Akanksha and Bhagat, Akash and Dawer, Yogesh and Lahiri, Bornini and Ojha, Atul Kr.},
title = {Developing a Multilingual Annotated Corpus of Misogyny and Aggression},
booktitle = {Proceedings of the Second Workshop on Trolling, Aggression and Cyberbullying},
month = {May},
year = {2020},
address = {Marseille, France},
publisher = {European Language Resources Association (ELRA)},
pages = {158--168},
url = {https://www.aclweb.org/anthology/2020.trac2-1.25}
}
```
