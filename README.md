# Image Classification with GPT-4o

This program uses GPT-4o's vision capabilities to classify images into predefined categories. It processes images from a specified folder and outputs the classification results to a CSV file.

## Setup and Usage

### 1. Environment Setup

To run the program, you need to set up a few things:

#### Create a `.env` File

1. Create a file named `.env` in the root folder of the project.
2. Add your OpenAI API key to the `.env` file with the following format:

    ```plaintext
    OPENAI_API_KEY=your_openai_api_key_here
    ```

   Replace `your_openai_api_key_here` with your actual OpenAI API key. Make sure to keep this file secure and do not share it publicly.

#### Create the Images Folder

1. In the same root folder where the script is located, create a folder named `images`.
2. Place the images you want to classify into this `images` folder. Supported image formats include `.jpg`, `.jpeg`, `.png`, `.gif`, and `.jfif`.

### 2. Installation

You need to have Python and the required packages installed. If you haven't already, install the required packages using pip:

```bash
pip install requests python-dotenv

### 3. Running the Program

1. Ensure that your `.env` file is correctly set up with your OpenAI API key.
2. Place the images you want to classify in the `images` folder.
3. Run the script using Python:

    ```bash
    python script_name.py
    ```

   Replace `script_name.py` with the actual name of your Python script file.

### 4. Output

The program will create a CSV file named `classification_results.csv` in the root folder of the project. This file will contain the classification results for each image processed. The CSV file will have two columns:

- **Image**: The name of the image file.
- **Classification**: The category assigned to the image by GPT-4o.

