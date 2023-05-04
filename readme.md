# 할일

- [ ] 알림
    - [ ] 호감표시할 때 알림생성
    - [ ] 호감사유변경할 때 알림생성
    - [ ] 알림목록
    - [ ] 알림목록 확인 시 마다, 아직 readDate 가 null 인것들만 추려서 날짜갱신
    - [ ] 상단바에 아직 읽지 않은 알림이 존재하는지 인디케이터로 표시
- [ ] 호감에 대한 수정/삭제 쿨타임
    - [x] 설정정보 가져오기
    - [x] 호감표시/호감사유변경 시에 modifyUnlockDate 갱신(현재날짜 + 쿨타임)
    - [x] UI에서 쿨타임 안차면 수정/삭제 못 하도록
    - [x] UI에서 남은시간 표시
    - [x] LikeablePersonService::canCancel 에 쿨타임 체크 추가
    - [x] LikeablePersonService::canModifyLike 에 쿨타임 체크 추가
    - [x] TC : 호감사유를 변경하면 쿨타임이 갱신된다. 실패, 해결
- [x] 회원가입 폼
    - [x] 로그인 상태에서 들어올 수 없다.
    - [x] 폼이 있어야 한다.
    - [x] input[name="username"] 필드가 있어야 한다.
    - [x] input[name="password"] 필드가 있어야 한다.
    - [x] 폼 체크
- [x] 회원가입 폼 처리
    - [x] 로그인 상태에서 들어올 수 없다.
    - [x] 유효성 체크를 해야 한다.
    - [x] member 테이블에 회원이 저장되어야 한다.
    - [x] 처리 후에 / 로 이동해야 한다. 302
    - [x] 회원가입이 완료되었습니다. /usr/member/login 으로 302
- [x] 로그인 폼
    - [x] 로그인 상태에서 들어올 수 없다.
    - [x] 폼이 있어야 한다.
    - [x] input[name="username"] 필드가 있어야 한다.
    - [x] input[name="password"] 필드가 있어야 한다.
    - [x] 폼 체크
- [x] 로그인 폼 처리(스프링 시큐리티가 알아서 해줌)
    - [x] 세션에 데이터가 들어있는지 확인
- [x] 레이아웃 네비바 구현
    - [x] 로그인 버튼
    - [x] 회원가입 버튼
    - [x] 로그아웃 버튼
- [x] 로그인 후에는 내비바에 로그인된 회원의 username 이 보여야 한다.
- [x] 정적파일 정리
    - [x] 두루두루 사용되는 CSS 를 common.css 로 모으기
    - [x] 두루두루 사용되는 JS 를 common.js 로 모으기
- [x] toastMsg 에 ttl 기능 추가
- [x] 인스타그램 회원정보 입력
    - [x] 입력한 인스타그램 ID가 이미 존재하더라도, 그것의 성별이 아직 U 이면 연결가능
    - [x] 로그인한 사람만 가능
    - [x] 아이디
    - [x] 성별
- [x] 인스타그램 회원정보 입력 폼 처리
    - [x] 로그인한 사람만 가능
    - [x] 아이디
    - [x] 성별
    - [x] 회원과 인스타회원의 연결
    - [x] 성공했을 때 호감표시 페이지로 이동
- [x] 본인이 좋아하는 사람 등록 폼
    - [x] 본인의 인스타그램 회원정보 입력을 완료한 사람만 가능
    - [x] 인스타그램 아이디
    - [x] 매력포인트(외모, 성격, 능력)
- [x] 본인이 좋아하는 사람 등록 폼 처리
    - [x] 아직 우리 서비스에 등록되지 않은 인스타 유저에게도 호감표시 가능
- [x] 엔티티 클래스의 중복로직 제거