# instargram_img_downloader
인스타그램 포스팅의 이미지를 다운로드 해주는 크롤러이다.

# 사용방법
- ID 및 PASSWORD에 본인의 인스타그램 아이디 및 비밀번호를 기입한다.
- 이미지 다운로드 원하는 계정의 아이디를 기입한다.
- 다운로드 원하는 이미지 갯수를 기입한다.

# 사용 라이브러리
- Selenium

# 작동 방식
- 인스타그램에 로그인 한다.
- 인스타그램 내부 팝업을 닫아준다.
- 이미지 다운로드 원하는 계정에 접근한다.
- 계정의 이미지를 원하는 갯수만큼 다운로드 한다.

# 한계점
- 특정 포스팅의 이미지만 다운로드 원할 경우, 해당 포스팅이 계정의 몇 번째 포스팅인지 직접 카운팅 해야 한다.
