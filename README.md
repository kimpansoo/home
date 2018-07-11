### 1.Raspberry pi zero w + snowboy = 조명 콘드롤 음성스위치
반갑습니다.
이곳에서는 라즈베리파이 제로 W와 음성 핫디텍션 [SNOWBOY](https://snowboy.kitt.ai/)로 음성제어 조명스위치를 만들어 보았습니다.

>[라즈베리파이 제로 w와 SNOWBOY 참고](https://app.box.com/notes/299018715900) 

>[동영상](https://drive.google.com/open?id=1zZ5AiDI05GIpqeC_7p4Z9xxkVcEuKtmj)

### 2.YouTube 스트리밍
>휴대 전화에 raspicast [앱을 다운로드하십시오](https://play.google.com/store/apps/details?id=at.huber.raspicast)
SSH 로그인 설정을 앱에 입력하십시오.
YouTube 비디오를 Raspberry Pi로 전송하려면 YouTube 앱과 비디오를 열고 "공유"→ Raspicast를 선택하십시오.
비디오가 PiGlass에서 재생되기 시작합니다!
>코드 입력
sudo apt-get install mpv
sudo pip3 install youtube-dl
git clone https://github.com/mps-youtube/mps-youtube.git
cd mps-youtube
sudo python3 setup.py install

sudo python3 setup . 파이 설치
mpsyt를 실행 한 다음 set player mpv를 입력하십시오.
축하합니다. 이제 YouTube 오디오를 스팀 할 수 있습니다!
예를 들어, / sia에 입력 
한 다음 Enter 키를 누르십시오. 노래 목록이 나타나면 입력하려는 노래의 번호를 입력하고 입력을 시작하십시오.
