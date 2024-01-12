# Fall_Prevention_banister

## 환경
#### Rasberry Pi 4, Arduino UNO

## 라이브러리
```bash
아래의 라이브러리들을 설치해주시면 됩니다.

tts관련
$pip install gtts #tts를 제작하는 툴이기 때문에 따로 soundmaker.py를 실행하지 않으려면 설치하지 않아도 됩니다.
$pip install playsound

스트리밍 처리 관련
$pip install numpy
$pip install opencv-python

웹소켓 관련
$pip install websocket

시리얼 통신 관련
$pip install pyserial
```

## 참고사항
```bash
실행파일은 py안의 FPB_main.py파일입니다.
tts를 만들려면 py 파일 내의 soundmaker.py파일로 만들면 됩니다.(경로 재설정 필요)
작품의 라즈베리파이와 안의 cctv를 화면을 보는 기기는 같은 와이파이환경에서 실행되어야 합니다.
cctv의 스트리밍 화면은 파일내의 index.html파일에서 코드 실행 후 보이는 아이피주소를 입력시켜주면 됩니다.
```
