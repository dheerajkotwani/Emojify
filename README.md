![](https://github.com/dheerajkotwani/Emojify/blob/main/repo_frame.png)

# Emojify 🍴
#### People use emojis every day... Emojis have become a new language that can more effectively express an idea or emotion. This visual language is now a standard for online communication, large online platform such as Twitter, Facebook and Instagram. Right now, the keyboard can predict emojis but only base on certain keywords and tags that are associated with emojis. So this project also does the same.
#### In this project, the model is predicting emoji's according to a given sentence using Deep Learning Models.

## Input
Text data consiting of different sentences along with the labels. Labels represent a particular emoji representing the sentence. 

- **emojify_test_x.csv** -  for testing our model
- **emojify_y_test.csv** -  for testing our model
- **emojify_train_x.csv** - for training our model
- **emojify_Y_train.csv** - for training our model

## Algorithm's Used
- RNN
- LSTM

### Emojify_Final.ipynb
[Emojify_Final.iypnb](https://github.com/dheerajkotwani/Emojify/blob/main/emojify_final.ipynb)   
This python script contains the code for the given model and its prediction.

## Result
**LSTM worked better than RNN** i.e. accuracy of the model is more by using LSTM than RNN.  
When we move from RNN to LSTM, we are introducing more & more controlling knobs, which control the flow and mixing of Inputs as per trained Weights. And thus, bringing in more flexibility in controlling the outputs.
So, LSTM gives us the most Control-ability and thus, Better Results. 
But also comes with more Complexity and Operating Cost.

## Additional Files
In this project, We have used the 6B 50D glove vector to build embedding matrix of words available in the glove vector.<br>
Downloading Link-> [glove.6B.50D.txt](https://github.com/dheerajkotwani/Emojify/blob/main/glove.6B.50d.txt)
