
# Neural Style Transfer




## Project Overview
This project implements Neural Style Transfer (NST) using TensorFlow and Keras and provides a user-friendly interface using Streamlit. Neural Style Transfer is a deep learning technique that allows blending the content of one image with the style of another image, resulting in visually appealing artworks.

The core idea behind NST is to separate and then recombine the content and style of two input images using convolutional neural network, typically VGG19.
## Installation Instructions
#### To set up the environment and run the project, follow these steps:
1. Create a folder named "style-transfer" on your Google Drive.
2. Download the "App.ipynb" file from the provided code section and upload it to the "style-transfer" directory on your Google Drive.
3. Open the "App.ipynb" file using Google Colab, ensuring that Google Colaboratory is installed on your Google Drive.
4. From the top-right dropdown menu in Google Colab, select "Change runtime type" and choose "T4 GPU" for optimal processing capabilities.
5. No additional dependencies need installation as they are pre-installed in Google Colab.
## Usage
#### To use the code, follow these steps:
1. Execute the code by pressing Ctrl + F9 to initiate the process.
2. A Google Drive authentication window will prompt for access to files in your Drive. Proceed by logging into your Google Drive account.
3. Capture the IP address displayed in the cell output. Navigate to the URL provided in the cell output, opening a new window.
4. Paste the previously copied IP address into the designated  tunnel password field to proceed with the operation.
5. Upload the files using the file upload buttons to upload a content image and a style image.
6. After uploading both images, click the "Style" button to apply Neural Style Transfer.
7. Allow the process to complete execution. The styled image will appear within the application interface and will be automatically saved in the designated "style-transfer" folder.
8. Navigate to the "style-transfer" folder. Refresh the directory to display the newly generated "stylised_image.png."
9. Link to Demo video:
## Dependencies
The project relies on the following Python libraries and dependencies:
- [Streamlit](https://streamlit.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [NumPy](https://numpy.org/)
- [PIL (Python Imaging Library)](https://pillow.readthedocs.io/en/stable/)
- [Matplotlib](https://matplotlib.org/)

## References
- Understanding Concept : [YouTube](https://youtu.be/ZObZRgyZ3Ig?si=EkWTkXlcAlSn-C0X)
- Writing Code: [Neural Style Transfer](https://keras.io/examples/generative/neural_style_transfer/#image-preprocessing--deprocessing-utilities)
- Front End Ideation: [YouTube - Front End Ideation](https://youtu.be/M3lZNbFJ6I0?si=FgIghyEkrTRIUd-D)
- Streamlit Documentation: [Streamlit Documentation](https://docs.streamlit.io/)
- TensorFlow Documentation: [TensorFlow Guide](https://www.tensorflow.org/guide)

## Important 
Running the code on a GPU is essential to ensure efficient processing. Failure to utilize GPU acceleration may result in significantly extended processing times beyond expectations.
