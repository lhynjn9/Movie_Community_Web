# Django와 Vue.js를 활용한 영화 커뮤니티 웹사이트

<br>

### 🏆SSAFY 7기 1학기 종합 프로젝트 우수상 입상🏆

- 진행 기간 : 2022.05.20.(금)  ~ 2021.05.26.(목)

<br>

![Animation](images/README/Animation.gif)

<br>

### 🤝팀원

| 이름   | 담당 영역                                                    | Github                        |
| ------ | ------------------------------------------------------------ | ----------------------------- |
| 박시원 | - 프론트엔드(70%) / 백엔드(30%)<br />- 백엔드 데이터를 받아와 프론트엔드 기능 구현 및 디버깅, 테스트 | https://github.com/siwon-park |
| 이현정 | - 프론트엔드(30%) / 백엔드(70%)<br />- DB 모델링, 백엔드 데이터 로직 작성, 프론트엔드 디자인 정교화 | https://github.com/lhynjn9    |

<br>

### 📝Description

- [상세화면](https://github.com/siwon-park/Movie_Community_Web/blob/master/%EC%83%81%EC%84%B8%ED%99%94%EB%A9%B4%20%EA%B5%AC%EC%84%B1/DetailView.md)
- 영화 정보 및 추천 서비스 제공 프로젝트
- 기획의도: MZ 세대를 고려한 신뢰성 있는 정보 기반의 영화 추천 커뮤니티 웹 사이트 제작 및 서비스 제공
  => 사용자가 제공하는 정보를 이용했기 때문에 신뢰성있는 정보라고 할 수 있음
  => 사이트의 서비스를 이용하는 재미를 주기위해 동적으로 웹 페이지를 구성

<br>

### 🥇GOAL

- 영화 데이터 및 사용자 데이터 기반 추천 서비스 구성
- 커뮤니티 서비스 구성
- HTML, CSS, JavaScript, Bootstrap, Vue.js, REST API, Database 등을 활용한 실제 서비스 설계
- 서비스 관리 및 유지 보수

<br>

### 💻 필수 요구사항

| No.  | 구분               | 기능                                        | 구현 정도(⭐⭐⭐⭐⭐)                                            |
| ---- | ------------------ | ------------------------------------------- | ----------------------------------------------------------- |
| 1    | 관리자 뷰          | 관리자 유저의 영화 C/R/U/D                  | ⭐⭐⭐⭐⭐                                                       |
| 2    | 관리자 뷰          | 관리자 유저의 일반 유저 관리                | ⭐⭐⭐⭐⭐                                                       |
| 3    | 관리자 뷰          | Django/Vue.js의 기본 admin 기능 이용        | ⭐⭐⭐⭐⭐                                                       |
| 4    | 영화 정보          | 50개 이상의 영화 데이터 삽입                | ⭐⭐⭐⭐⭐                                                       |
| 5    | 영화 정보          | 로그인 유저의 영화 평점 C/U/D               | ⭐⭐⭐⭐⭐                                                       |
| 6    | 영화 추천 알고리즘 | 유저 정보를 기반으로 한 영화 추천           | ⭐⭐⭐⭐⭐                                                       |
| 7    | 영화 추천 알고리즘 | 영화 추천 알고리즘1개 이상의 추천 방식 사용 | 1. 콘텐츠(좋아요, 평점) 기반 필터링<br />3. 장르 기반(랜덤) |
| 8    | 커뮤니티           | 커뮤니티 기능                               | ⭐⭐⭐⭐⭐                                                       |
| 9    | 커뮤니티           | 로그인 유저만 커뮤니티 글 C/R               | ⭐⭐⭐⭐⭐                                                       |

<br>

### 🛠Tech Stack

![image](https://user-images.githubusercontent.com/93081720/170559780-a977ed18-e589-4ffd-bb49-2f24d92cdeac.png)

<br>

### 🏗데이터베이스 모델링(ERD)

![image](https://user-images.githubusercontent.com/93081720/170559637-5439b223-507f-4a47-842c-f6073f39ed74.png)

<br>

### 🏔컴포넌트 구조

![image](https://user-images.githubusercontent.com/93081720/170559504-24208c97-1837-4b46-b1fd-2da311cf9673.png)

<br>🎮 서비스 플로우 차트

![image](https://user-images.githubusercontent.com/93081720/170559916-3516cc7a-58d8-40b7-842d-b27edaddd097.png)

<br>

### 📅개발일지

| No.  | Date     | Name   | ToDo                                                         | Done                                                         |
| ---- | -------- | ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | 22/05/20 | 박시원 | 로그인/회원가입 및 기초 CSS                                  | 로그인/회원가입 기능 구현, 영화 데이터 불러오기 구현         |
| 2    | 22/05/20 | 이현정 | 로그인/회원가입, 프로필 데이터 직렬화                        | 로그인/회원가입, 프로필 데이터 직렬화,영화 데이터 필터링     |
| 3    | 22/05/21 | 박시원 | 로그인/회원가입 폼 CSS, 대댓글 기능 구현, 영화 데이터 받아오는 부분 수정 등 | 로그인/회원가입 CSS 폼 작성, 리뷰, 대댓글 기능 구현(일부)    |
| 4    | 22/05/21 | 이현정 | OneVsOne 특정 주제의 응답 수 구현, 패스워드 직렬화 수정, 팔로우 기능 수정, 게시글 직렬화 수정 | OneVsOne 특정 주제의 응답 수 구현, 직렬화 수정, 패스워드 직렬화 수정, 팔로우 기능 수정, 게시글, 직렬화 수정, 유저의 영화 리스트 직렬화 마무리 |
| 5    | 22/05/22 | 박시원 | 대댓글 기능 구현, 프로필 데이터 CRUD 기능 테스트 및 구현     | 대댓글 기능 구현 완료, 프로필 CRUD 데이터 테스트 완료        |
| 6    | 22/05/22 | 이현정 | all-auth url 오버라이팅 테스트, 모델 수정(nickname 필드 삭제), 덤프 데이터 생성 파일 수정 | all-auth url 오버라이팅 테스트, 모델 수정(nickname 필드 삭제), 덤프 데이터 생성 파일 수정, 덤프 데이터 업데이트 |
| 7    | 22/05/23 | 박시원 | 메인 페이지 동작 로직 구성 및 초기 CSS                       | 메인 페이지 데이터 동작 확인 및 구성, 초기 CSS 적용          |
| 8    | 22/05/23 | 이현정 | url 전체 동작 테스트, 데코레이터 추가, 상대방 프로필 조회 url 추가, OneVsOne 주제 등록 url 추가, 친구 추천 기능 수정, 팔로잉 수 출력 | url 전체 동작 테스트, 데코레이터 추가, 상대방 프로필 조회 url 추가, OneVsOne 주제 등록 url 추가, 친구 추천 기능 수정, 팔로잉 수 출력, 평점 기능 수정(사용자 당 1번의 평점 허용) |
| 9    | 22/05/24 | 박시원 | 메인 페이지 작업 마무리, 웹 페이지 동작 버그 개선, 프로필 페이지 필수 구현 기능 구성 | 일부 동작 버그 및 오류 개선 완료                             |
| 10   | 22/05/24 | 이현정 | 영화 추천 알고리즘 구현, 탈퇴 url 생성, 친구 추천 기능 수정(고려 요소에 나이 추가), 장르별 영화 필터링 기능 추가 게시판 필터링 직렬화 생성 | 콘텐츠 기반 영화 추천 알고리즘 구현, 탈퇴 url 생성, 친구 추천 기능 수정(고려 요소에 나이 추가), 장르별 영화 필터링 기능 추가 게시판 필터링 직렬화 생성 |
| 11   | 22/05/25 | 박시원 | 미흡 구현 요소(리뷰 작성 세분화, A vs B 기능 구현, 프로필 페이지, 좋아요/위시리스트 버튼 토글링, 평점 입력 및 수정, 삭제) 등 구현 | 영화를 선택한 리뷰 작성, A vs B 기능 구현, 프로필 페이지 일부 구현 |
| 12   | 22/05/25 | 이현정 | 메인 페이지, 게시글 페이지 css 구성, 추천 알고리즘 수정(고려 요소에 싫어하는 장르 추가), OneVsOne 동작 확인, navbar 커스터 마이징, 로그인/회원가입 폼 수정, 회원 탈퇴 버튼 생성 | 메인 페이지, 게시글 페이지 css 구성, 추천 알고리즘 수정(고려 요소에 싫어하는 장르 추가), OneVsOne 동작 확인, navbar 커스터 마이징, 로그인/회원가입 폼 수정, 회원 탈퇴 버튼 생성 |
| 13   | 22/05/26 | 박시원 | 좋아요/위시리스트 버튼 토글링, 평점 입력 기능 구현, 친구 추천, 팔로우, 리뷰 정렬 기능, 댓글 수정 삭제 권한 정교화 | 버그 수정 및 좋아요/위시리스트 토글링 구현, 평점 입력 기능 구현 |
| 14   | 22/05/26 | 이현정 | 상세 영화 페이지 css 구성, 마우스 오버 효과 수정, 비밀번호 변경 url 테스트 싫어하는 장르 선택 form 생성 | 상세 영화 페이지 css 구성, 마우스 오버 효과 수정, 비밀번호 변경 url 테스트 싫어하는 장르 선택 form 생성 |

<br>

### 💎배웠던 점

| Name   | Content                                                      |
| ------ | ------------------------------------------------------------ |
| 박시원 | - 대댓글 구현을 위한 재귀 컴포넌트 작성<br />- 버튼 태그와 span태그에는 v-model이 적용되지 않는다 <br />- ‘unexpected side effect in ~ computed property 에러’<br />⇒ computed로 data를 변경하려 하면 안 된다.<br />- 깃을 활용한 협업 |
| 이현정 | - M:N 관계의 serializer 구성 방법<br />* 큰 틀의 모델 안에서 정의하려는 데이터 필드를 명확하게 정의해야함<br />* 여러 행의 데이터를 한번에 가져오기 위해서는 Many=True를 꼭 작성해야하며, 추가적인 수정이 없을 경우 read only 설정을 해주어야 함<br />- css의 구성<br />* 태그를 가로 배치하기 위해서는 여러 겹으로 둘러 쌓여져도 하나의 div 태그로 감싸야 함<br />* 반응형 레이아웃을 구성하기 위해서는 고정된 값보다는 % 로 값을 정하는 것이 필요<br />- 협업 관리<br />* git 사용 시, 각 브랜치에서 작업을 하고 마스터 브랜치에서 머지한 후, 새로운 브랜치 이용하는 것이 필요<br />* 페어와 긴밀한 소통을 통해 작업의 흐름에 맞게 푸시 및 머지 시점을 조율하는 것이 필요<br / |

<br>

### 🔥이슈 관리

| No.  | Name   | Content                                                      | Solve    | follow-up                                                    |
| ---- | ------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| 1    | 박시원 | 게시글 Detail 페이지 문제 발생<br />1. 게시글 상세 페이지에서 좋아요 누를 시 화면이 갱신이 되지 않는 문제 발생<br />2. 게시글 상세 페이지 댓글 작성 시 바로 갱신 되지 않는 문제 발생<br />3. 게시글 상세 페이지 댓글 삭제 시 바로 갱신 되지 않는 문제 발생<br />⇒ 원인은 review와 comment를 computed 속성으로 받아와서 그런 듯함 | 해결완료 |                                                              |
| 2.   | 이현정 | serializer<br/>\1. AssertionError: The field 'vote_answer_count' was declared on serializer VoteSerializer, but has not been included in the 'fields' option. => serilaizer에서 정의된 필드가 사용되지 않은 것<br/>\2. AssertionError: Expected a `Response`, `HttpResponse` or `HttpStreamingResponse` to be returned from the view, but received a `<class 'NoneType'>` => url에 엔드 슬래시 누락 | 해결완료 |                                                              |
| 3.   | 박시원 | 1. 대댓글 수정 버튼을 누를 시 기존 입력된 데이터를 받아오는 문제⇒ props속성의 데이터이기 때문에 v-model로는 해결 불가 | 해결완료 | 대댓글 생성 후 정상 출력 구현 ⇒ 자기 자신의 id를 자식에게 넘겨줘야하는데 부모의 id를 넘겨주고 있었음 |
| 4.   | 박시원 | 1. 댓글 작성을 완료해도 입력 데이터가 사라지지 않음<br />2. 대댓글 삭제를 해도 살아있는 현상 발생<br />3. 대댓글 작성/수정/삭제 권한이 모두에게 보이는 현상 발생 | 해결완료 |                                                              |
| 5.   | 박시원 | 데이터를 가져오고 저장하는 비동기 로직에 대한 이해가 부족, 뷰 라이프 사이클 훅 등 | 미흡     | 추가적인 학습 필요                                           |

<br>

### 🎨 서비스 구현

MZ 세대를 타겟팅한 기획의도에 맞게 사용자 간 친구 추천을 통해 영화 친구를 구할 수 있는 커뮤니티 기반 웹 사이트를 만들고 싶었으나 실제 친구 추천을 구현하는 수준에 그쳤음

| No   | 기능                                                         | 기능 설명                                                    | 구현 정도(⭐⭐⭐⭐⭐) | 실제 구현 수준                             |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- | ------------------------------------------ |
| 1    | 로그인                                                       | all auth를 통한 로그인 기능 구현                             | ⭐⭐⭐⭐⭐            |                                            |
| 2    | 로그아웃                                                     | all auth를 통한 로그아웃 기능 구현                           | ⭐⭐⭐⭐⭐            |                                            |
| 3    | 회원가입                                                     | 회원가입 폼 커스텀을 통한 추가 필드 구현<br />해당 정보 DB 정상 반영(adapter구현) | ⭐⭐⭐⭐⭐            |                                            |
| 4    | 회원탈퇴                                                     | 회원 탈퇴 기능 구현                                          | ⭐⭐⭐⭐⭐            |                                            |
| 5    | 마이페이지                                                   | 사용자 정보 조회, 좋아요한 영화 목록 조회, 위시리스트 영화 목록 조회, 정보 수정 기능, 싫어하는 장르 선택 기능 구현<br />=> 싫어하는 장르 영화 추천 최소화 기능 구현 | ⭐⭐⭐⭐⭐            |                                            |
| 6    | 친구 추천                                                    | 현재 사용자 지역 기준 추천, 출생 연도 기준으로 +-3 필터링    | ⭐⭐⭐⭐⭐            |                                            |
| 7    | 마이페이지                                                   | 내가 작성한 글 모아보기                                      | ⭐⭐⭐              | 내가 작성한 글 숫자 출력                   |
| 8    | 개인 맞춤 영화 추천                                          | 개인 맞춤 영화 추천 알고리즘 구현                            | ⭐⭐⭐⭐⭐            |                                            |
| 9    | 영화별 좋아요/위시리스트 버튼                                | 전체화면, 개별화면                                           | ⭐⭐⭐⭐⭐            |                                            |
| 10   | 영화 필터링(카트 컴포넌트 30개)                              | 최신순, 리뷰 많은순, 추천순 필터링                           | ⭐⭐⭐⭐⭐            |                                            |
| 11   | 개봉 예정작, 상영작 태그 스티커                              |                                                              |                  | 필터링으로 대체 구현                       |
| 12   | 검색 기능                                                    |                                                              |                  | 미구현                                     |
| 13   | 영화 마우스 커서를 올렸을 때 기능 : 줌인/ 뒤집기, 리뷰영상/제목 | 영화 카드 CSS                                                | ⭐⭐⭐⭐⭐            |                                            |
| 14   | 개별 영화의 게시글과 그 수 제공                              | 개별 영화 정보에서 해당 영화와 관련된 게시글로 이동 및 해당 숫자 출력 | ⭐⭐⭐⭐⭐            |                                            |
| 15   | New/Hot 태그 스티커                                          |                                                              |                  | 미구현                                     |
| 16   | 예매페이지 리다이렉트                                        | URL/ 아이콘 삽입                                             | ⭐⭐⭐⭐⭐            |                                            |
| 17   | 개별 영화 페이지에서 게시글 작성 기능                        |                                                              |                  | 미구현                                     |
| 18   | 영화별 게시글 생성                                           | 리뷰 게시판에서 영화정보가 있는 게시글과 그렇지 않은 글을 달리하여 작성 | ⭐⭐⭐⭐⭐            |                                            |
| 19   | 게시판 필터링 기능                                           | 최신순/좋아요순/댓글 많은 순 필터링                          | ⭐⭐⭐⭐⭐            |                                            |
| 20   | 최신글/인기글 스티커                                         |                                                              |                  | 필터링 기능으로 통합                       |
| 21   | 게시글 좋아요 기능                                           | 게시글 총 좋아요 개수 및 좋아요 등록/취소 기능 구현          | ⭐⭐⭐⭐⭐            |                                            |
| 22   | OneVsOne                                                     | 간단한 A vs B 게임을 통해 사용자의 의견을 볼 수 있는 기능 구현 | ⭐⭐⭐⭐             | 관리자 주제 추가 구현 하지 않음(준비는 함) |
| 23   | 댓글/대댓글 기능                                             | 사용자 커뮤니케이션 활성화를 위해 댓글에 댓글을 계속 작성할 수 있는 대댓글 기능 구현 | ⭐⭐⭐⭐⭐            |                                            |
| 24   | 댓글/대댓글 좋아요                                           | 댓글 총 좋아요 개수 및 좋아요 등록/취소 기능 구현            | ⭐⭐⭐⭐⭐            |                                            |
| 25   | 게시글 CRUD                                                  | 로그인한 사용자만 게시글 생성/조회/수정/삭제 가능, 자기 자신의데이터에 한해서 추가 작업 가능 | ⭐⭐⭐⭐⭐            |                                            |
| 26   | 댓글/대댓글 CRUD                                             | 로그인한 사용자만 댓글 생성/조회/수정/삭제 가능, 자기 자신의데이터에 한해서 추가 작업 가능 | ⭐⭐⭐⭐⭐            |                                            |
| 27   | 다크모드                                                     |                                                              |                  | 초기에 구현은 했으니 기능상 결함으로 제외  |
| 28   | 특정 사용자를 클릭하면 나와 취향이 얼마나 비슷한지 알려주는 기능 |                                                              |                  | 미구현                                     |
| 29   | 우하단 고정 버튼                                             | 우하단 고정 버튼 클릭 시 페이지 맨 위로 이동 가능한 기능 구현 | ⭐⭐⭐⭐⭐            |                                            |

<br>

### 🤔 느낀점

- #### 박시원

생애 첫 프로젝트를 해본 결과 여러 가지를 깨달을 수 있었습니다. 첫째, 비동기 통신과 vuex에 대해 공부가 좀 더 필요하다고 느꼈습니다. 이론적으로 충분히 이해했다고 생각했던 부분이지만, 실제 백엔드에서 넘어온 데이터를 프론트에서 다루는 과정에서 의도했던 대로 동작하지 않음을 발견할 수 있었습니다. 이를 디버깅하기 위해 많은 시간을 투자했지만 원했던 만큼 완벽하지 않았고 코드를 비효율적으로 짰다고 생각합니다.
둘째, 욕심이 처음에 너무 앞섰던 것 같습니다. 실제 구현할 수 있는 정도를 염두해두고 기본, 필수적인 부분을 먼저 구현했어야 했는데, 추가 구현을 염두해두고 프로젝트를 구성하다 보니 작업 속도도 늦고 여러모로 비효율적이었다고 생각합니다. 셋째, 간단한 로직 같아 보이지만 실제 신경써야할 부분이 꽤나 많다고 느꼈고 권한, 에러 메세지 팝업, 접근 차단 등 생각보다 고려할 점이 많았습니다.
하지만, 이번 관통 프로젝트를 통해 앞으로 주어진 문제에 대해 어떻게 접근해서 해결하는 것이 좋은지에 대해 보다 좋은 경험이 됐다고 생각합니다. 사람들이 왜 프로젝트를 해보는 것이 더 중요하다고 말하는지 조금은 알게 된 시간이었습니다. 무엇을 더 공부해야하고 어디가 부족했으며, 필요로하는 지에 대해 알 수 있게 된 좋은 경험이었습니다.



- #### 이현정

관통 프로젝트를 여러번 진행했지만, 이렇게 큰 규모의 관통은 처음이라 마음이 급했던 것 같습니다. 이전에 여러번 반복적으로 배워서 아는 내용이 많았고, 단지 그것들을 합치는 거였음에도 불구하고 마음이 급해서 차근차근 진행하지 못해서 아쉬움이 남았습니다. 일정을 잘 조율하면 계획한 대로 오류없이 모두 구현할 수 있었지만, 이슈관리의 미흡, 미숙한 협업 등이 원인이 되어 원하는 만큼의 결과를 얻지 못했습니다. 하지만, 이번 프로젝트를 통해 스스로 공식문서를 참고하여 오류를 해결하는 능력을 기를 수 있었습니다. 이전에 중구 난방으로 찾아보던 블로그 글 보다는 공식 문서를 꼼꼼히 확인하는 것이 더 낫다는 것을 깨닫는 경험을 할 수 있었습니다. 이번 프로젝트가 앞으로 진행할 여러 프로젝트의 프로젝트의 양분이 되면 좋겠습니다. 

