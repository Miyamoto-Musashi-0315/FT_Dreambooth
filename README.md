# Artistic-Focused Fine-tuning

This project processes images and text to train or generate models using Stable Diffusion. It builds upon concepts demonstrated in [Hugging Face’s Dreambooth Training Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/sd_dreambooth_training.ipynb) and [Stable Diffusion Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb). The code and methodology are inspired by these sources and are tailored to this project.

For more details on the project, please visit [this page](https://sites.google.com/view/01fe20bec260genai/home?authuser=0).


Follow the steps below to set up, create the dataset, and run the code.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the ipynb file and start running cells

## Dataset Preparation

To run this project, you need to prepare a dataset of images and corresponding text files for captions.

1. Create a folder to store the dataset (e.g., `dataset/`).
2. Place image files in `.png`, `.jpg`, or `.jpeg` format inside the folder.
3. For each image file, create a corresponding text file with the same name as the image file. For example:
   - `1.jpg` and `1.txt`
   - `example.png` and `example.txt`
4. The `.txt` file should contain a single line of text representing the caption or description of the image.

## Running the Code

1. Open the provided Jupyter Notebook (`FT_drmbth.ipynb`) in your preferred editor (e.g., Jupyter Notebook, Jupyter Lab, or VS Code).
2. Ensure the dataset folder path is correctly specified in the notebook.
3. Execute the cells in the notebook sequentially.

This code provides a great idea of how Stable Diffusion works and how to train and generate models. It utilizes principles from [Hugging Face's Stable Diffusion Notebook](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/stable_diffusion.ipynb) for the generation process.

## Notes

- The captions in the `.txt` files should match the images to improve model accuracy.
- If additional dependencies are required, install them manually.
- The notebook demonstrates how to leverage Stable Diffusion models for generating and modifying images based on text descriptions.

## Contributing

Feel free to submit issues or pull requests for enhancements or bug fixes.


