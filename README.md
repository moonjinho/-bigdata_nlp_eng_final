# bigdata_nlp_final (ENG)
빅데이터자연어처리기술 영어 감정분석 기말 과제

- 소스 실행 순서

1. git 소스에 있는 friends_train.json / friends_test.json / friends_dev.json 준비
2. 필요한 라이브러리 import 및 데이터 가져오기
3. json 데이터 가져오기
4. 트레이닝용 데이터 생성
5. 품사 태깅
6. 카운팅 끝난 후, 임베딩
7. 트레이닝 데이터의 emotion value를 모두 숫자로 변환
8. X,Y 에 최종적인 train data와 train label 투입 후, 모델 생성
9. LSTM으로 리뷰 감성 분류 시작
10. 가장 좋은 모델을 기준으로 테스트 데이터 정확도 측정 (기준 val_accuracy)
11. Kaggle Sample 데이터를 통한 결과 분류 시작 (data.csv)
12. sample.csv 파일로 export

- 참고한 오픈 소스

1. https://wikidocs.net/44249
2. https://wikidocs.net/31766
3. https://myjamong.tistory.com/77
4. https://wikidocs.net/92961

- Kaggle Name --> (Jin-ho Mun) OR (jinhomoon)
