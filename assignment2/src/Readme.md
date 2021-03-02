# Language Identification using N-Gram Language Model

# Problem what I solved

Final goal for this project is to identify sentence's written language by using bigram model I made. For this, I had to pre-process given three data set written by English, French, and Italian. Next, implement a letter bigram model, and word bigram model without using language model toolkits or libraries. Lastly, apply smoothing techniques for the unseen cases, calcuate each languages' score for every sentences and choose one lanugage that have higer score than others. Finally, I have 99% accuracy for identifing language correctly.

# How to run code
The way run these code is pretty straightforward, what you have to do is cloning this repository. If you make other language model, add your train data in the "src/Data/Input/folder", put your test data in the "src/Data/Validation/folder", and then final anwer will be saved at "src/Data/Output/folder". So what you have to do is try out all the ipynb below and apply best model your data fit in.

- letterLangId: This ipynb file implemented letter bigram model.
- wordLangId: This ipynb file implemented word bigram model and applied La-place smoothing.
- wordLangId2: This ipynb file also implemented word bigram model and applied simple Good-Turing smoothing.
