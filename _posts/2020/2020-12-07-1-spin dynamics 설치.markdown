---
LAYOUT: POST
TITLE:   "1-spin dynamics 설치"
DATE:   2020-12-07 10:30:00 +0900
CATEGORIES: LIFE

---



#####  2020/12/07(월)

 
spirit 을 설치하려면.

Qt5 를 설치해야됨.

[github gist 참고](https://gist.github.com/sigmadream/45050b2efbbd64582487)

---
3. qt5 및 부속 프로그램 설치
brew install qt5
brew install Caskroom/cask/qt-creator

4. 설정을 해야 한다.
다음과 같은 삽질을 순서대로 실시합니다.

'Qt Creator' - 'Preferences' - 'Build & Run' - 'Qt Versions' - 'Add' - 'Macintosh HD' - 'Command + Shift + . (숨김파일 보여주는 단축키)' - '/usr/local/Cellar/qt5/bin/qmake'

'Preferences' - 'Kits' - 'Compiler' - 'Clang (x86 64bit)'

'Preferences' - 'Qt version' - '방금 우리가 만든 Qt Versions를 선택'



