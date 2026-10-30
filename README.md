# Pet Face Detection with SSD

> **Bootcamp Mission 07** | Object Detection

## 미션 소개
SSD 객체 탐지 모델을 활용해 개와 고양이 이미지에서 얼굴 영역을 탐지하는 컴퓨터 비전 미션입니다. 이미지 분류와 달리 객체의 위치와 범주를 함께 예측하는 과정을 다룹니다.

## 구현 목표
- 객체 탐지 문제의 입력과 출력 형식을 이해한다.
- SSD 모델로 얼굴 영역의 위치를 예측한다.
- 탐지 결과를 바운딩 박스로 시각화한다.

## 주요 구현 내용
- 개·고양이 얼굴 객체 탐지
- SSD 기반 추론
- 바운딩 박스와 탐지 결과 시각화

## 사용 기술
- Python
- SSD
- Computer Vision
- Jupyter Notebook

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission07.ipynb
```

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
```text
notebooks/
  mission07.ipynb
README.md
requirements.txt
.gitignore
```

## 학습 내용
- 객체 탐지는 클래스 예측과 위치 회귀를 함께 다룬다는 점
- 신뢰도 임계값이 탐지 결과 수에 영향을 준다는 점

## 트러블슈팅 및 재현 시 참고 사항
실행 결과에 포함된 로컬 경로는 재현 환경에서 상대 경로로 바꾸는 것을 권장합니다.

## 결과 확인
탐지된 얼굴 영역은 노트북의 이미지 출력에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Object Detection** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.