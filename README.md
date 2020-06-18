# Cough-analysis-for-COVID-19
# Dataset used:

ESC-50 cough samples [snaps](https://www.kaggle.com/kartikay99k/cough-detection) and [audio files](https://www.kaggle.com/mmoreaux/environmental-sound-classification-50)

# Work-Flow
# Audio processing part
1. We begin with loading the signals for mel-spectrogram and MFCC signal processing, refer [notebook](signal_processing.ipynb)
2. Use [Librosa](https://librosa.org/librosa/) file for performing Mel-spectrogram and MFCC processing

# Image part

**Libraries Used**
1. [pytorch libraries](https://pytorch.org/)
2. pytorch image [transformers](https://pytorch.org/docs/stable/torchvision/transforms.html)
3. pytorch pretrained model [MobileNet_V2](https://pytorch.org/docs/stable/torchvision/models.html)

# Required settings for optimal usage
1. GPU/TPU

# Data Visualizations
![work in progress](https://image.shutterstock.com/z/stock-vector-caution-work-in-progress-image-1473524501.jpg)
