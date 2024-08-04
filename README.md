# MusicGen
Music Generation Project

Here's a professional summary of the project based on the transcript you provided:

---

**Project Title: Music Generation Using Recurrent Neural Networks**

**Project Overview:**
This project focuses on the generation of music using advanced machine learning techniques. Originally intended as a music recommendation system, the project evolved into a music generation system, offering a more creative and challenging application of artificial intelligence.

**Datasets Used:**
1. **MAESTRO Dataset:** Initially, the project utilized the MAESTRO dataset, which comprises approximately 1,300 files. However, the generated music from this dataset was repetitive and did not meet quality expectations.
   
2. **ADL Dataset:** To improve results, the project incorporated the ADL dataset, consisting of around 12,000 to 13,000 files. This larger dataset significantly enhanced the quality of music generated, resulting in more diverse and less repetitive outputs.

**Model Architecture:**
- **Recurrent Neural Network (RNN):** The project employs a specialized type of neural network known as a Recurrent Neural Network (RNN), which is adept at handling sequential data and capturing dependencies over time.

- **Long Short-Term Memory (LSTM):** The specific RNN architecture used is LSTM, which addresses the vanishing gradient problem commonly encountered in traditional RNNs.

- **Bidirectional LSTM:** To further enhance performance, a Bidirectional LSTM was utilized, allowing the model to process data in both forward and backward directions. This approach leverages both past and future data, leading to more accurate predictions.

- **Regularization Techniques:** To prevent overfitting and improve generalization, dropout layers and normalization techniques were implemented within the neural network.

**Training Process:**
1. **Data Preprocessing:** MIDI files were processed to extract musical notes, represented by three parameters: pitch, duration, and step (timing). These notes were then organized into a sequence for the model to predict the subsequent note, which in this case is the 11th note, serving as the label for training.

2. **Weighted Training:** Different weights were assigned to parameters during training, emphasizing the importance of certain musical aspects, such as pitch over note duration, to enhance the musical quality.

3. **Model Performance:** The final model successfully generated music with a focus on accurate pitch representation, resulting in a coherent musical piece that aligns with human expectations of musical composition.

**Conclusion:**
The project demonstrates the potential of using advanced neural network architectures for creative tasks such as music generation. By leveraging larger datasets and employing sophisticated models like Bidirectional LSTMs, the project achieved significant improvements in the quality of generated music, paving the way for further exploration in AI-driven music creation.
