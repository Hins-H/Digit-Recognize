# Digit-Recognize-

### Conda 配置环境
``` shell
conda create --name=ml python=3.11
conda activate ml
pip install -r requirements.txt
```

### 项目结构
``` shell
.
├── README.md
├── data
│   ├── test                        # 结果
│   │   ├── SVM_test.csv
│   │   └── knn_test.csv
│   └── raw                         # 原始数据
│       ├── sample_submission.csv
│       ├── test.csv
│       └── train.csv
├── knn.ipynb                       # Numpy 手搓 KNN
├── SVM.ipynb                       # sklearn 的 SVM
└── preprocess                      # 预处理
    ├── __init__.py
    └── preprocess.py
```
