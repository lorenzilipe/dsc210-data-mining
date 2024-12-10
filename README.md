# Project: Movie Recommender System
### Course: DSC 210: Numerical Linear Algebra
#### Instructor: Dr. Tsui-wei Weng
#### Project Members: Joshua Chuang, Joyce Hu, Felipe Lorenzi, Ryan Clement

#### Instructions:
* Ensure that the following libraries are installed in python 3 environment:
  - surprise
  - recommenders
  - matplotlib
  - seaborn

* Run `EDA.ipynb` to see eda analysis of MovieLens 1m Dataset
* Run `SVD_final.ipynb` to run SVD model
* To run `sota_model_training.ipynb`, import notebook into Kaggle and run using GPU T4 x2 accelerator. Once cells are run, save the trained models `.pth` files that should be under `/kaggle/working/saved`.
  - Notebook trains state of the art models NeuMF and BERT4Rec
  - Current runtimes: NeuMF ~30 min, BERT4Rec ~2 hours
  - Our pretrained models can be downloaded [here](https://drive.google.com/drive/folders/1UFe74OeRqQpH730OVVGdybwMyOA_lCPY?usp=sharing)
* To run `sota_model_results.ipynb`, open notebook in Collab and run using T4 GPU. Upload the trained models `.pth` files.

#### Results:
|  | SVD | NeuMF | BERT4Rec |
| -------- | ------- | -------- | ------- |
| RMSE | 0.888 | 0.995 | 2.961 | 
| Precision@10 | 0.074 | 0.202 | 0.0241 |
| Recall@10 | 0.026 | 0.164 | 0.241 |

![model_metrics_graph](https://github.com/user-attachments/assets/431008fe-b436-4e0a-ac5d-46ee4e9a9f58){ width=50% }

#### Project Report:
Project report can be found [here]()
