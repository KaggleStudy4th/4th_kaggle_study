## 1. 캐글 api 불러오는 과정에서 오류 + 해결
#### https://little-coder-developer.tistory.com/56

## 2. 데이터 전처리 과정에서 생긴 오류 
#### ->사소한 오타... 해결 완료!

## 3. random_state 에 대하여
#### 재현가능(for reproducibility)하도록 난수의 초기값을 설정해주는 것이며, 임의의 숫자를 넣어주면 됨! 
#### ex) random_state = 100 
#### np.random.seed() => 컴퓨터가 만드는 무작위 수는 사실 엄격한 의미의 무작위 수가 아님. 
#### 어떤 특정한 시작 숫자를 정해 주면 컴퓨터가 정해진 알고리즘에 의해 마치 난수처럼 보이는 수열을 생성, 이런 시작 숫자를 시드(seed)라고 함!
#### ex) rand 함수로 5개의 난수를 생성해 보자. -> np.random.rand(5)
