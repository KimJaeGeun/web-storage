# web-storage
web storage 공부용

목차
1. [cookie](#cookie)
2. [session](#session)
3. [localstorage](#localstorage)


## cookie
- 개요
    - 브라우저에 저장되어지는 문자열 데이터파일
    - key=value로 이루어져있으며, 최대 크기는 4kb
    - 클라이언트 로컬에 저장되어지기에 만료기간 설정이 없는 경우 영구적으로 존재

- 구성요소
    1. key
        - 쿠키의 value에 접근할 수 있게 지정하는 유니크 인자
    2. value
        - key를 통하여 접근할 수 있는 쿠키 값
    3. 옵션
        1. path
            - cookie에 접근가능한 경로 설정
            - 기본값은 현재 경로
            - 현재경로 하위의 절대경롤 의미하며, 해당 경로 이하의 경로한정으로 cookie에 접근 할 수 있다.
        2. domain
            - 접근가능한 도메인 설정
            - 기본값은 쿠키를 설정한 도메인으로 지정
            - 서브도메인 또한 접근이 불가
                - ex) example.com - 쿠키생성 도메인, sub.example.com - example.com에서 생성한 쿠키는 접근 불가
        3. expire
            - 쿠키 만료 
            - example.com

