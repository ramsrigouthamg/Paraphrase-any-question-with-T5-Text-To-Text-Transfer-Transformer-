# Paraphrase any question with T5 (Text-To-Text Transfer Transformer) - Pretrained model and training script provided

Using this program you can generate **paraphrases** of any given question.

A detailed Medium blogpost explaining necessary steps can be [found here.](https://medium.com/@ramsrigouthamg/paraphrase-any-question-with-t5-text-to-text-transfer-transformer-pretrained-model-and-cbb9e35f1555)

## Input

The input to our program will be any **general question** that you can think of -

```Which course should I take to get started in data Science?```

## Ouput

The output will be **paraphrased** versions of the same question. Paraphrasing a question means, you create a new question that expresses the **same meaning** using a **different choice of words**.

**Paraphrased Questions generated from the T5 Model :**

```
0: What should I learn to become a data scientist?
1: How do I get started with data science?
2: How would you start a data science career?
3: How can I start learning data science?
4: How do you get started in data science?
5: What's the best course for data science?
6: Which course should I start with for data science?
7: What courses should I follow to get started in data science?
8: What degree should be taken by a data scientist?
9: Which course should I follow to become a Data Scientist?  
```

## Inference code
The **t5-pretrained-question-paraphraser.ipynb** notebook has all the code to run the model on any given question of your choice and generate paraphrases for it.
 

## Training the model
The training and validation datasets are present in the **paraphrase_data** folder.
Install the necessary libraries from **requirements.txt**.
Use any **GPU** machine and run **train.py**

Training this model for 2 epochs (default) took about 20 hrs on **p2.xlarge** (AWS ec2)

