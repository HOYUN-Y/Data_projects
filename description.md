# CMI - Detect Behavior with Sensor Data
##### https://www.kaggle.com/competitions/cmi-detect-behavior-with-sensor-data/overview

### OVERVIEW
Can you use movement, temperature, and proximity sensor data to differentiate between body-focused repetitive behaviors (BFRBs), like hair pulling, from non-BFRB everyday gestures, like adjusting glasses? The goal of this competition is to develop a predictive model that distinguishes BFRB-like and non-BFRB-like activity using data from a variety of sensors collected via a wrist-worn device. Successfully disentangling these behaviors will improve the design and accuracy of wearable BFRB-detection devices, which are relevant to a wide range of mental illnesses, ultimately strengthening the tools available to support their treatment.

## TEAM(Kaggle)
- Suji-highschool alumni

## ENVIORNMENTS
- GITHUB, PYTHON, VSCODE/GOOGLE COLAB

## Team Meeting Minutes (Discussion Summary and Future Plans)
* 6.7 ~ 6.12
    - Github 환경 설정
    - 계획
        - 데이터 수집 환경 구축(Kaggle)
        - 데이터셋 확인
* 6.13(금)
    - 결과물 회의 및 계획
* 6.14 
    - 데이터 형태 확인
    - 계획
        - EDA
* 6.22
    - 결과물 회의 및 계획
    - 게획
        1. tof 데이터 줄이는 방안
        2. sequence id 기준 groupby 하면 센서데이터 어떻게 할 것인지 ->텐서데이터 학습 방법 등
* 6.28(토) 

## Dataset
- train.csv (Sensor data for training)
- train_demographic.csv (Demographic data for training)
- test.csv
- test_demographic.csv

* Records 

* Features

* Target
    - sequence_type: Indicates whether the sequence is a target (BFRBs) or non_target (not BFRBs).
    - gesture: Specifies the type of BFRB gesture (for target) or the type of non-BFRB gesture (for non_target).

## Purpose

## Preprocessing

## Modeling

## Conclusion & Evaluation


## SKILLS
- Python
- Pandas
- ML
- etc.