
## Project Overview
This project implements Named Entity Recognition (NER) using the BERT model. We use the `simpletransformers` library to fine-tune a pre-trained BERT model on a custom NER dataset, classifying words into categories like person names, organizations, locations, and more.

## Setup Instructions
To set up the project and install the required packages, follow these steps:
`pip install -r requirements.txt`

### Prerequisites
Make sure you have Python 3.x and `pip` installed on your system. You can check if you have them installed by running:

```bash
python --version
pip --version


**Note:** You can install the dependencies using: 'requirements.txt' file provided


## Dataset
The dataset used is a custom NER dataset provided in CSV format with columns:
- `sentence_id`: Unique identifier for sentences.
- `words`: The words in each sentence.
- `labels`: The named entity labels corresponding to each word.

## Model Training
To Train the selected models execute the below programs:
BERT Model: Execute file '01.NER_BERT_Training_F1.ipynb'
CRF Model : Execute file '02.NER_CRF_Training_F1.ipynb'

  
## Model Testing
To Train the selected models execute the below programs:
BERT Model: Execute file '01.NER_BERT_Chatbot_F1.ipynb'
CRF Model : Execute file '02.NER_CRF_Chatbot_F1.ipynb'


