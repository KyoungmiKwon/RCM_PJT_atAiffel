###  설정

* 아래의 라이브러리를 설치 해 주세요
```bash
pip install tensorflow
pip install streamlit numpy pandas joblib scikit-learn tqdm
```
* 아래 버전을 권장드립니다.    
  `Python 3.11`, `TensorFlow 2.15.0`

### 실행 방법

해당 파일이 있는 폴더 안에서 다음 명령어를 실행 하세요.    
```bash
streamlit run show_st2.py
```
  * `show_st.py`: 노드 테스트 코드
  * `show_st2.py`: 프로젝트 전체 실행 코드

### Test
* 파라미터를 변경하며 아래와 같이 실험 해 보았습니다.

| epoch | lr    | dropout | batch | embed | NDCG   | Hitrate |
|-------|-------|---------|-------|--------|--------|---------|
| 5     | 1e-4  | 0.0     | 2048  | 16     |  0.66162 | 0.63048  |
| 10    | 1e-4  | 0.4     | 2048  | 16     | 0.66202   | 0.63016    |
| 20    | 1e-4  | 0.4     | 1024  | 16     | 0.66285   | 0.63103  |
