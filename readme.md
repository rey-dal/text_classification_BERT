## Text Classification | BERT

Machine learning project : News classification with BERT - pretrained state of art model.

Trained & Tested on data AG News 

-brt-arc > references > architectures.ipynb : Bag-of-Words(BOW), TF-IDF, RNN models, Transformer, self attention with encoder & decoder, BERT

-src > 
- `ML_Pipeline`: modules w/function declarations for various ML tasks.
- `engine.py`: The core, all function calls.

## Data Description

The AG News dataset, classes: "World," "Sports," "Business," and "Sci/Tech" 

---

## Installation

1. Install the required packages specified in the `requirements.txt` file.

   For Anaconda:
   ```bash
   conda create --name <yourenvname>
   conda activate <yourenvname>
   pip install -r requirements.txt
   ```

   For Python Interpreter:
   ```bash
   pip install -r requirements.txt
   ```

2. Within `src`: Run/Debug the `engine.py` file, and the necessary steps will be automated according to the defined logic.

3. Input datasets are stored in the `input` folder.

4. Predictions and models are saved in the `output` folder.

---
