# Bootcamp Mission 07 - SSD 기반 개와 고양이 얼굴 객체 탐지

## 1. 개요
Oxford-IIIT Pet 데이터셋을 활용해 개와 고양이 얼굴 영역을 탐지한 미션입니다.

## 2. 목표
Object Detection 모델을 활용해 이미지 내 객체 위치를 예측하고 평가하는 것을 목표로 했습니다.

## 3. 사용 기술
- Python
- pandas
- numpy
- matplotlib
- scikit-learn
- opencv-python
- Pillow
- torch
- torchvision
- ultralytics
- kagglehub

## 4. 주요 기능
- Pet 데이터셋 준비
- Annotation 처리
- SSD 모델 실험
- YOLO 모델 비교

## 5. 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission07.ipynb
```

## 6. 주요 파일
- `notebooks/mission07.ipynb`

## 7. 폴더 구조
```text
bootcamp-mission-07
  .gitignore
  notebooks/
    mission07.ipynb
  README.md
  requirements.txt
```

## 8. 학습 내용
객체 탐지 문제에서 바운딩 박스 데이터 처리와 모델 추론 결과 해석 방법을 학습했습니다.

## 9. 트러블슈팅
미션을 진행하며 발생한 오류와 해결 과정은 노트북 또는 보고서에 정리했습니다.

## 10. 결과 화면
결과 이미지는 노트북 출력, 보고서 또는 `images/` 폴더에서 확인할 수 있습니다.

## 11. 공개 전 확인 사항
- 제출 노트북만 포함했으며, 원본 데이터와 모델 파일은 공개 범위 확인 전 포함하지 않았습니다.
