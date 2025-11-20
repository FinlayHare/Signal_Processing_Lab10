# Signal_Processing_Lab10

This MATLAB script demonstrates an image enhancement technique for low-light photography using a pre-trained deep learning network. The script simulates a low-light imaging scenario and uses a specialized neural network to restore image quality.

1. Preparation -	Download pretrained model	- Creates a temporary directory and downloads a low-light image enhancement neural network
2. Network Loading -	Load pre-trained neural network	- Loads the network from a downloaded .MAT file
3. Image Input	- Prepare reference image	- Reads an RGB image and resizes it to 512x512 pixels
4. Image Degradation -	Simulate low-light conditions	- Dramatically reduces image brightness and adds Gaussian noise
5. Input Preprocessing -	Create fake RAW input	- Converts image to grayscale and replicates into 4 channels
6. Network Preparation	- Format input	- Wraps input as a deep learning array, with optional GPU acceleration
7. Enhancement	- Run neural network	- Predicts and enhances the low-light image
8. Output Processing	- Convert results	- Converts network output back to a standard image format
9. Visualization	- Display results	- Shows original, low-light, and enhanced images side by side
    
<img width="2162" height="758" alt="Screenshot 2025-11-20 at 10 45 39" src="https://github.com/user-attachments/assets/605cf19f-b0a0-497e-aee9-e96776334f7a" />
