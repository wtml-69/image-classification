# image-classification
Image classification comparing CNN, MobileNetV2, and EfficientNetB0 on Imagenette dataset.

------------ 前置作業 ------------
Tensoflow Version: 2.10.0
打開 Anaconda Prompt，依序執行

1. 建立環境

conda create -n tf210_env python=3.10 -y

2. NumPy 2.0、TFDS 版本不容，以及缺少畫圖和進度條套件的問題，可以在同一個 Anaconda Prompt 下一次輸入
pip install tensorflow==2.10.0 tensorflow-datasets==4.6.0 "numpy<2.0.0" "protobuf<=3.20.3" matplotlib ipywidgets jupyter
