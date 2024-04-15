## GitLens 사용법
GitLens는 Git을 위한 확장프로그램이다. GitLens를 사용하면 Git의 대부분의 기능을 GUI 모드로 VSCode에서 사용할 수 있다.

---

## 1. VSCode에 GitLens 확장프로그램 설치
먼저 GitLens를 VSCode에 설치한다.

---

## 2. GitLens 레이아웃 설정
GitLens를 설치하면 VSCode 사이드바에 GitLens 아이콘이 추가 된다. GitLens가 제공하는 Git의 여러 기능을 제공하는 탭을 GitLens에 표시할지 Source Control에 표시할지 지정한다. 기본은 source control 레이아웃이다.

아래 제공되는 그림에서 볼 수 있듯이 GitLens에서 제공되는 Git 명령이 다양하게 제공되어 GUI에서 편리하게 사용할 수 있다.


<img width="422" alt="스크린샷 2024-04-15 174000" src="https://github.com/dawoon1229/VSCode_/assets/164113758/ceafd987-80c0-4e5d-8ff3-2aac0943afc9">

GitLens Layout을 변경하기 위해 다음과 같이 실행한다.
  1. ctrl + shift + p 를 눌러 명령 팔레트를 표시한다.
  2. 입력 상자에 gitlens:set 을 입력한다.
  3. 필터된 명령 목록 중 GitLens:set Views Layout 명령을 선택한다.
  4. 표시된 레이아웃 목록 중에 원하는 레이아웃을 선택한다.

---

## 3. Revision Navigation
VSCode 화면 오른쪽 상단에 있는 GitLens의 리비젼 네비게이션 단추들은 해당 파일의 변경된 history를 확인하는데 편리하다.

커밋 중 오래전 커밋을 선택해서 보고 싶다면 리비젼 버튼을 alt 키와 함께 클릭한다. 그러면 해당 파일에 대한 리비젼 목록이 표시된다.

---

## 4. GitLens Branch
GitLens를 이용해 브랜치 목록을 확인하고 브랜치전환, Pull, Push 뿐 만이 아니라 Pull Request 단추를 이용해 바로 GitHub PR 페이지로 이동할 수 있다. Branch 관련 명령 아이콘은 현재 사용 환경에 맞게 제공되면 각 아이콘에 대한 것은 다음과 같다.

<img width="206" alt="스크린샷 2024-04-15 174501" src="https://github.com/dawoon1229/VSCode_/assets/164113758/44978b4e-a9aa-47b5-96d5-2e5d1db68f77">

  1. Switch to Another Branch
  2. Create Branch
  3. Refresh
  4. Fetch
  5. Create Pull Request
  6. Open Branch on Remote
  7. Current Branch
  8. Pull
  9. Pull 받을 commit 있음을 의미
  10. Push
  11. Push할 commit 있음을 의미

---

## 5. Remote

<img width="218" alt="스크린샷 2024-04-15 174650" src="https://github.com/dawoon1229/VSCode_/assets/164113758/42dd65b1-2a77-440d-8c9d-9a314394603f">

  1. Add Remote
  2. Refresh
  3. Fetch
  4. Disconnect from Remote
  5. Open Repository on Remote
  6. default Remote
  7. Connect from Remote : remote에 connet 하면 branch에서 Create Pull Request 를 사용할 수 있다.
