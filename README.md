# ASVP-ESD: A Dataset for Emotion Recognition from Non-Speech Utterances

## Overview
Emotion recognition plays a vital role in human-computer interaction, with applications in mental health monitoring, affective computing, and customer experience enhancement. Traditional methods primarily rely on linguistic audio data; however, non-speech vocalizations such as laughter, sighs, and crying also carry emotional cues.

This repository introduces **ASVP-ESD**, a novel dataset designed for emotion recognition using non-verbal auditory cues. It provides high-quality recordings of non-speech utterances labeled with emotional states and facilitates research in emotion recognition beyond speech-based datasets.

## Features
- **Non-speech vocalizations:** Includes various non-linguistic sounds such as laughter, sighs, crying, etc.
- **Emotion Labels:** Each sample is annotated with its corresponding emotional state.
- **Feature Extraction:** Temporal, spectral, and prosodic characteristics extracted for analysis.
- **Benchmark Models:** Performance evaluation using traditional Machine Learning and Deep Learning models:
  - **ML Models:** K-Nearest Neighbors (KNN), Random Forest (RF), Multi-Layer Perceptron (MLP), Gradient Boosting Classifier (GBC), LightGBM, Decision Tree (DT), and XGBoost.
  - **DL Models:** Long Short-Term Memory (LSTM), Gated Recurrent Units (GRU), and Bidirectional GRU (Bi-GRU).
- **Performance Analysis:** Comparison of models to determine effectiveness in non-verbal emotion recognition.

## Dataset
- **Dataset Name:** ASVP-ESD
- **Content:** High-quality non-speech utterances with emotion labels
- **Format:** Audio files with accompanying metadata
- **Use Cases:** Mental health monitoring, customer service analysis, virtual environments, and games

## Installation
Clone the repository:
```bash
  git clone https://github.com/your-username/ASVP-ESD.git
```
Install required dependencies:
```bash
  pip install -r requirements.txt
```

## Usage
1. **Preprocess Data:**
   ```python
   from preprocessing import preprocess_data
   data = preprocess_data("path_to_audio")
   ```
2. **Feature Extraction:**
   ```python
   from feature_extraction import extract_features
   features = extract_features(data)
   ```
3. **Train Models:**
   ```python
   from models import train_model
   model = train_model(features, labels, model_type='LSTM')
   ```
4. **Evaluate Performance:**
   ```python
   from evaluation import evaluate_model
   evaluate_model(model, test_data)
   ```

## Results
The experimental results showcase the strengths and limitations of different models in non-verbal emotion recognition, establishing a strong baseline for future research.

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or collaborations, feel free to reach out:
- **Email:** kshitijbudhe@gmail.com

