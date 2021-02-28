# imbd-sentiment-analysis

This is a sentiment analysis model trained on IMDB movies textual reviews.
The resulting model will take as input a review from a simple web form and give a positive or negative output response.

The project is based on the following components:
* A PyTorch based Deep Neural Network model to predict sentiment from a review,
* An AWS Lambda server to execute on demand a code snippet that will provide data to the model endpoint,
* AWS API Gateway to gather data from a web page through a restful API **,
* A simple web page to input data.
Two models were designed in the project, the second one is intended to improve initial performance.
The items above marked with ** are not described in detail or contained into the project repository.

# Files

NegativeReviewExample.png\
PositiveReviewExample.png\
SageMaker Project.ipynb\
Web App Diagram.svg\
serve/model.py\
serve/predict.py\
serve/requirements.txt\
train/model.py\
train/model_new.py\
train/train.py\
train/train_new.py\
train/requirements.txt\
website/index.html
