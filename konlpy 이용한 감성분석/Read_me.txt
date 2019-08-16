konlpy 모듈을 실행하려면 java 설정이 필요.

1. java 최신버전 설치
- https://www.java.com/ko/ 에서 자신에 맞는 자바 설치
- 파이썬 bit 와 자바 bit 를 컴퓨터 bit에 알맞게 설치해야함

2. JAVA_HOME 설정
- '내 PC'에서 우클릭 - > 속성 -> 고급 시스템 설정 -> 환경변수 -> 시스템 변수 -> 새로만들기
 -> 변수 이름에 JAVA_HOME , 변수 값에 java 폴더 위치 ex)C:\Program Files\Java\jre1.8.0_221

- Path 클릭 후 편집 - 새로 만들기 - %JAVA_HOME%\bin 입력 - 확인

3. JPype1 (>=0.5.7)을 다운로드 받고 설치. 다운 받은 .whl 파일을 설치하기 위해서는 pip 을 업그레이드 해야할 수 있습니다.

- https://www.lfd.uci.edu/~gohlke/pythonlibs/#jpype
- 위의 주소에서 컴퓨터에 맞는 JPype 설치
- 아나콘다 prompt에서 다음 입력
	> pip install --upgrade pip
	> pip install (파일명)
	ex) pip install JPype1-0.5.7-cp27-none-win_amd64.whl