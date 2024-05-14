# SkimLit: Enhancing the Skim-ability of Unstructured Medical Abstracts

## Project Description
The SkimLit project is designed to make it easier for researchers to navigate the increasing volume of medical literature, particularly randomized controlled trials (RCTs) that lack structured abstracts. By employing Natural Language Processing (NLP) techniques, SkimLit classifies sentences within abstracts into distinct categories such as objectives, methods, results, etc. This classification aids researchers in quickly identifying the most relevant sections of a paper, facilitating faster literature review.

## Key Features
- **NLP Model**: Utilizes a machine learning model to classify text into predefined categories, enhancing the readability and accessibility of complex research papers.
- **GPU Acceleration**: Optimized for performance with GPU support to handle large volumes of data efficiently.
- **Automated Data Handling**: Includes scripts for automatic data retrieval and preprocessing from publicly available medical research databases.


## Models Used
### 1. **Long Short-Term Memory (LSTM) Networks**
Long Short-Term Memory networks, a type of recurrent neural network, are specifically designed to handle sequence prediction problems, making them highly effective for text processing tasks where the order and context of words are crucial for understanding.

### 2. **Bidirectional Encoder Representations from Transformers (BERT)**
BERT represents a revolutionary approach in NLP, using a transformer architecture that learns contextual relations between words (or sub-words) in a text.

### 3. **Convolutional Neural Networks (CNNs) for Sentence Classification**
While predominantly known for their use in image processing, Convolutional Neural Networks have been adapted for NLP tasks such as sentence classification.

### 4. **Hybrid Embedding Layer Model**
The Hybrid Embedding Layer Model in the SkimLit project is an innovative approach that combines pretrained token embeddings with character embeddings to create a rich, layered representation of text inputs.

### 5. **Transfer Learning with Pretrained Token, Character, and Positional Embeddings**
This model leverages transfer learning to utilize pretrained embeddings, which brings a foundational understanding of language that is then built upon with additional embeddings that capture character-level and positional information.

## Contributing
Contributions to SkimLit are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests to us.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments
- Thanks to all contributors who have participated in the development of SkimLit.
- Special thanks to the providers of the PubMed RCT dataset used for training our models.
