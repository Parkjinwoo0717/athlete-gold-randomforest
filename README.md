# 랜덤포레스트를 이용한 운동선수 금메달 여부 예측

체력검사 수치(체격·근력·지구력)로 금메달을 딴 선수인지 맞히는 분류 분석입니다.

- 방법: 랜덤포레스트 (RandomForestClassifier, 트리 100개)
- 평가: 정확도 0.82 · 정밀도 1.00 · 재현율 0.36 · F1 0.53 (평가 79명)

## 데이터 출처
Nilsook, P., et al. (2023). Physical fitness feature of athletes (Version 3).
Mendeley Data. https://doi.org/10.17632/vmwgtj58xs.3
라이선스: CC BY 4.0

※ 원본 데이터 파일은 올리지 않았습니다. 위 링크에서 내려받아 사용하세요.

## 파일
- athlete_gold_randomforest.ipynb : 분석 코드
- athlete_project.pptx : 발표 자료