# Text Summarization

This repository contains tools and techniques for text summarization. It leverages advanced natural language processing (NLP) methods to generate concise and meaningful summaries of textual content. The project is designed for researchers, developers, and enthusiasts looking to experiment with or implement text summarization models.


## Dataset

The dataset used for training and evaluation is located in the `data` directory.

## Installation

To set up the project environment, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/farukaplan/Text-Summarization
   cd Text-Summarization
   ```

2. **Create a virtual environment** (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

The main implementation is provided in the Jupyter Notebook `text_summarization.ipynb`. To run the notebook:

1. **Ensure Jupyter is installed**:

   ```bash
   pip install jupyter
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

3. **Open and execute** the `text_summarization.ipynb` notebook to train and evaluate the model.
4. Beware, since we developed this project on Google Colab, file path to dataset may vary, you may need to adjust it accordingly

## Results

The model's performance is evaluated using ROUGE metric. Detailed results, including training and validation accuracy and loss curves, are documented in the `text_summarization_report.pdf` file.

## Contributing

Contributions to enhance the project are welcome. To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## Contributors
This project is developed by Faruk Kaplan and [Mert Altekin](https://github.com/AltekinMert)

## Video
If you prefer to watch video to understand the code, you can visit following YouTube video: [https://youtu.be/o95-X_zDRkU](https://youtu.be/cpD72_WR6KU?feature=shared)
