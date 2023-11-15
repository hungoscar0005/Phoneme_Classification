# Phoneme_Classification
Framewise phoneme prediction from speech. (phoneme: A unit of sound that can distinguish one word from another in a particular language.)  
Data source : LibriSpeech (subset of train-clean-100)  

## Dataset Description
train_split.txt - train metadata (Phoneme ID)  
train_labels.txt - train labels  (Phoneme match to its frame)  
test_split.txt - test metadata  
feat/train/{id}.pt & feat/test/{id}.pt - 39-dimension MFCC w/ CMVN for each utterance(audio)  

