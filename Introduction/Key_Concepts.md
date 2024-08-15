# Key Concepts in Multimodal Machine Learning

## Feature Extraction

Feature extraction involves identifying and selecting the most informative parts of the data. Techniques differ based on the modality, such as:

- **Text**: Tokenization, word embeddings (e.g., Word2Vec, BERT).
- **Images**: Convolutional Neural Networks (CNNs), edge detection.
- **Audio**: Spectrograms, Mel-Frequency Cepstral Coefficients (MFCC).

## Data Fusion

Combining information from multiple modalities can be done at various levels:

- **Early Fusion**: Data is combined before feeding into the model.
- **Late Fusion**: Outputs from individual models are combined.
- **Hybrid Fusion**: A combination of both early and late fusion.

## Modality Alignment

Alignment ensures that data from different modalities is synchronized. Techniques include:

- **Temporal Alignment**: Ensuring that data from different sources corresponds to the same time frame.
- **Semantic Alignment**: Ensuring that different modalities are semantically aligned, such as matching images with relevant text.
