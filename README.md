초기 설정
1. API키 발급
2. Visual Studio Code 다운로드
3. Visual Studio Code 내에서 python 설치
4. 아나콘다 다운로드
5. 위의 프로그램 다운로드 경로에 새로운 폴더 생성하기
ex) 자동매매프로그램 또는 자동매매 등
6. Visual Studio Code 실행 후 위의 폴더를 열어 터미널 생성 후 아래 명령어를 입력
* pip install pyupbit
* pip install openpyxl
* pip install schedule
* conda install -c conda-forge fbprophet
* pip install pystan --upgrade
-> Visual Studio Code 종료 후 다시 실행

7. 클라우드 서버 생성
8. 클라우드 서버 생성 후 아래 명령어를 입력
Ubuntu 서버 명령어
* 한국 기준으로 서버 시간 설정: sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
* 현재 경로 상세 출력: ls -al
* 경로 이동: cd 경로
* vim 에디터로 파일 열기: 예시 : vim bitcoinAutoTrade.py
* vim 에디터 입력: i
* vim 에디터 저장: :wq!
* 패키지 목록 업데이트: sudo apt update
* pip3 설치: sudo apt install python3-pip
* pip3로 pyupbit 설치: pip3 install pyupbit
* 백그라운드 실행: nohup python3 bitcoinAutoTrade.py > output.log &
* 실행되고 있는지 확인: ps ax | grep .py
* 프로세스 종료(PID는 ps ax | grep .py를 했을때 확인 가능): kill -9 PID

Ubuntu 20.4 인공지능 (Prophet) 자동매매 환경 설치 방법
* 4GB이상 RAM 필요 (AWS t2.medium 이상)
* sudo apt update
* sudo ln -sf /usr/share/zoneinfo/Asia/Seoul /etc/localtime
* sudo apt install python3-pip
* pip3 install pyupbit
* pip3 install schedule
* pip3 install pystan==2.19.1.1
* pip3 install convertdate
* pip3 install fbprophet
