# SSVEP-based GoPiGo Navigation

This project implements a Steady-State Visual Evoked Potential (SSVEP)-based navigation system for the GoPiGo robot. The system uses EEG signal processing and machine learning techniques to classify brain signals and control the robot's movement.

## Dependencies

To install the required dependencies, run the following commands:

```bash
pip install mne numpy pandas scikit-learn joblib pyriemann
pip install umap-learn matplotlib
pip install pyqt5
pip install mlxtend
```

## How to Run
1. Install all dependencies listed above.
2. python main.pyRun the main script to start the project:
```bash
python main.py
```
.
├── [best_model_checkpoint.h5](http://_vscodecontentref_/1)      # Pre-trained model checkpoint
├── [chrononet_live.py](http://_vscodecontentref_/2)             # Real-time ChronoNet-based EEG processing
├── [ChronoNet_Model.py](http://_vscodecontentref_/3)            # ChronoNet model implementation
├── [CNN_EEGNET.py](http://_vscodecontentref_/4)                 # CNN-based EEGNet implementation
├── [compare_and_populate.py](http://_vscodecontentref_/5)       # Script for comparing and populating results
├── [comparison.py](http://_vscodecontentref_/6)                 # Comparison of different models
├── [config.json](http://_vscodecontentref_/7)                   # Configuration file for the project
├── [confusion_and_compare.py](http://_vscodecontentref_/8)      # Confusion matrix generation and model comparison
├── [cortex_live.py](http://_vscodecontentref_/9)                # Real-time Cortex EEG processing
├── [cortex.py](http://_vscodecontentref_/10)                     # Cortex EEG processing utilities
├── [CSP_SVM.py](http://_vscodecontentref_/11)                    # Common Spatial Pattern (CSP) with SVM model
├── [data_import_ChronoNet.py](http://_vscodecontentref_/12)      # Data import utilities for ChronoNet
├── [data_import_eegnet.py](http://_vscodecontentref_/13)         # Data import utilities for EEGNet
├── [data.csv](http://_vscodecontentref_/14)                      # Dataset file
├── [DWT_KNN.py](http://_vscodecontentref_/15)                    # Discrete Wavelet Transform (DWT) with KNN model
├── [DWT_SVM.py](http://_vscodecontentref_/16)                    # DWT with SVM model
├── [EEGNET_live.py](http://_vscodecontentref_/17)                # Real-time EEGNet-based EEG processing
├── [EEGNet_Model.py](http://_vscodecontentref_/18)               # EEGNet model implementation
├── [EEGNET.py](http://_vscodecontentref_/19)                     # EEGNet utilities
├── [Fast_Fourier.py](http://_vscodecontentref_/20)               # Fast Fourier Transform (FFT) utilities
├── FFT with [PSD_SVM.py](http://_vscodecontentref_/21)           # FFT with Power Spectral Density (PSD) and SVM model
├── [FFT_KNN.py](http://_vscodecontentref_/22)                    # FFT with KNN model
├── [FFT_new.py](http://_vscodecontentref_/23)                    # Updated FFT implementation
├── [FFT_SVM.py](http://_vscodecontentref_/24)                    # FFT with SVM model
├── [Four_class.py](http://_vscodecontentref_/25)                 # Four-class classification script
├── [log.txt](http://_vscodecontentref_/26)                       # Log file for tracking execution
├── [LSTM_Live.py](http://_vscodecontentref_/27)                  # Real-time LSTM-based EEG processing
├── [main.py](http://_vscodecontentref_/28)                       # Main entry point for the project
├── [model_svm.joblib](http://_vscodecontentref_/29)              # Pre-trained SVM model
├── [oussama.h5](http://_vscodecontentref_/30)                    # Another pre-trained model checkpoint
├── [predict_GRU.py](http://_vscodecontentref_/31)                # GRU-based prediction script
├── [profiles.json](http://_vscodecontentref_/32)                 # User profiles or configuration
├── [PSD_SVM.py](http://_vscodecontentref_/33)                    # PSD with SVM model
└── [README.md](http://_vscodecontentref_/34)                     # Project documentation
Key Files
main.py: The main script to run the project.
ChronoNet_Model.py: Contains the implementation of the ChronoNet model.
EEGNet_Model.py: Contains the implementation of the EEGNet model.
CSP_SVM.py: Implements CSP with SVM for EEG signal classification.
FFT_SVM.py: Implements FFT with SVM for EEG signal classification.
config.json: Stores configuration parameters for the project.
Logs and Outputs
log.txt: Contains logs generated during the execution of the project.
best_model_checkpoint.h5: Stores the best model checkpoint for ChronoNet.
model_svm.joblib: Stores the pre-trained SVM model.
Dataset
data.csv: The dataset used for training and testing the models.
Authors
This project was developed by Subhodeep Basu, Arko Singh, Sreerupa Roy, Bhagyashree Mane and Oussama. Contributions are welcome!