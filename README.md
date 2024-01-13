# ChatBot
1. First filtered Dataset according to my need from Hugging Face and used Samsum dataset
I loaded data from hugging Face
Link: https://huggingface.co/datasets/samsum
I used *Samsum dataset* for my project This dataset basicaly use to build text summarization models on conversational data. 
2. from transfer Learning concept I used one pre-trained model named Google's pegasus model
3. calculate accuracy with Rogue metric 
4. rogue score was very less so i have to fine tune the model with pytorch's Trainer API
5. Build my own model
6. compare accuracy
7. Rogue score increase 20%
8. hence project successful

9. Next Trained the same dataset on facebook/bart-large-cnn pre-trained model and obtained improved rough score than pegasus
10. 

