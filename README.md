# final_project
## Reproducing Submission:
1.instal requirements package  
2.Download [kaggle data](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/data)  
3.Download [Pre-train models](https://github.com/kirito878/final_project/blob/main/README.md#5pre-trained-models)    
4.[Inference](https://github.com/kirito878/final_project#4inference)  
5.Make submission
## 1.Requirements

To install requirements:

```setup
pip install -r requirements.txt
```
## 2.Code
all code are in the [src](https://github.com/kirito878/final_project/tree/main/src)

## 3.Training
To train the model , use [train.ipynb](https://github.com/kirito878/final_project/blob/main/src/train.ipynb)  

## 4.Inference
To evaluate my model , please use [inference.ipynb](https://github.com/kirito878/final_project/blob/main/src/inference.ipynb)  
if you want to evalutae some specific model , please uncomment correspond cell , or it will use the best model (default)
## 5.Pre-trained Models
all pre-trained models are in the [model](https://github.com/kirito878/final_project/tree/main/model)  
1.[Logistic regression](https://github.com/kirito878/final_project/blob/main/model/logisticRegression.pickle)  
2.[AdaBoost](https://github.com/kirito878/final_project/blob/main/model/AdaBoostClassifier.pickle)  
3.[Elastic net](https://github.com/kirito878/final_project/blob/main/model/elasticNet.pickle)  
4.[Elastic net cv](https://github.com/kirito878/final_project/blob/main/model/elasticNetCV.pickle)  
5.[xgboost](https://github.com/kirito878/final_project/blob/main/model/XGBClassifier.pickle)  
6.[lightgbm](https://github.com/kirito878/final_project/blob/main/model/model.txt)
## 6.Results

my model result :

| Model name         | Private Score  | 
| ------------------ |---------------- |
| Logistic regression|     0.58987     | 
| AdaBoost            |     0.57345    | 
| Elastic net         |     0.59006    | 
| Elastic net cv    |     0.59007       | 
| xgboost           |     0.58082      | 
| lightgbm          |     0.58594        | 
