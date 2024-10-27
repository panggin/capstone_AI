# capstone_AI
혈당 관리를 위한 식단 기록 앱 AI 파트

## Intro

음식 사진 등록으로 영양 정보를 자동으로 판단하는 기능을 구현하기 위해 한식 이미지 분류기를 제작하였습니다.

기존 분류 모델 `MobileNet`의 특성 추출층을 사용하고 새로운 분류 체계에 맞도록 완전 연결층을 추가하여 학습하였습니다.

- 최종 학습 모델 : [foodmodel.h5](https://github.com/panggin/capstone_AI/blob/main/code/AI_package_and_flask/foodmodel.h5)

- 이미지 분류기 활용을 위한 모듈 : [foodmodel_module.py](https://github.com/panggin/capstone_AI/blob/main/code/AI_package_and_flask/foodmodel_module.py)

- 보고서 : [당일일지_혈당관리앱_중간보고서](https://github.com/panggin/capstone_AI/blob/main/%EB%8B%B9%EC%9D%BC%EC%9D%BC%EC%A7%80_%ED%98%88%EB%8B%B9%EA%B4%80%EB%A6%AC%EC%95%B1_%EC%A4%91%EA%B0%84%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)
, [당일일지_혈당관리앱_최종보고서](https://github.com/panggin/capstone_AI/blob/main/%EB%8B%B9%EC%9D%BC%EC%9D%BC%EC%A7%80_%ED%98%88%EB%8B%B9%EA%B4%80%EB%A6%AC%EC%95%B1_%EC%B5%9C%EC%A2%85%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

## Description

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/c508073c-7336-4dd4-a7d8-3add52c644ae">

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/5f62b72b-ca80-4c3a-a9a4-31d002a06293">

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/b97ad005-3336-4a37-b29b-8809f8355c53">

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/55b7df97-c7a0-478e-b06d-5645042694be">


## Project Setup

[이미지 분류기 활용 모듈](https://github.com/panggin/capstone_AI/blob/main/code/AI_package_and_flask/foodmodel_module.py)을 사용하여 학습된 모델의 예측 기능을 사용할 수 있습니다.

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/48a8cfd2-834a-4770-a195-b9be6f676ee0">
