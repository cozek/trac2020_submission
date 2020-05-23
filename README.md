# trac2020_submission
[TRAC 2020](https://sites.google.com/view/trac2/) Models code team **abaruah**

Paper: http://panlingua.co.in/trac-2/pdf/2020.trac2-1.12.pdf

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
@InProceedings{trac2abaruah,
author = {Baruah, Arup and Das, Kaushik Amar and Barbhuiya, Ferdous Ahmed and Dey, Kuntal},
title = {Aggression Identification in English, Hindi and Bangla Text using BERT, RoBERTa and SVM},
booktitle = {Proceedings of the Second Workshop on Trolling, Aggression and Cyberbullying},
month = {May},
year = {2020},
address = {Marseille, France},
publisher = {European Language Resources Association (ELRA)},
pages = {76--82},
url = {http://panlingua.co.in/trac-2/pdf/2020.trac2-1.12.pdf}
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
