# Crisis Social Media Classification (Vision-Language)

This project contains code and resources for **classifying crisis-related social media posts** using both text and images (vision-language AI). The goal is to automatically categorize posts into:

- **Urgent Help**
- **Relief Info**
- **Misinformation**
- **Irrelevant**

## Features

- Multimodal classification: combines image and text for better accuracy
- Notebook: `crisis-social-media-classification-visionlanguage.ipynb`
- Example data and visualization scripts

## Usage

1. Clone the repo or download the notebook.
2. Open and run `crisis-social-media-classification-visionlanguage.ipynb` in Jupyter or Colab.
3. Prepare your dataset in CSV format:
    - Each row: `text, image_path, label`
4. Update notebook paths as needed and run all cells.

## Requirements

- Python 3.8+
- torch
- transformers
- pandas
- PIL
- scikit-learn
- tqdm

## Dataset Example

```csv
text,image_path,label
Help! Flooding everywhere!,images/img001.jpg,Urgent Help
Distribution of relief supplies ongoing,images/img002.jpg,Relief Info
