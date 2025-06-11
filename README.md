### ❗️ macOS에서 손상된 앱 오류 해결 방법

macOS는 인터넷에서 받은 앱에 대해 실행을 막을 수 있습니다. 아래 단계를 따라 실행하세요:

1. 앱을 설치합니다.
2. 터미널(Terminal)을 엽니다.
3. 아래 명령어를 복사해서 붙여넣고 Enter:

sudo xattr -r -d com.apple.quarantine /Applications/'Move!Bunny'.app

4. 기기 비밀번호를 입력하세요. (보이지는 않지만 입력되고 있습니다.)
5. 앱을 실행합니다.
