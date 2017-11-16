# EEG_Emotion_Classfication

## Overview
EEG_Emotion_Classification은 pleasure, neutral, unpleasure 감정을 의도한 영상을 보면서 사람의 뇌파(EEG)를 통해 얻어진 머리의 특정 부위들의 Feature 데이터를 추출하고 해당 데이터를 사용하여 의사 분류 트리에 해당 데이터들을 입력하고 감정 분류를 실시하는 모듈이다.적절한 뇌파 추출을 위해 EEG 측정 Device를 사용하여 남자 10명, 여자 10명의 데이터를 추출하였으며, 실험 과정 중 잘못된 실험 프로토콜 설정으로 인한 결과물을 제외한 총 10가지의 데이터를 수집하였다.

## Features
Data 폴더에 위치한 데이터들은 .mat 파일의 확장자를 가지고 있으며 피실험자는 총 18개의 영상을 시청하고 다음 영상을 방해하는 노이즈를 최대한 줄이기 위해 30초씩 휴식을 취한다. 데이터는 2x18의 셀로 이루어져 있으며 1행은 영상을 보면서 추출된 데이터이고, 2행은 30초마다의 휴식 기간의 데이터이다. 각 열은 서로 다른 18개의 영상을 나타낸 것이다.
![2x18 cell](https://github.com/JeongKwonHo/EEG_Emotion_Classfication/IMAGE/CELL.png)
