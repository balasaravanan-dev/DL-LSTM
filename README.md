# DL- Developing a Deep Learning Model for NER using LSTM

## AIM
To develop an LSTM-based model for recognizing the named entities in the text.

## Problem Statement and Dataset


## DESIGN STEPS
### STEP 1: 

Load data, create word/tag mappings, and group sentences.

### STEP 2: 

Convert sentences to index sequences, pad to fixed length, and split into training/testing sets.

### STEP 3: 

Define dataset and DataLoader for batching.

### STEP 4: 

Build a bidirectional LSTM model for sequence tagging.

### STEP 5: 

Train the model over multiple epochs, tracking loss.

### STEP 6: 

Evaluate model accuracy, plot loss curves, and visualize predictions on a sample.



## PROGRAM

### Name:

### Register Number:

```python
class BiLSTMTagger(nn.Module):
    # Include your code here







    def forward(self, input_ids):
        # Include your code here
        


model = 
loss_fn = 
optimizer = 


# Training and Evaluation Functions
def train_model(model, train_loader, test_loader, loss_fn, optimizer, epochs=3):
    # Include the training and evaluation functions



    return train_losses, val_losses


```

### OUTPUT

## Loss Vs Epoch Plot

Include your plot here

### Sample Text Prediction
Include your sample text prediction here

## RESULT
Thus, an LSTM-based model for recognizing the named entities in the text has been developed successfully.
