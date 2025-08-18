# Computer Vision Lab Experiments

This repository contains implementations of various Computer Vision practical experiments based on the syllabus for the "Lab Computer Vision" course (Code: 23CT1522) from Yeshwantrao Chavan College of Engineering. The experiments cover fundamental and advanced topics in image processing, feature extraction, object detection, motion estimation, and recognition tasks.

These implementations are primarily in Python, using libraries such as OpenCV, NumPy, Matplotlib, and deep learning frameworks like TensorFlow or PyTorch where applicable (e.g., for YOLO and R-CNN).

## Course Outcomes
Upon successful completion of these experiments, you will be able to:
1. Apply image enhancement and smoothing techniques to improve image quality for further analysis.
2. Extract meaningful features from images using descriptors such as HOG and SIFT.
3. Implement and evaluate modern object detection methods including YOLO and R-CNN.
4. Analyze and develop solutions for motion estimation, object recognition, and facial expression recognition using classical and learning-based methods.

## List of Experiments
1. **Image Enhancement using Grey Level Transformations**  
   - Implement various grey level transformations to enhance image quality.

2. **Image Smoothing using Convolution**  
   - Apply convolution processes on an input image for smoothing.

3. **Histogram of Oriented Gradients (HOG) for Feature Extraction**  
   - Implement HOG to extract features from images.

4. **Scale Invariant Feature Transform (SIFT)**  
   - Apply SIFT on an input image for feature detection and description.

5. **Object Detection using YOLO**  
   - Implement the YOLO algorithm for real-time object detection.

6. **Object Detection using R-CNN**  
   - Implement R-CNN algorithms for object detection.

7. **Motion Estimation using Optical Flow**  
   - Implement optical flow techniques for motion estimation.

8. **Object Recognition**  
   - Develop a system for recognizing objects in images.

9. **Facial Expression Recognition**  
   - Implement recognition of facial expressions using classical or learning-based methods.

(Note: The original document lists 9 experiments, though the query mentioned 10. If an additional experiment is intended, it can be added later.)

## Prerequisites
- Python 3.x
- Libraries: 
  - OpenCV (`pip install opencv-python`)
  - NumPy (`pip install numpy`)
  - Matplotlib (`pip install matplotlib`)
  - Scikit-Image (`pip install scikit-image`) for some feature extractions
  - TensorFlow or PyTorch for deep learning-based experiments (e.g., YOLO, R-CNN)
- Sample images/videos are included in the respective experiment folders or can be downloaded from public datasets (e.g., COCO for object detection).

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/Computer-Vision.git
   cd Computer-Vision
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
   (Create a `requirements.txt` file with the above libraries if not already present.)

## Usage
Each experiment is in its own folder (e.g., `experiment-1/`, `experiment-2/`, etc.). Navigate to the folder and run the main script:
```
python main.py
```
- Input images are provided in the folders or can be replaced with your own.
- Outputs (enhanced images, detections, etc.) will be displayed or saved in the output directory.

## Contributing
Feel free to fork this repository and submit pull requests for improvements, bug fixes, or additional experiments.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Based on the syllabus from Nagar Yuwak Shikshan Sanstha’s Yeshwantrao Chavan College of Engineering (Department of Computer Technology).
- Inspired by open-source Computer Vision resources like OpenCV documentation and research papers on YOLO, R-CNN, etc.

For any questions, contact siddheshpitale16@gmail.com
