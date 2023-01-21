# SEQUENCE GENERATION WITH RNN: SHAKESPEARE POEMS
This project reads Shakespeare poems and generates new poems. You can give your own sentences and it will generate new poems based on it. Recurrent Neural Networks is used here , more specifically LSTM layer which gives greater performance and can remember longer sequences than simple RNN.
<br>
<ul>
<li>This project reads text from shakespeare.txt file and breaks it into small training examples.</li>
<br>
<li>Then its trained on model with LSTM layer -> Dropout layer -> Dense layer with softmax activation for around 130 epochs.</li>
<br>
<li>Finally you can generate new outputs every time in shakespeare's style. </li>
<br>
<li>Generate output function takes initial senetence and no. of words you want to generate. </li>

<ul>
