# MachineTranslation

Dataset : <br/>Hindi English Parallel Corpus consisting of 15k pairs of sentences in Hindi and English. <br/>

  
<br/>
Pre-processing steps performed are : 
<ul>
  <li>Removing special characters, quotes and extra space</li>
  <li>Adding start and end tokens in both English and Hindi</li>
  <li>Obtaining the Hindi and English Vocabulary</li>
</ul>

<br/>

Model Architecture :  <br/>Used a Encoder Decoder Architecture consisting of LSTM modules and Attention mechanism for capturing long range dependencies.<br/>

Model Evaulation :  <br/>Used bleu score metric of NLTK module to detect accuracies of model.<br/>
