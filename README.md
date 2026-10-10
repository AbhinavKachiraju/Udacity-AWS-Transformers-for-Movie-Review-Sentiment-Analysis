# Udacity-AWS-Transformers-for-Movie-Review-Sentiment-Analysis



Summarize the project results 
I trained a 4-layer transformer to classify IMDB reviews as positive or negative. 
After 7 epochs, validation accuracy was 79.56% and test accuracy was 76.89%, above 75% target. 
Validation accuracy peaked at about 80% after epoch 5, while training loss kept falling, showing overfitting


List key takeaways 
  a. classification averages all token embeddings into one vector and feeds it to a linear with two outputs. 
  b. Training for more than 5 epochs only increased overfitting, trining loss kept falling but validation accuracy was aroung 80% mark 
  c. The final model reached 76.89% accuracy, above 75% target
