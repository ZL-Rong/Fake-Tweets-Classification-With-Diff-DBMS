# Training BERT-Fake-Tweets-Classification Model with MYSQL, PostgreSQL and Neo4j, and comparing their performance of training process

## Required Libraries
1. conda install -c huggingface transformers
2. conda install -c pytorch pytorch
3. conda install -c anaconda flask
4. conda install -c anaconda jinja2
5. conda install -c anaconda numpy
6. conda install -c anaconda mysql-connector-python
7. conda install -c anaconda psycopg2
8. pip install neo4j

## Training the model
1. run training_model.py
OR
2. run training_model_db.py

## Running the flask server
1. python app.py
2. access the local server: http://127.0.0.1:5000/

## Acknowledge
1. Huggingface bert-base-cased: https://huggingface.co/bert-base-cased
2. Datasets: https://github.com/prathameshmahankal/Fake-News-Detection-Using-BERT/tree/main/data
3. BERT Paper Reference: https://arxiv.org/abs/1810.04805
4. Frontend Reference: https://github.com/ac4mm/Fake-Detector
