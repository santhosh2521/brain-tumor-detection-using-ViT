# Brain-tumor-detection-using-ViT

Welcome to the Brain Tumor Detection project using Vision Transformer (ViT)! This project aims to detect brain tumors using ViT, a transformer-based architecture originally designed for image classification tasks.

## Getting Started

Follow these steps to get started with the project:

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/your_username/brain_tumor_detection.git
```

### 2. Open vit3.ipynb
Open the vit3.ipynb notebook in your preferred Python environment. This notebook contains the code which runs for brain tumor detection using ViT.

### 3. Install Dependencies
Before running any code blocks, make sure to install the required dependencies. Run the following command in a code cell:

```bash
!pip install tensorflow scikit-learn
```

### 4. Transfer the Data Folder to drive

Add the data folder to your Google Drive.

### 5. Mount Google Drive on Google Colab

To mount your Google Drive on Google Colab, follow these steps:

1. Run the following code block in Google Colab:

    ```bash
    from google.colab import drive
    drive.mount('/content/drive')
    ```
2. Follow the link provided and authenticate with your Google account.
3. Copy the authentication code and paste it into the designated area.

### 6. Navigate to Content Directory

Navigate to the content directory in Google Colab:
```bash
%cd /content
```

### 7. Paste vit.py and utils.py
Upload the vit.py and utils.py in Google Drive first.

Upload vit.py and utils.py files to Google Colab. Then, move them to the content directory using the file manager or the following command:

```bash
!mv /content/drive/your_path/vit.py /content
!mv /content/drive/your_path/utils.py /content
```
Replace your_path with the actual path to the files in your Google Drive.

or 

directly drag and move the files from local storage to the content folder

### 8. Run Code Blocks

Now, you are all set to run the code blocks in vit3.ipynb one by one. Follow the instructions within the notebook for each code block.


