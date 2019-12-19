Parellel text / bitext Sample 
<s> hello, how are you </s>		<s>	مرحبا، كيف الحال </s> 
<s> fine and you </s>			<s>	تمام وانت كيفك </s> 





# Methods in MT 

1. Cancat source and target texts (with markers), use autoregressive RNN with the input sequence of the source language to generate the sequence of the target language


2. use encoder-decoder (seq2seq): input sequence is provided to encoder (RNN or LSTM or GRU), generate context vector (last hidden state), use context vector as input to decoder (RNN or LSTM or GRU) to generate the sequence in the target language

