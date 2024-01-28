# DeepFake

This model, based on deep learning techniques, allows for various transformations and animations of images and videos referenced from First Order Model Demo repository.

## Summary

The program demonstrates the following functionalities:

1. **Image Animation**: Users can upload or select images and videos to animate the uploaded image according to the movements in the selected video.
2. **Video Generation**: Users can upload or select videos to generate new videos based on the movements in the uploaded video.
3. **Settings Configuration**: Users can configure various settings such as model selection, relative keypoint displacement, and movement scale adaptation.
4. **Output Comparison**: The generated output can be compared side by side with the original input video.

## Usage

1. **Environment Setup**: Ensure all the required dependencies are installed in your Python environment.
2. **Execution**: Execute the provided code cells in the notebook.
3. **Input Selection**: Choose an image and video to manipulate and configure the desired settings.
4. **Generation**: Click on the "Generate" button to initiate the processing.
5. **Download**: Once the processing is complete, download the generated output for further use.

## Dependencies

- `IPython.display`
- `PIL.Image`
- `cv2`
- `imageio`
- `io`
- `ipywidgets`
- `numpy`
- `os.path`
- `requests`
- `skimage.transform`
- `warnings`
- `base64.b64encode`
- `demo` (custom module, possibly developed or obtained separately)
- `ffmpy`
- `google.colab.files`
- `google.colab.output`
- `IPython.display.HTML`
- `IPython.display.Javascript`
- `skimage.img_as_ubyte`

## Note

Ensure that all required files and directories (`demo`, `config`, etc.) are present in the appropriate locations relative to the notebook file for the program to function correctly.

