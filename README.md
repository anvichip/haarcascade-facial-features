# Eye and Mouth Detection using Haar Cascades

This project demonstrates the detection of eyes and mouth using Haar cascades in OpenCV. The code is designed to run on Google Colab, making it easy to execute and experiment with.

## Setup

To run this code, follow the steps below:

1. Open Google Colab: Go to [Google Colab](https://colab.research.google.com) in your web browser.

2. Create a new notebook: Click on "New Notebook" to create a new Colab notebook.

3. Import the notebook: Copy and paste the code from [detect_eyes_and_mouth.ipynb](detect_eyes_and_mouth.ipynb) into the newly created Colab notebook.

4. Upload the required XML files: Upload the `haarcascade_frontalface_default.xml`, `haarcascade_eye.xml`, and `haarcascade_mcs_mouth.xml` files to your Colab session. These XML files contain the pre-trained models for face, eye, and mouth detection respectively.

5. Run the code: Execute the code cells in the Colab notebook to run the eye and mouth detection algorithm on the provided image.

## Usage

To use this code on your own images, follow these steps:

1. Prepare your image: Make sure you have an image file (.png, .jpg, etc.) that you want to perform eye and mouth detection on.

2. Modify the code: Update the `image_path` variable in the code to point to the path of your image file.

3. Run the code: Execute the code cells in the Colab notebook to run the eye and mouth detection algorithm on your image.

4. View the results: The code will display the image with detected eyes and the largest non-overlapping mouth. The coordinates of the eyes and non-overlapping mouths will also be printed.

## Dependencies

The following dependencies are required to run the code:

- OpenCV: `pip install opencv-python`
- Google Colab: No additional installation required as it comes with pre-installed libraries.

## License

This project is licensed under the [MIT License](LICENSE).
