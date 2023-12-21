# HorseDetector20% With Keras, Tensorflow, and Mediapipe

This project demonstrates real-time horse detection using TensorFlow Lite and the MediaPipe library.

## Installation

1. **Clone the Repository:**
   ```
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
  
2. **Install Dependencies**
   ```pip install mediapipe tensorflow opencv-python```


### Usage
Download the TF Model:

Download the trained TF model and place it in the project directory or a subdirectory. Update the model_path variable in the script with the correct path to the TF model:

[Link_to_model](https://teachablemachine.withgoogle.com/models/RlqUUeVyM/)

### Versions:
[Link to version 1 README.md file](https://github.com/Fyoung24/HorseDetector20-/blob/main/README.md)

##### File Structure:
HorseDetector.py houses the necessary code to test/run the model. Opens the built-in webcam and starts the model.

##### Remaining Bugs and Future Improvements:
When you run the model the following message may appear:
2023-12-20 12:30:34.536168: I tensorflow/core/platform/cpu_feature_guard.cc:182] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: AVX2 AVX512F AVX512_VNNI FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
**THIS IS NOT AN ERROR** the program will work fine without adressing this message at all.

###### Contributing: 
Any improvements/optimizations are welcome. I plan on creating a more robust model and perhaps expanding the range of animals it can recognize




  

