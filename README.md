# Autonomous Driving Data Preprocessing

## Overview
This repository contains scripts and documentation for preprocessing data for autonomous driving models. The dataset includes images and annotations in JSON format.

## Folder Structure
- **/data/raw**: Contains the original dataset with images and annotations.
- **/data/processed**: Contains the preprocessed data ready for model training.
- **/scripts**: Contains Python scripts for data preprocessing tasks.
- **/docs**: Additional documentation and explanations.

## Preprocessing Steps
1. **Data Integration**: Combine JSON annotations with image paths.
2. **Bounding Box Normalization**: Normalize bounding box coordinates based on image dimensions.
3. **Data Augmentation**: Apply random transformations to images and adjust bounding boxes.
4. **Dataset Splitting**: Divide the dataset into training, validation, and test sets.
5. **File Format Conversion**: Convert annotations to the required format for the model.

## Usage
To run the preprocessing scripts:
1. Install dependencies: `pip install -r requirements.txt`
2. Run preprocessing: `python scripts/preprocess.py`
3. Check processed data in the `/data/processed` folder.

## License
This project is licensed under the MIT License.


# 자율주행 데이터 전처리

## 개요
이 저장소에는 자율 주행 모델을 위한 데이터 전처리를 위한 스크립트와 문서가 포함되어 있습니다. 데이터 세트에는 JSON 형식의 이미지와 주석이 포함되어 있습니다.

## 폴더 구조
- **/data/raw**: 이미지와 주석이 포함된 원본 데이터세트를 포함합니다.
- **/data/processed**: 모델 학습을 위해 준비된 전처리된 데이터를 포함합니다.
- **/scripts**: 데이터 전처리 작업을 위한 Python 스크립트가 포함되어 있습니다.
- **/docs**: 추가 문서 및 설명입니다.

## 전처리 단계
1. **데이터 통합**: JSON 주석을 이미지 경로와 결합합니다.
2. **경계 상자 정규화**: 이미지 크기를 기준으로 경계 상자 좌표를 정규화합니다.
3. **데이터 확대**: 이미지에 무작위 변환을 적용하고 경계 상자를 조정합니다.
4. **데이터세트 분할**: 데이터세트를 훈련, 검증, 테스트 세트로 나눕니다.
5. **파일 형식 변환**: 주석을 모델에 필요한 형식으로 변환합니다.

## 용법
전처리 스크립트를 실행하려면 다음 안내를 따르세요.
1. 종속성 설치: `pip install -r 요구 사항.txt`
2. 전처리 실행: `python scripts/preprocess.py`
3. `/data/processed` 폴더에서 처리된 데이터를 확인하세요.

## 라이센스
이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다.


