# project_dog_v2

### 9/11 팀 회의
1) 주제 선정
2) 팀원별 원하는 스택 확인

### 9/12 팀 회의
1) 주제 확정
2) 머신러닝, 딥러닝, 데이터 시각화로 팀 나눔
3) 소스 코드 확인

### 9/13 코드 작성
1) preprocess.py에 추가할 new_input()함수 및 실행 코드, classifier.py에 들어갈 결과 프린트 코드

### 9/13 파일 트리 정리
1) scan / register 단계 분리
2) image path 변경(scan/YOLOv5/detect.py)
3) image path 변경(register/YOLOv5/detect.py)

### 9/14 코드 작성
1) activate.py생성
2) classifier_1.py 파일에 결과 프린트 부분 추가

### 9/14 팀 회의
1) DB 형식 확정
2) 폴더 트리 확정

### 9/15 코드 작성
1) image/scan_input 폴더 초기화 기능 추가(scan/YOLOv5/detect.py)
2) image/register_input 폴더 초기화 기능 추가(register/YOLOv5/detect.py)
3) image/test 폴더 초기화 기능 추가(scan/YOLOv5/detect.py)
4) preprocess.py에 DB update 코드 추가
5) classifier.py에서 출력값 수정 및 모듈 연결

### 9/18 코드 작성
1) cropped_img 폴더 DB 인덱스와 연동, 번호 자동생성
2) DB 형식 고정. 바뀐 칼럼값 preprocess에 수정
3) preprocess.py new_input()의 입력값에 조건 붙이기
4) 입력값 조건 추가 하면서 classifier.py의 출력값에 들어있던 조건절 수정. (answer = 'y' or answer = 'Y'등등에서 answer in ['y', 'Y'])
5) image/enroll_img 경로 추가
