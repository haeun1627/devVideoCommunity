# devVideoCommunity
individual project

동영상 검색과 작성 기능이 들어있는 개발자 커뮤니티 사이트

* 동영상 게시물 작성 가이드라인은 게시판 공지사항으로 안내

1. 유투브 코딩 동영상 주소들을 데이터베이스에 카테고리 순으로 저장한다.

ajax로 주소를 받아와 제목과 동영상을 가져온다.

게시물 작성 시엔 데이터에 유투브 동영상을 볼 수 있는 코드를 입력하도록 한다. 

제목에 언어종류 또는 해당 동영상의 내용을 표시할 수 있는 특징적인 문구를 작성하도록 함.(보통의 동영상엔 포함이 되어있고 특징적인 문구를 포함되어있는 동영상 자료를 사용하도록 함.)

2. 벡엔드 설계시 참고해야할 사항

프론트에서 만들어 놓은 검색창에 검색하는 단어 입력 시에 그 해당 단어를 유투브에 있는 동영상 목록의 해당 코드를 가진 동영상을 다 가져온 목록중에서 타이틀 값들 안에서 검색을 하게 한다.

데이터베이스 설계 시에 각각의 키 값들에 카테고리를 부여하여 카테고리 값이 검색한 값에 포함되어 있는 경우 해당 동영상을 모두 화면에 출력.

3. 개발에 사용될 언어와 프레임워크

react, ecmascript, nodejs(express), typescript, ecmascript6



출처: https://wdevp.tistory.com/86 [청일 일지]
