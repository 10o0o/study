# 기계학습 파이썬 개발환경

## 라이브러리란?
 - 특정 기능들을 종류별로 미리 만들어 묶어 둔 것
 - 종류: 표준 라이브러리, 외부 라이브러리, 개인 모듈

### 외부 라이브러리
#### numpy
다차원의 배열/행렬을 생성하고 다룸
#### matplotlib
과학 계산용 그래프 라이브러리
#### pandas
데이터로부터 학습자료를 읽고 쓰고, 전처리함
#### scipy
다양한 과학적 계산을 위한 모듈, scientific python의 약자
#### scikit-learn
기계학습에 필요한 다양한 알고리즘 제공

### 프레임워크
- TensorFlow
- Keras
- Pytorch

#### TensorFlow
- 구글이 오픈소스로 개발
- 핵심기줄 C++
- 프론트 엔드는 파이썬으로 작성
- GPU 사용
- 시각화 툴인 TensorBoard 제공

#### Keras
- 텐서플로를 기반으로 한 프레임워크
- 직관적인 API
- 혀냊 텐서플로아ㅗ 통합되어 텐서플로 안에서도 사용 가능

#### PyTorch
- Lua로 개발된 Torch를 파이썬 API로 개발
- 디버깅이 쉬운 직관적인 코드로 구성
- 동적 그래프: 언제든지 데이터에 따라 모델 조정 가능

### IDE

#### Jupyter Notebook
- IPython (Interfactive Python)의 장점 모두 물려 받음
- 웹 브라우서에서 코딩과 문서 작성 모두 가능
- 최고의 파이썬 개발환경 (IDE: Interactive Development Environment)

## jupyter notebook 유용한 셀 명령어 (셀 편집상태에서 <esc>, ctrl + m 커맨드 모드)
- m: 셀 타입을 마크다운으로 전환
- y: 셀 타입을 코드로 전환
- dd: 셀 삭제
- x: 셀 잘라내기
- c: 셀 복사
- s: 파일 저장
- Shift + m: 아래 셀과 병합
- Enter: 편집 모드로 진입
- l: 코드 셀의 라인에 번호매김 하거나 숨기기