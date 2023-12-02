# Deep Learning Detection System in Chest Radiography for Lung Diseases

This project implements a Deep Learning Detection System for lung diseases in chest radiography. The system is developed using TensorFlow and consists of an ensemble of Convolutional Neural Networks (CNNs) including ResNet50, VGG16, and InceptionV3. Additionally, a graphical user interface (GUI) is developed using Flask, allowing users to upload chest X-rays and receive predictions on potential lung diseases.

## Key Features

- Ensemble of CNN models (ResNet50, VGG16, InceptionV3)
- Graphical User Interface (GUI) with Flask
- Prediction of lung diseases in chest X-rays
- Evaluation using confusion matrices for individual models and ensemble model

## Dataset

The dataset used for training and testing is obtained from Kaggle:

[Kaggle Chest X-ray Dataset](https://www.kaggle.com/datasets/jtiptj/chest-xray-pneumoniacovid19tuberculosis)

## Ensemble Model Structure

The ensemble model is structured by combining the outputs of three individual CNN models: ResNet50, VGG16, and InceptionV3. The diagram below illustrates the architecture of the ensemble model.

![ensemble](https://github.com/namrahrehman/Project00/assets/93483806/66ca7be4-345f-4e7e-ae2b-3bd213341cbb)

## Individual Model Confusion Matrices
### ResNet50 Confusion Matrix
![Resnet50_Results](https://github.com/namrahrehman/Project00/assets/93483806/c12a6b23-b647-499c-9a52-0c5bbc366860)

### VGG16 Confusion Matrix
![vgg](https://github.com/namrahrehman/Project00/assets/93483806/a7c28fd5-912b-4215-839e-4c8b4ed696af)

### InceptionV3 Confusion Matrix
![inception](https://github.com/namrahrehman/Project00/assets/93483806/62507b8e-c46e-46cc-93c2-d1cf741e1fcc)

## Ensemble Model Confusion Matrix

### Ensemble Confusion Matrix
![ensemble](https://github.com/namrahrehman/Project00/assets/93483806/9d044356-8b1a-4a0a-8cfa-14bd4a8039f1)

## GUI 
![Screenshot (39)](https://github.com/namrahrehman/Project00/assets/93483806/314f83a2-f93e-44a4-9e87-3b9aaac1da1d)
![Screenshot (38)](https://github.com/namrahrehman/Project00/assets/93483806/688e221c-9e05-429f-b712-9d40c436cefc)
![Screenshot (40)](https://github.com/namrahrehman/Project00/assets/93483806/106e0618-f271-4617-911a-2257947fe68b)
![Screenshot (36)](https://github.com/namrahrehman/Project00/assets/93483806/6308dad8-990e-4b9a-b46e-3c4b2151adbe)
![Screenshot (37)](https://github.com/namrahrehman/Project00/assets/93483806/c354337d-fa2e-4a39-92db-0bd1d33e300d)
![Screenshot (34)](https://github.com/namrahrehman/Project00/assets/93483806/a8881275-b714-4d08-82cb-a225ef71cc56)
![Screenshot (35)](https://github.com/namrahrehman/Project00/assets/93483806/6b99caad-b24f-4ad9-917f-e18c00517fef)


## How to Use

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yourusername/your-repo.git](https://github.com/namrahrehman/Project00)
   
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

4. **Run the Flask App**
   ```bash
   python app.py

