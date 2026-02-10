# 🌍 Google Landmark Recognition 2020 (PyTorch)

* PyTorch를 활용하여 랜드마크 이미지를 분류하는 프로젝트입니다. 
* 베이스라인 모델 구축부터 전이 학습(ResNet-18) 및 하이퍼파라미터(lr) 최적화를 통해 성능을 단계적으로 개선해 나가는 과정을 기록하고 있습니다.

---

## Experiments & Progress

실험 단계별로 성능 변화를 기록한 노트북 파일들입니다.

| Step | Notebook File | Key Updates | Accuracy |
| :--- | :--- | :--- | :--- |
| **1** | `landmark-recognition.ipynb` | PyTorch CNN Baseline 구축 | 72.00% |
| **2** | `landmark-recognition-viz.ipynb` | 데이터 시각화 추가 및 전처리 정교화 | 74.25% |
| **3** | `landmark-recognition-resnet.ipynb` | 모델 교체 (**SimpleCNN → ResNet-18**) | 87.75% |
| **4** | `landmark-recognition-lr-opt.ipynb` | **Learning Rate 최적화** (0.001 → 0.0001) | 95.00% |
| **5** | `landmark-recognition-aug.ipynb` | **Data Augmentation** 추가 및 transforms 최적화 | 96.00% |
