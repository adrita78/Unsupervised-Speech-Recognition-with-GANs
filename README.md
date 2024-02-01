# Unsupervised-Speech-Recognition-with-GANs

# Wav2Vec-U: Unsupervised Speech Recognition with GANs

This project aims to re-implement and enhance the Generative Adversarial Network (GAN)-based unsupervised model for speech recognition, known as wav2vec-U. The proposed method introduces novel approaches to training speech recognition models without the need for labeled data.

## Key Features

- **Self-Supervised Learning:** Leveraging self-supervised speech representations to autonomously segment unlabeled audio.
- **Adversarial Training:** Establishing a mapping from representations to phonemes through adversarial training.
- **Ablation Experiments:** Various experiments with different generator and discriminator architectures, schedulers, optimizers, and data augmentation techniques.
- **Performance Metrics:** Achieving a Levenshtein distance of 20.12 on the test dataset and substantial reductions in phoneme error rate on benchmark datasets.
- **Language Adaptability:** Demonstrating adaptability to diverse languages, including low-resource ones like Kyrgyz, Swahili, and Tatar.

## Results

- **TIMIT Benchmark:** Outperforming existing unsupervised approaches with a phoneme error rate reduction from 26.1 to 11.3.
- **Librispeech Dataset:** Achieving a remarkable word error rate of 5.9 on the test-other subset.
- **Versatility:** Experimental results on nine languages, showcasing the versatility and applicability of the proposed method.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wav2vec-U.git
   cd wav2vec-U
