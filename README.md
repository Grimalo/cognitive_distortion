# Identification of Cognitive Distortions through the Analysis of Situations & Associated Feelings

## Project Description
This study explores a multilabel classification model based on BERT (Bidirectional Encoder Representations from Transformers) for identifying cognitive distortions in textual data. Cognitive distortions, such as personalization and overgeneralization, negatively impact mental health. The model was trained and validated on an annotated dataset to classify twelve different cognitive distortions.

The methodology included balancing class distribution, tokenizing texts with BERT's tokenizer, and converting labels to a binary format for multilabel classification. The modified BERT model was trained and evaluated using precision, recall, and f1-score metrics for each label, as well as overall accuracy. 

The model achieved an overall accuracy of 51.4% on the test set and 50.5% on the validation set. It performed best in the "No distortion" and "Blaming" categories. However, it struggled with "Overgeneralization" and "Personalization," indicating a need for further optimization and more training data. The project was developed using Python in Google Colab.

## Repository Structure


Paper: [https://www.overleaf.com/project/665b79335705676605dade53](https://www.overleaf.com/read/drwfyyvfxmjh#da61a7)
