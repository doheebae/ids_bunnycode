# ids_bunnycode

pip install scapy

pip install tqdm

위의 라이브러리 설치가 필요합니다. 혹 구현하다가 또 install할 게 있으면 여기다 계속 추가할게요.

스레드 수는 본인의 cpu에 따라 다르지만 적어도 10이상은 하셔야 퍼포먼스 속도가 납니다.

진행률을 보여주는게 좋을 것 같아 넣었는데 분석 속도가 빠르면 금방 지나가서 표시되지 않는 것 같습니다.

일단 잘 디코딩했는지 확인하기 위해서 텍스트 파일 형식으로 저장하게 했는데요 경로는 main.py가 실행되는 곳일겁니다.
분석할 파일 경로는 절대경로로 해주시면 돼요(상대경로로는 제가 안해봐서)
디코딩 모듈을 잘 만들면 텍스트 파일 만드는 부분은 제거를 할 겁니다
