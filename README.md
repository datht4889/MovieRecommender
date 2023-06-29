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
| K = 30 | RMSE | MAE | Precision@k | Recall@k | F1 | MAP@K | NDCG |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [Content-based](src/Content_based.ipynb) | 0.004732 |	0.044239 |	0.048462 |	0.017796 | 0.965038 |	0.753001 |	0.255647 |
| [User-User](src/User_user_Collaborative.ipynb) | 0.146126	| 0.475077 |	0.411771 |	0.219145 | N/A |	N/A |	N/A |
| [Item-Item](src/Item_Item_ColaborativeFiltering.ipynb) | 0.132478	| 0.441997 |	0.388229 |	0.212522 | N/A |	N/A |	N/A |
| [MFGD](src/Matrix_Factorization_For_RS.ipynb) | 0.025503 |	0.147866 |	0.130329 |	0.053824 | 0.943084 |	0.744337 |	0.285308 |
| [MFSVD](src/Matrix_Factorization_For_RS.ipynb) | 0.088526 | 0.419846 | 0.379626 | 0.144336 | N/A | N/A | N/A |


## Contributors
* Trịnh Hoàng Giang: giang.th214893@sis.hust.edu.vn
* Hoàng Thành Đạt: dat.ht214889@sis.hust.edu.vn
* Lăng Văn Quý: quy.lv214928@sis.hust.edu.vn
* Hồ Ngọc Ánh: anh.hn214877@sis.hust.edu.vn
* Vũ Lâm Anh: anh.vl214876@sis.hust.edu.vn
