# license

> 오픈 소스 프로젝트를 위한 라이선스 파일 생성.
> 더 많은 정보: <https://nishanths.github.io/license>.

- 기본값(자동 감지된 작성자 이름 및 현재 연도)을 사용하여 `stdout`에 라이선스 출력:

`license {{라이선스_이름}}`

- 라이선스를 생성하고 파일에 저장:

`license -o {{경로/대상/파일}} {{라이선스_이름}}`

- 사용 가능한 모든 라이선스 나열:

`license ls`

- 사용자 정의 작성자 이름과 연도로 라이선스 생성:

`license --name {{작성자}} --year {{출시_연도}} {{라이선스_이름}}`
