![text_generation_sampling](https://user-images.githubusercontent.com/58797479/94343512-589f4900-0036-11eb-9481-f2a6e0bba710.png)

# Generate-Text
Using Recurrent Neural Networks it is possible to generate text . We can train the models on large text data ,let the model train on input data  and generate text.<br> 
Here I have tried to generate text ,on a war based ebook using recurrent neural network , In 2 ways.<br>
<ol>
  <li> In first one ,I have tried to build character level language model in which , the output is predicted character-wise . </li>
  <li> In this one ,  a embedding layer is used to find semantic relation between words and the input corpus in broken down into tokens.Then the model is trained on these tokens,to generate the text . More meaningfull results are provided by this models
  </ol>
<b>The model can be improved by :- </b>
<ol>
  <li>Increasing the input text corpus .</li>
  <li>Training with more no. epochs.</li>
  <li>Increasing the LSTM layers / Adding more neurons.</li>
  <li>Try with different temperatures that suit your requirement!</li>
  </ol>
  
  <h3><u>Note :- </h3></u>You can feed any text (book)to the model ,Try experimenting with the model , But don't expect to generate text like a real writer!!
  

