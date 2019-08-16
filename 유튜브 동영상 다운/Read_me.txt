- youtube 다운로드1 : 유튜브 동영상의 url을 컨버터 사이트에 복사해 다운을 받는 크롤링 프로그램. 시간이 좀 걸린다.
- youtube 다운로드2 : pytube 모듈을 사용한 크롤링 프로그램, 1보다 속도가 빠르지만 다운로드 금지인 영상은 받을수가 없다.


- 필요한 모듈이 없으면 anaconda promt에서 따로 설치를 해야함
- pytube는 파이썬 3.5x 에서만 돌아가므로 파이썬 3.6 이상 버전을 사용하면 가상환경을 만들어주어야 한다.
- pytube에서 title 에러가 뜨면 https://github.com/nficano/pytube/pull/435/files 를 참조하여 내부 코드 변경
