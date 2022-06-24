# Genshin Resin Counter Widget [![Github Downloads (total)](https://img.shields.io/github/downloads/stupidJoon/genshin-resin-counter-widget/total.svg)]()

Scriptable를 이용해서 만든 원신 레진 카운터 위젯

![](https://user-images.githubusercontent.com/35032401/138546515-82be9aba-230c-42b9-98ea-114e9c95d02e.png)

# 기능
- 현재 퓨어 레진 확인 기능
- 현재 퓨어 레진이 전부 회복할때까지의 시간 확인 기능
- 현재 탐사파견이 도착했는지 확인 기능(오른쪽 위의 아이콘의 색깔로 탐사파견이 전부 진행중이면 초록색, 일부만 진행중이면 노란색, 진행중인 탐사파견이 없으면 빨간색)
- 다크모드 지원

# 설치 방법
1. 먼저 원신 UID와 hoyolab의 쿠키가 필요하다
    1. 원신 UID를 가져온다
    2. hoyolab에서 출석체크나 전적 페이지에 들어간다
    3. 쿠키에서 ltoken 값과 ltuid값을 가져온다
2. Scriptable 앱에서 위젯 스크립트를 가져온다
    1. 앱스토어에서 Scriptable을 설치한다
    2. Release 탭에서 .scriptable 파일을 다운로드한다
    3. .scriptable 파일을 Scriptable 앱으로 가져온다
3. 위젯을 추가한다
    1. 아이폰 빈 화면에서 가장 작은 Scriptable 위젯을 추가한다
    2. 위젯을 꾹 눌러서 위젯 편집에 들어가고 Script를 선택해서 2에서 가져왔던 원신 레진 카운터 스크립트를 선택해준다
    3. 다시 위젯 편집 화면에서 Parameter에 1에서 가져온 쿠키를 다음 형식대로 넣어준다(UID|ltoken=asdf; ltuid=asdf;)
    > ex) 123456789|ltoken=asdfasdfasdf; ltuid=12345678;

# 미리보기
| 설명  | 이미지 |
| ------------- | ------------- |
| 라이트 모드  | <img src="https://user-images.githubusercontent.com/35032401/138547577-5ee6f948-c610-4cff-88f0-46b8af435250.png" />  |
| 다크모드  | <img src="https://user-images.githubusercontent.com/35032401/138547579-6b0c1988-2fe4-46ea-9e4e-49cf143021d4.png" />  |
