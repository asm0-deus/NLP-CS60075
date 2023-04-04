# NLP PROJECT- EVENT EXTRACTION
### Hyperparameters:
- batch_size = 3
- epochs = 1
- learning_rate = 1e-5
- max_seq_length = 490
- num_warmup_steps = 0
- num_training_steps = 9273


### Deep Learning Libraries and Tools Used:
- BertTokenizer
- BertForSequenceClassification
- Pytorch
- Tenserflow
- Numpy
- Pandas
- Joblib

### Model details
- Model used: BertForSequenceClassification.from_pretrained("bert-base-uncased",num_labels=25)
- Input: 30522 word embeddings
- Output: 25 output features
- Hidden Layers: 10 
- Parameters: 768 in each hidden layer
