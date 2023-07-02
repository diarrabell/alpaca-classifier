# Alpaca Classifier using CreateML

This project uses a binary classification model to distinguish between alpacas and animals that are not alpacas. The model was developed in CreateML using training data from this Kaggle dataset: ["Alpaca Dataset for Image Classification"](https://www.kaggle.com/datasets/sid4sal/alpaca-dataset-small). 

## Data
The original dataset consists of 142 "Alpaca" images and 185 "Not alpaca" images. I used approximately 80% of each category for training and approximately 20% for testing. 

<img width="875" alt="Screenshot 2023-07-02 at 7 07 29 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/44ba9332-b3ac-4567-a81f-c719a0fa9e94">

## Training 
The model was trained over 25 iterations on 259 images, resulting in a training accuracy and validation accuracy of 99.1%.
<img width="873" alt="Screenshot 2023-07-02 at 7 10 59 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/12fa833f-53c8-44ae-b0f0-0d644a63d47f">

## Evaluation
The model was evaluated on 68 images from the test dataset. The test data's metrics show high precision and recall scores, with only false negative and one false positive reported.
<img width="928" alt="Screenshot 2023-07-02 at 7 18 39 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/cdb59c35-4b56-40ce-add2-005beb30b5af">

## Testing
Overall, the model is able to accurately recognize the difference between alpacas and other images. Here are some examples:
<img width="578" alt="Screenshot 2023-07-02 at 7 27 32 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/7e70751a-df6d-40d4-971e-ae781dee921e">
<img width="578" alt="Screenshot 2023-07-02 at 7 28 46 PM" src="https://github.com/diarrabell/alpaca-classifier/assets/36339346/cb23855f-4257-4a76-a022-d3d0a207e08a">

To test the project for yourself, open the Alpaca Classifier in Xcode.
