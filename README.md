# Question-Generation-and-Answering-for-Cooking-Recipes
Boolean Question Generation and Answering System for Cooking Recipes


# Self-answering self generated questions
Combine boolean question generation and boolean question answering, to answer the generated questions. The dataset will be annotated manually.



Our datasets and models codebases:
the dataset used is Food Ingredients and Recipes Dataset with Images : https://www.kaggle.com/datasets/pes12017000148/food-ingredients-and-recipe-dataset-with-images
the models codebases are

Our evaluation base model : https://pypi.org/project/boolean-question/

roberta-base : https://huggingface.co/roberta-base

roberta-base-boolq : https://huggingface.co/shahrukhx01/roberta-base-boolq

To run the code download the models and place them in models folder and the datasets exist in our repository then run the desired notebook

trained and stored model:

1.roberta-base retrained with 2000 auto-generated questions : https://drive.google.com/file/d/1oRte7R7lthNWoUWnfSB-JHP7sqcyoKsE/view?usp=sharing

2.roberta-base-boolq retrained with 2000 auto-generated questions : https://drive.google.com/file/d/1vnJQAz2DsTiRCqG68I3ygjwmecvxt5Ep/view?usp=sharing


Our questions datasets are avalible in our git repository

Based on our intial evaluations, base model's accuracy is 55.5% when tested with auto-generated questions and 64% when tested with manually-generated questions, 
and the first model's accuracy is 55.5% when tested with auto-generated questions and 57.1% when tested with manually-generated questions,
and the second's accuracy is 61.75% when tested with auto-generated questions and 61% when tested with manually-generated questions. 


Most of our datasets collecting/building/pre-processeding are illustrated in our QuestionGeneration file. Our data spilting is demonstrated in Model_retraining file. 

Our solution architecture, how you provided parameters and how you supplied it with training data are demonstrated in Model_retraining file.

Our evaluation is represented in EvaluateBaseModel file for the base model, and EvaluateOurModels file for our models.

Mainly we will be using Demo file to Demonstrate our work.
