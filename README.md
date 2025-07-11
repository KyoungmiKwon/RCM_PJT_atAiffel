## 가상환경 설정

* 새로운 가상환경을 생성한 뒤, 아래 버전으로 진행해 주세요.
  (권장: `Python 3.11`, `TensorFlow 2.15.0`)

```bash
pip install tensorflow
pip install streamlit numpy pandas joblib scikit-learn tqdm
```

## 실행 방법

* 프로젝트 폴더 안에서 다음 명령어로 실행해 주세요.

  * `show_st.py`: 노드 테스트 코드
  * `show_st2.py`: 프로젝트 전체 실행 코드

```bash
streamlit run show_st2.py
```
