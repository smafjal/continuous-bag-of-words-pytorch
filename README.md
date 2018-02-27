### continuous-bag-of-words(CBOW)-pytorch
This is one of the implementation of CBOW model in pytorch lib. CBOW is used for learning the word(getting the word probability) by looking at the context. A single window was define for words context learnig. One of the objectives of CBOW model is to find two words similirity. 
 Nowadays CBOW is frequently used in many NLP deep learning task.
 
## RUN
```bash
python3 cbow_model_pytorch.py 
```
it will verbose all training loss.
**test_cbow** function used to show the two words similarity after learning the corpus context.
