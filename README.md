# PCR4ALL

This is the github repo for LREC 2022 paper "PCR4ALL: A Comprehensive Evaluation Benchmark for Pronoun Coreference Resolution in English".

## Dependency

Python 3.6, Pytorch 1.1

## Introduction of PCR4ALL
This repo includes the a large-scale WSC-style binary choice questions to evaluate pronoun coreference resolution systems from various domains and aspects. 


#### Dataset Format

    Datatset: a list of WSC-style questions.

        Question: a dictionary. The keys and values are:

            "sentence": the original context, with "_" as the place for the pronoun/candidates;
            
            "pronoun": the pronoun used in the original sentence, if any;

            "option1"/"option2": two possible textual candidates;
            
            "answer": 1 or 2. The correct answer to the question.
            
            "is_X": X represents one in linguistic, knowledge, medical, casual, formal, and gender_bias. True/False denotes if the 
            question belongs to the correpsonding category.
            
            "data_source": original wsc source;
            
## Others
If you have any other questions about this repo, you are welcome to open an issue or send me an [email](mailto:xzhaoar@connect.ust.hk), I will respond to that as soon as possible.
