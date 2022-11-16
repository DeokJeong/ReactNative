? 회사에서 ReactNative를 공부하고있었지만 Flutter와 RN을 두고 어떤것을 선택할지 정하지 못했기때문에 비교해보기위함

---

1 - node.js 공식 홈페이지 https://nodejs.org/ko - LTS 다운로드
    설치 후 cmd를 열어 node -v 를 입력해서 버전이 뜨는지 확인한다
    node.js를 설치하면 npm도 설치되기때문에 npm -v 를 입력하여 버전이 뜨는지 확인한다.
    
2 - yarn 을 깔아준다 = yarn ( npm과 같은 패키지 관리도구로 npm보다 패키지를 더 빨리 설치함 : 페이스북에서 만든 도구 )
    npm install --global yarn
    
3 - JDK(java Development Kit) 설치 = 윈도우 : Chocolatey 패키지 매니저 사용 권장 
    만약 Chocolatey가 설치되어 있지 않다면 'Powershell'을 '관리자 권한' 으로 실행 후 아래 명령어 입력
    Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('http://internal/odata/repo/ChocolateyInstall.ps1'))
    Chocolatey를 설치한 뒤 JDK 설치
    choco install -y openjdk8
    설치 후 javac -version 을 입력해 버전이 뜨는지 확인한다.
    
4 - 안드로이드 스튜디오(Android Studio) 설치 : 모든 운영체제 동일
    https://developer.android.com/studio/index.html
     1) 설치 진행 중 설치타입을 정하는 화면이 나오면 Custom 옵션을 선택
     2) UI Theme 를 선택하는 화면에선 취향에 맞게 선택
     3) 넘기다보면 RAM 선택하는 화면이 나타나고 현재 사용 중인 컴퓨터의 성능에 따라 자동으로 추천하므로 따로 변경하지않고 Next 버튼 클릭
     4) Finish 
    
5 - 안드로이드 환경 변수 설정
    1) 내 PC 우클릭 '속성'
    2) '고급 시스템 설정' 클릭 후 '환경변수'클릭
    3) '환경변수' - '시스템변수' - '새로만들기' 순으로 클릭 ANDROID_HOME 변수 설정 경로참고 : C:\Users\사용자계정\AppData\Local\Android\Sdk
    
6 - VS Code 설치를 마지막으로 React Native 의 설치는 끝!

---
