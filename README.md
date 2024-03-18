
# Real Life Violence Detection

This project aims to detect violence in real-life scenarios using deep learning techniques. It utilizes a combination of image processing, deep neural networks, and machine learning algorithms for accurate detection.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/keshav-kumar-01/Fight-Detection.git
   ```

2. Install the required packages:

   ```bash
   pip install tensorflow opencv-python scikit-image pillow
   ```

## Usage

1. Define the video fight detection model:

   ```python
   def mamon_videoFightModel2(tf, wight='/path/to/mamonbest947oscombo-drive.hdfs'):
       # Model definition code here
       return model
   ```

2. Load the pre-trained model:

   ```python
   model22 = mamon_videoFightModel2(tf)
   ```

3. Define your learning rate and update the optimizer:

   ```python
   your_learning_rate = 0.001
   optimizer = tf.keras.optimizers.Adam(learning_rate=your_learning_rate)
   ```

4. Compile the model with the updated optimizer:

   ```python
   model22.compile(optimizer=optimizer, loss='binary_crossentropy', metrics=['accuracy'])
   ```

5. Define a function to read video frames:

   ```python
   def video_mamonreader(cv2, filename):
       # Video reading code here
       return frames
   ```

6. Define a function to predict fights in videos:

   ```python
   def pred_fight(model, video, accuracy=0.9):
       # Prediction code here
       return fight, precent
   ```

7. Define the main function to process video files:

   ```python
   def main_fight(folder_path):
       # Main processing code here
       return res_mamon
   ```

8. Specify the folder containing your video files and call the `main_fight` function:

   ```python
   folder_path = '/path/to/your/video/files'
   res = main_fight(folder_path)
   ```

9. Access the result containing information about detected fights and processing time.

## Dependencies

- TensorFlow
- OpenCV
- scikit-image
- Pillow

## Contributors

- [Keshav Kumar](https://github.com/keshav-kumar-01)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Note: Replace `/path/to/your/video/files` with the actual path to your video files and update the URLs, file paths, and contributor information according to your project.
