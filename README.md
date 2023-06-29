# RECOMMENDER SYSTEM

## Description
Predict unknown ratings and recommend movies to users based on a dataset of users and movies


## Getting Started

### Dependencies
* Python
* Pandas
* Numpy
* sklearn
* matplotlib


### Result
| K = 30 | RMSE | MAE | Precision | Recall | F1 | MAP | NDCG |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Content-based](src/Content_based.ipynb) | 1.03 | 0.91 | 0.63 | 0.59 | 0.58 | 0.73 | 0.77 |
| [User-User](src/User_user_Collaborative.ipynb) | 0.97 | 0.78 | 0.65 | 0.66 | 0.62 | 0.73 | 0.90 |
| [Item-Item](src/Item_Item_ColaborativeFiltering.ipynb) |  0.91 | 0.75 | 0.59 | 0.54 | 0.54 | 0.65 | 0.87 |
| [MFGD](src/Matrix_Factorization_For_RS.ipynb) | 1.03 | 0.81 | 0.54 | 0.91 | 0.66 | 0.65 | 0.82 |
| [MFSVD](src/Matrix_Factorization_For_RS.ipynb) |  0.95 | 0.75 | 0.65 | 0.73 | 0.65 | 0.73 | 0.92 |


## Contributors
* Trịnh Hoàng Giang: giang.th214893@sis.hust.edu.vn
* Hoàng Thành Đạt: dat.ht214889@sis.hust.edu.vn
* Lăng Văn Quý: quy.lv214928@sis.hust.edu.vn
* Hồ Ngọc Ánh: anh.hn214877@sis.hust.edu.vn
* Vũ Lâm Anh: anh.vl214876@sis.hust.edu.vn
