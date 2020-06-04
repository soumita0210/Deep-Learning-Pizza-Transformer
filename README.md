# Deep-Learning-Pizza-Transformer

In this project we address the task of using Neural Machine Translation to apply artistic style transfer. While this may look like another translation task, the challenge is that the input and target maintains almost similar vocabulary and thus the model would be learning a particular writing style rather than word level translations. Seq2Seq model leveraging Recurrent Neural Networks like LSTM(Long Short Term Memory) has been used previously to convert modern english language to Shakespearean style. We aim to further improve the speed and quality of this style transfer using Transformer model. The Transformer model based solely on attention mechanisms, dispensing with recurrence and convolutions entirely reduces the training time as the system is more parallelizable yet producing better translations. Following this we present a modified version of Transformer named as the Pizza structure which proves to give better quality style transfer in spite of having less number of parameters. We further compare the performance of all the three models : Seq2Seq with Attention, Transformer and Pizza Transformer.


**Tools used:** Python, Tensorflow, nltk

**Hand-picked examples:**

Input: i will hit you !

Output: i will strike thee !


Input: Don’t worry about me .

Output: fear me not .


Input: What is wrong with you ?

Output: what is thy wrong with thee ?


Input: I am very happy .

Output: i am much merry .


Input: what do you want ? 

Output: what s your will ?
