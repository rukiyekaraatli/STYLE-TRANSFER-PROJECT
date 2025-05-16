STYLE TRANSFER PROJECT

This project aims to apply different styles, such as the Ghibli style, to images using a style transfer model from TensorFlow Hub.

Technologies Used

* **TensorFlow:** An open-source library for machine learning and deep learning tasks.
* **TensorFlow Hub:** A platform to discover, publish, and reuse pre-trained machine learning model parts (modules). This project utilizes the `google/magenta/arbitrary-image-stylization-v1-256` model.
* **PIL (Pillow):** A Python Imaging Library. It's used for loading, resizing, and saving images.
* **NumPy:** A fundamental library for numerical operations in Python. It's used to convert image data into numerical arrays.
* **Matplotlib:** A data visualization library in Python. It's used to display the result of the style transfer.
* **Google Colab files module:** Used for file uploading and downloading operations within the Colab environment.

Setup and Usage

1.  **Run this project in a Google Colab notebook.**
2.  The necessary libraries will be installed automatically.
3.  Navigate to the "**File Upload**" section and upload the content image you want to stylize and the style image you want to apply.
4.  Run the code cells sequentially.
5.  Once the "**Performing Style Transfer**" section is complete, the resulting image will be displayed.
6.  The resulting image will be saved as `result.jpg` and can be downloaded from the "**Saving Results**" section.

Project Structure

The project is organized as a Google Colab notebook and includes the following main sections:

* **Loading Libraries:** The section where the necessary Python libraries are imported.
* **Loading the Model and Defining Functions:** The section where the TensorFlow Hub model is loaded and image processing functions (image loading and style transfer) are defined.
* **File Upload:** The section where the content and style images for style transfer are uploaded.
* **Performing Style Transfer:** The section where style transfer is applied to the uploaded images and the result is displayed.
* **Saving Results:** The section where the style transfer result is saved to a file and downloaded.
