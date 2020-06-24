# Text_Generation_LanguageModelling
In this project we will develop a poetry generation model. 
A kind of a Text generation "Language Modelling".

Doing this project made me realisie that the Langugae modelling
and Seq2Seq decoder part (with Teacher Forcing) have a lot similarities.

The slight yet impacting difference is that the initial hidden state in a language model
is an arbitratry vector, while the hidden start input in the Decoder of the Encoder-Decoder 
model is the 'CONTEXT' or 'THOGHT' vector produced by the endoder.


