# Label Prediction Using LSTM Based Models
The repository consists of notebooks and data files created as a part of the prediction process.

## Files
- <b>data/train_combined_imbalanced.csv</b> - Consists of imbalanced set of Question, Answer and Labels, of shape (2405, 3). The data was combined from "data/Q&A dataset with label - 05 04.csv" and "data\Q&A dataset with label - 1502-subtopics with comments (2).csv"
- <b>data/train_balanced_labels.csv</b> - Consists of balanced set of Question, Answer and Labels, of shape (2000, 3) with each label consisting of 400 records. The split was done from "data/train_combined_imbalanced.csv" file<br><i>NOTE: The data is in ordered format. Kindly, consider shuffled and unshuffled data for training the models to compare the performance.</i> 
- <b>data/validation.csv</b> - Consists of imbalanced set of Question, Answer and Labels, of shape (405, 3), with the remaining data from "data/train_combined_imbalanced.csv" file after splitting "data/train_balanced_labels.csv" file.
- <b>data/inference_from_8606.csv</b> - Consists of Question, Answer and Labels, of shape (300, 3). The labels were defined by subjective definition.