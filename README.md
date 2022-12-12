# wav-spectrogram-classification
1. 음성데이터 분류 문제
- 1차원 시계열 데이터(wav)를 Conv1D 모델을 이용하여 분류
- 1차원 데이터를 2차원 Spectrogram으로 변환하고, Conv2D 모델을 이용하여 분류
- 각각의 모델에 skip-connection을 추가하여 overfitting 문제가 얼마만큼 해결되는지 확인
- 더 나아가 그래프 데이터로 만들고, simplicial complex 구조를 이용해 보자...

2. "Signal processing on simplicial complexes" 논문 introduction 정리 : 
   https://www.notion.so/Signal-processing-on-simplicial-complexes-bd607da833e24c988dd536b39f99400a
