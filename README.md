# cllm_rnn
first stab at character level language model rnn

Note that this is a simple RNN. It is NOT a seq2seq model. That is, it DOES not consume the entire input sequence before generating the entire output sequence. 

In fact, the output is kind of interesting. We simply output the loss directly, without any prediction task. 
