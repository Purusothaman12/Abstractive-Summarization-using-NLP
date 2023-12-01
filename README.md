# Abstractive-Summarization-using-NLP

In my abstractive summarization project utilizing NLP, I meticulously processed the data through tokenization and cleaning. Taking a step further, I employed GloVe 300 for tokenization and encoding. The project stands out with the implementation of three distinct training models:

1)build_seq2seq_model_with_just_lstm: This model is a Seq2Seq architecture with exclusive use of LSTMs in both the encoder and decoder. It highlights the fundamental LSTM structure for sequence-to-sequence tasks.

2)build_seq2seq_model_with_bidirectional_lstm: Another variant involves Bidirectional LSTMs in both the encoder and decoder. This bidirectional approach enhances the model's ability to capture contextual information from both directions in the input sequence.

3)build_hybrid_seq2seq_model: This model boasts a hybrid architecture, featuring Bidirectional LSTMs in the encoder and traditional LSTMs in the decoder. This combination leverages the advantages of bidirectionality during encoding while maintaining the simplicity of LSTMs during decoding.

These models were strategically chosen to explore different aspects of sequence-to-sequence modeling. The hybrid approach, in particular, harnesses the strengths of both LSTM configurations. The outcomes of these models contribute to a comprehensive understanding of their respective strengths and limitations, providing valuable insights for future developments in abstractive summarization. Overall, this project showcases a nuanced exploration of sequence-to-sequence architectures in the context of NLP, demonstrating a commitment to sophisticated model design and experimentation.
