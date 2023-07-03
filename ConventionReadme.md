# Coommit Convention

## **<좋은 Git 커밋 메시지의 7가지 규칙>**

1. **제목과 본문을 한 줄 띄워 분리하기**
2. **제목은 영문 기준 50자 이내로**
3. **제목 첫 글자를 대문자로**
4. **제목 끝에 . 금지**
5. **제목은 명령조로**
6. **Github - 제목(이나 본문)에 이슈 번호 붙이기**
7. **본문은 영문 기준 72자마다 줄 바꾸기**
8. **본문은 어떻게보다 무엇을, 왜에 맞춰 작성하기**

## **<커밋 메시지 구조>**

```bash
type: Subject

body

footer
```

## **<타입>**

- **feat : 새로운 기능 추가**
- **fix : 버그 수정**
- **docs : 문서 수정**
- **style : 코드 formatting, 세미콜론(;) 누락, 코드 변경이 없는 경우**
- **refactor : 코드 리팩터링**
- **test : 테스트 코드, 리팩터링 테스트 코드 추가(프로덕션 코드 변경 X)**
- **chore : 빌드 업무 수정, 패키지 매니저 수정(프로덕션 코드 변경 X)**
- **design : CSS 등 사용자 UI 디자인 변경**
- **comment : 필요한 주석 추가 및 변경**
- **rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우**
- **remove : 파일을 삭제하는 작업만 수행한 경우**
- **!BREAKING CHANGE : 커다란 API 변경의 경우**
- **!HOTFIX : 급하게 치명적인 버그를 고쳐야 하는 경우**

****<커밋 메시지 예시>****

```bash

[FEAT]: (CORE)코어 기능 추가
[FIX]: 00기능 spaceing Bug fix
[DOCS]: readme ETC 수정
![HOTFIX]: APP Crash main View oo기능 수정


```

![image](https://github.com/Nueyne-APP/.github/assets/83629930/8ad5da0c-b21f-4519-b8c7-dcfee58b4114)