# 한양대학교 바이오로보틱스 연구실 딥러닝 서버 사용법
## 1. 계정 요청
   원하시는 계정명과 비밀번호, 소속을 tjdalckd@gmail.com으로 보내주세요.
   
    example) 
    ID : bio1
    PASSWD : bio1234
    소속 : 최영진 교수님 연구실
## 2. 계정 로그인
   WINDOWS에서 접속하는 경우 Putty라는 프로그램을 사용하시는 것을 추천합니다.
   Putty프로그램을 실행하고 메일로 알려드린 아이피를 입력하면 접속하실 수 있습니다.
   다음의 사이트를 참고하셔서 접속하세요.
   
    https://deidesheim.tistory.com/entry/PuTTY-%EB%A1%9C-SSH-%EC%9B%90%EA%B2%A9%EC%A0%91%EC%86%8D-%ED%95%B4%EB%B3%B4%EA%B8%B0
   Ubuntu 환경에서 접속할 경우 openssh-server를 설치해야 합니다.
   터미널창을 열고 다음을 입력하여 openssh-server를 설치합니다.
   
    sudo apt-get install openssh-server
    ssh 계정명@166.104.xxx.xxx 
## 3. 환경 설정
   딥러닝 서버는 Ubuntu 18.04 / CUDA 10.0 Version으로 구축된 환경입니다. 따라서 사용하실 학습 환경을 딥러닝 서버의 환경과 맞춰주셔야 합니다.
    
