# VR-Game-Review-Immersion-BERT-Model
Code and pre-trained BERT model for detecting immersion in VR game reviews.

This repository provides Python scripts and pre-trained BERT models for detecting immersion-related content in VR game reviews. The project includes two main functionalities:

Calculating the immersion-related probability for a single review.
Processing an Excel file to calculate immersion-related probabilities for all reviews in the text column.
Download Files
All necessary files, including the Python scripts and pre-trained BERT model, can be downloaded from OneDrive:
Download from OneDrive https://tuni-my.sharepoint.com/:f:/g/personal/xiaohang_deng_tuni_fi/EuvoshtTUyVDrhpAgzrIkY8B65jpKR2ovLCTpfYRoX88kw?e=hf6VMW

Please ensure the files are placed in the same directory as the scripts for proper execution.

Setup and Installation
Clone the repository
Clone this repository to your local machine:
git clone https://github.com/yourusername/VR-Game-Review-Immersion-BERT-Model.git

Install dependencies
Install the required Python libraries using requirements.txt:
pip install -r requirements.txt

requirements.txt
torch
transformers
pandas
numpy
scikit-learn
tqdm
openpyxl
matplotlib

Usage
Single Review Classification
To calculate the immersion probability for a single review, use the single_review.py script. Example:
python single_review.py "This VR game provides an immersive experience!"

The script will output the immersion probability for the input review text.

Batch Review Classification (Excel File)
To calculate immersion probabilities for an entire set of reviews stored in an Excel file, use the batch_review.py script. Make sure to place the Excel file (test data.xlsx) in the same directory as the script.
python batch_review.py

This will generate a new Excel file (output.xlsx) with a calculated immersion probability for each review in the "text" column.

License
This project is licensed under the MIT License - see the LICENSE file for details.
