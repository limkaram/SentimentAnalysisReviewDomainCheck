# NLPReviewDomainTransfer
KcELECTRA 딥러닝 모델 활용 도메인 의존성 확인

# CNNModelAnalysis

### 내용
    Korean Comment Corpus 사전 학습 모델인 KcELECTRA 활용 리뷰 도메인 의존성 확인
    
### 데이터셋
    CIFAR-10

### 목적
    호텔 리뷰 감성분석기 구현 예정이나 수집 데이터의 부족으로
    공개된 네이버 영화 리뷰 데이터를 활용하여 학습 후 호텔 리뷰 데이터를 추론하여도 유의미한 결과가 나오는지 확인

### 결과
    - 영화 리뷰 데이터를 활용 학습 후 약 50개의 호텔 리뷰 데이터에 대하여 추론하여 정확도 측정시 약 93.75% 수준으로 유의미함
    - Fine-Tuning시 학습되는 데이터보다 사전 학습시 활용되는 코퍼스의 도메인(Korean Comment)에 더욱 의존하는 것으로 추정됨

