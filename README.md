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
[Drive Model Link](https://drive.google.com/file/d/14-ty_Vmhm-8eM78EnvYihprMs9D-eRQE/view?usp=sharing)
Open this link then click "Open With Teachable Machine" 
<img width="1283" alt="Screenshot 2023-12-21 at 12 24 51 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/a53c96c0-b709-40eb-b701-17320c1c74b0">

If "Open With Teachable Machine" does not appear, download the file then navigate to the Teachable Machine Website.
[Link to Teachable Machine](https://teachablemachine.withgoogle.com/train)
Under "New Project" click on "Open Existing Project From File"
<img width="1263" alt="Screenshot 2023-12-21 at 12 21 11 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/7f876b40-1a89-42bc-92b4-b4d92c653bf2">

Let the File load then click "Train"<img width="1003" alt="Screenshot 2023-12-20 at 8 41 16 AM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/726d97b6-dd0e-40f8-9402-48b639ca4506">

After the Model has trained, click "Export Model"
<img width="331" alt="Screenshot 2023-12-21 at 12 29 51 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/cfbac56d-1b20-4777-91a2-401985dc46fa">

Once the model has loaded select the "Tensorflow" tab then "Keras"
<img width="796" alt="Screenshot 2023-12-21 at 1 35 20 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/871b8273-41b4-4a00-86cf-b50fe2d8a9ea">




Download the trained TF model and place it in the project directory or a subdirectory, or just keep it in your downloads. 
Update the model_path variable in the script with the correct path to the TF model. 
<img width="855" alt="Screenshot 2023-12-21 at 2 06 04 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/d81321b7-edcb-44cb-9e4a-d6b5e76b094d">

The pathname for the model and the text lables can be found in Finder on Mac. Here's a screenshot of what that looks like:

<img width="700" alt="Screenshot 2023-12-21 at 2 04 49 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/c55f88a8-dcad-4fb7-8f04-ef2d42fd571e">


Finally, run the program by pressing the "Run Button."
<img width="908" alt="Screenshot 2023-12-21 at 1 57 58 PM" src="https://github.com/Fyoung24/HorseDetector20-/assets/95723225/ff7ce037-f893-4349-a03b-7376c752cdfc">
The program should open your webcam and will run indefinitely until 'Q' is pressed.



### Versions:
[V1 README file](https://github.com/Fyoung24/HorseDetector20-/blob/main/README.md)

##### File Structure:
HorseDetector.py houses the necessary code to test/run the model. Opens the built-in webcam and starts the model.

##### Remaining Bugs and Future Improvements:
When you run the model the following message may appear:

```
2023-12-20 12:30:34.536168: I tensorflow/core/platform/cpu_feature_guard.cc:182] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: AVX2 AVX512F AVX512_VNNI FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
```   
**THIS IS NOT AN ERROR** the program will work fine without adressing this message at all.
I plan upon improving the accuracy of this model and expanding the range of animals it can recognize.

###### Contributing: 
Any improvements/optimizations are welcome. As I said above, I plan on creating a more robust model and perhaps expanding the range of animals it can recognize.




  

