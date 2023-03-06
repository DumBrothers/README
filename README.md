# README
## Git 브랜치 전략(current)

- Git branch 설명
    - master(main) : 공식 릴리즈를 기록하는 브랜치, prod 배포용 브랜치
    - release: 출시 버전을 준비하는 브랜치 ()
    - develop: 개발용 브랜치, 이슈로 브랜치 생성 후 개발
    - feature-issue#[number]: github 에서 개발 이슈 생성 후 나온 번호로 브랜치 이슈를 만듬
    - hotfix#[release-version]: master, release 로 바로 Push 하게되는 긴급 수정 브랜치
- Commit Type
    - Add: 기능 추가
    - Remove: 삭제
    - Fix: 기능 수정
    - Refactor: 리펙토링
    - Bug: 버그 수정
    - Style: 코드 포맷팅, 주석, 세미콜론 누락, 코드 변경이 없는 경우
    - Test: 테스트 코드, 리펙토링 테스트 코드 추가
    - Docs: 문서 수정(markdown..)
    - Etc:  그외
