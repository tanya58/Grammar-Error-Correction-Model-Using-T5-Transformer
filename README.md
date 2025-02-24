# Grammar-Error-Correction-Model-Using-T5-Transformer
English Grammar Error Correction System
This project aims to develop an advanced English grammar error correction system using the T5 transformer model. It leverages an Encoder-Decoder architecture built from scratch to detect and correct grammatical mistakes in written text. The objective is to create a reliable and efficient tool that enhances text accuracy by automatically identifying and rectifying errors.

# Features
T5 Model Integration
This project utilizes the Transformer-based T5 (Text-to-Text Transfer Transformer) model, which is well-suited for a variety of natural language processing tasks. The T5 model has been fine-tuned specifically to identify and correct grammatical errors in English text, ensuring improved language accuracy.

Encoder-Decoder Architecture
Alongside the fine-tuned T5 model, a custom Encoder-Decoder architecture has been developed from scratch. This architecture enhances contextual understanding and enables the model to generate precise grammatical corrections, improving the overall accuracy of text correction.


# Model Training
Fine-Tuning the T5 Model
The T5 model is fine-tuned using a dataset containing annotated examples of grammatical errors. This process adapts the model specifically for English grammar correction, enabling it to effectively identify and rectify errors in written text.

Training the Encoder-Decoder Architecture
The custom Encoder-Decoder architecture is trained on a parallel dataset consisting of grammatically correct and incorrect sentences. During training, the model’s parameters are optimized to minimize the difference between the generated corrections and the actual correct sentences, ensuring accurate grammatical adjustments.

# Dataset
https://www.kaggle.com/datasets/satishgunjal/grammar-correction

# Result
The performance of the grammar correction system is evaluated using metrics such as precision, recall, and F1 score, Bleu.
Average BLEU Score: 0.6847878463169301
