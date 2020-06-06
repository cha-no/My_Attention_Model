## Attention Model
### 카카오아레나 쇼핑몰 카테고리 분류
#### 한국어 자연언어처리

- train_chunk 1개로 상품명 데이터만 이용
-
- okt 한국어 형태소 분석기 이용
- LSTM 모델에 Attention 매커니즘 적용
- attention value 값으로 dot product 연산 적용
- 정확도 약 0.91

#### 버전
- tensorflow 2.0.0
- keras 2.3.1
