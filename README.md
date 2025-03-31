# Sleep Stage Classification using EEG Signals

## Overview
This project implements a **Sleep Stage Classification** system using **EEG signals** and **Machine Learning**. The system processes EEG data, extracts relevant features, and classifies sleep stages into different categories such as **Wake (W), N1, N2, N3 (Deep Sleep), and REM**.

## Features
- **Preprocessing:** Noise removal, filtering, and normalization of EEG signals.
- **Feature Extraction:** Time-domain, frequency-domain, and time-frequency features.
- **Machine Learning Models:** SVM, Random Forest, CNN, LSTM, etc.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score.
- **Visualization:** Sleep stage predictions and EEG signal plots.

## Dataset
The project utilizes publicly available EEG datasets such as:
- **Sleep-EDF** (Expanded)
- **PhysioNet Sleep Database**

Ensure you have the necessary permissions to use the datasets.

## Installation
Clone the repository:
```sh
git clone https://github.com/yourusername/sleep-stage-classification.git
cd sleep-stage-classification
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage
### Data Preprocessing
```sh
python preprocess.py --data_path ./data
```

### Train Model
```sh
python train.py --model cnn --epochs 50
```

### Evaluate Model
```sh
python evaluate.py --model cnn
```

### Predict Sleep Stages
```sh
python predict.py --input_file sample_eeg.csv
```

## Results
- Achieved **X% accuracy** using CNN on Sleep-EDF dataset.
- Feature importance analysis shows [mention insights].
- Model comparison available in `results/`.

## Future Work
- Improve classification using hybrid models.
- Integrate real-time EEG data processing.
- Deploy as a web application.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## References
1. Sleep-EDF Database: https://physionet.org/content/sleep-edfx/1.0.0/
2. PhysioNet: https://physionet.org/

