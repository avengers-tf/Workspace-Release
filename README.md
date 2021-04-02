# Workspace Installer Release

File Version == TAG Version 비교 후 불일치하면 업데이트   
Release의 Hash : "data" -- JSON 값으로 SHA-265 비교
   
## Update File 올리는 법
1. Setup.exe 파일 변경
2. release 추가
3. https://api.github.com/repos/avengers-tf/Workspace-Release/releases/latest 경로에서   
"zipball_url": "url" << url로 접속 후 다운로드
5. 다운로드 ZIP 파일 해시 sha256 복사
6. release message에 hash : "해시값" 추가 후 업데이트 release
