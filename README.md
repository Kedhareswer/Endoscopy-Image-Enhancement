# Medical Image Enhancement Web Application

This web application provides a user-friendly interface for enhancing medical images using advanced AI models. It supports both image and video enhancement with real-time processing capabilities.

## Features

- **Image Enhancement**: Upload and enhance medical images using SRCNN and UNet models
- **Edge Detection**: Visualize and compare edges in original and enhanced images
- **Video Enhancement**: Process video files or use webcam for real-time enhancement
- **Frame Capture**: Capture and enhance specific frames from videos
- **Performance Metrics**: View PSNR and SSIM metrics to evaluate enhancement quality

## Models

The application uses two deep learning models:

1. **SRCNN (Super-Resolution Convolutional Neural Network)**
   - Designed for image super-resolution
   - Architecture: 3 convolutional layers with ReLU activation

2. **UNet**
   - Originally designed for biomedical image segmentation
   - Architecture: Encoder-decoder with skip connections
   - Effective for preserving spatial information

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kedhareswer/Endoscopy-Image-Enhancement.git
   cd Endoscopy-Image-Enhancement
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

## Usage

### Image Enhancement

1. Navigate to the "Image Enhancement" tab
2. Upload an image by dragging and dropping or clicking "Browse Files"
3. View the enhanced image, edge detection results, and performance metrics

### Video Enhancement

1. Navigate to the "Video Enhancement" tab
2. Upload a video file or enable webcam
3. Use the video controls to play/pause and capture frames
4. View enhanced frames in the "Captured Frames" section

## Requirements

- Python 3.7+
- Flask
- PyTorch
- OpenCV
- NumPy
- Pillow
- scikit-image

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- SRCNN model architecture by Chao Dong et al.
- UNet model architecture by Olaf Ronneberger et al.