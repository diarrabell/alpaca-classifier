# Alpaca Classifier using CreateML

This project uses a binary classification model to distinguish between alpacas and animals that are not alpacas. The model was developed in CreateML using training data from this Kaggle dataset: ["Alpaca Dataset for Image Classification"](https://www.kaggle.com/datasets/sid4sal/alpaca-dataset-small). 

## Data
The original dataset consists of 142 "Alpaca" images and 185 "Not alpaca" images. I used approximately 80% of each category for training and approximately 20% for testing. 
<img width="1151" alt="Screenshot 2023-07-02 at 7 36 19 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/960c71fe-2d2e-4cf0-a851-aa80369bcfdd">

## Training 
The model was trained over 25 iterations on 259 images, resulting in a training accuracy and validation accuracy of 99.1%.

<img width="1130" alt="Screenshot 2023-07-02 at 7 35 51 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/0f24b2e9-db20-4281-be9a-18e3cf30469a">

## Evaluation
The model was evaluated on 68 images from the test dataset. The test data's metrics show high precision and recall scores, with only one false negative and one false positive reported.
<img width="894" alt="Screenshot 2023-07-02 at 7 35 10 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/84a942e6-945e-4219-97fa-d0d50dc91d16">


## Testing
Overall, the model is able to accurately recognize the difference between alpacas and other images. Here are some examples:

<img width="578" alt="Screenshot 2023-07-02 at 7 33 32 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/2b43dc7b-5aef-41ae-a97a-801d353540b3">
<img width="578" alt="Screenshot 2023-07-02 at 7 34 23 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/cc770753-f8c2-416c-9dc5-519a90ceb9f1">

To test the project for yourself, open the Alpaca Classifier in Xcode.
