# PosProgram

## 프로젝트 설명
Pos기와 app와 연동 시켜 식당의 남은 자리를 확인할 수 있는 프로젝트 중 Pos프로그램의 소스코드이다.

eclipse를 통해 작성하였고, eclipse의 WindowBuilder를 설치해 GUI 디자인을 해주었다.

Mysql DB를 사용하여 데이터를 저장,관리 해주었고, JDBC를 이용하여 연동시켰다.


## PosProgram 기능 설명
- 회원가입창을 통해 가게 정보를 받고, Main 페이지에서 테이블 수, 메뉴 등 가게 정보를 입력받을 수 있다.
- 결제 페이지에서 입력된 테이블수대로 테이블이 생성되고 각 테이블에 메뉴를 저장하고, 불러올 수 있다.
- 또한, 대기열을 보는 페이지가 있어 대기 손님을 확인하고 호출할 수 있다.

---
## PosProgram 화면
1. 로그인 화면

<img src="https://user-images.githubusercontent.com/59429551/105848686-b6629280-6022-11eb-8c79-86c05515f573.png" width="380" height ="220">                 


2. 회원가입 화면

![signup](https://user-images.githubusercontent.com/59429551/105849027-2bce6300-6023-11eb-9287-cfed1936832a.png)


3. Main화면. -프로그램 사용방법 확인 가능.

<img src="https://user-images.githubusercontent.com/59429551/105848764-cf6b4380-6022-11eb-9da5-f9fb7582461c.png" width="380" height ="220">


4. 마이페이지 화면. - 개인정보를 확인 가능.

<img src="https://user-images.githubusercontent.com/59429551/105848873-f0cc2f80-6022-11eb-82c4-2b87cb7fbc91.png" width="380" height ="220">


5. 메뉴 화면 - 메뉴를 불러오고 추가, 삭제 가능.

<img src="https://user-images.githubusercontent.com/59429551/105848801-ddb95f80-6022-11eb-80e3-9c8fea163207.png" width="380" height ="220">                


6. 좌석 화면 - 저장된 좌석 수를 불러오거나 저장, 초기화, 수정 가능.

<img src="https://user-images.githubusercontent.com/59429551/105848917-ff1a4b80-6022-11eb-848f-84b8eb900a27.png" width="380" height ="220">                 


7. 포스 화면 - 저장된 메뉴와 좌석을 불러와 화면에 띄우고 계산을 도와준다.

<img src="https://user-images.githubusercontent.com/59429551/105848964-10fbee80-6023-11eb-86be-da73b9163d86.png" width="380" height ="220">


8. 대기 화면 - 어플에서 대기버튼을 누르면 포스기의 대기 화면에서 사용자의 아이디와 번호를 확인 가능하고, 대기 완료를 눌러 사용자 호출이 가능하다.

![wait](https://user-images.githubusercontent.com/59429551/105848997-1fe2a100-6023-11eb-8417-faea58382804.png) 
