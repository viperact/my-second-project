# TIL

## 리눅스 명령어

1. ls

   > list (목록표시)

2. cd

   > change directory (작업 경로 변경)

3. rm

   > remove (파일 삭제)

4. mkdir

   > make directory (작업목록 생성)

5. rmdir

   > remove directory (작업목록 삭제)

6. touch

   > 파일생성

7. cat
   > 파일의 내용 출력

## Git

1. init

   > git 생성

2. add<파일명>

   > staging area로 이동

3. commit -m <메세지>

   > Repository로 이동

4. push <원격저장소><브랜치>

   > 원격(Github)으로 이동

5. pull <원격저장소><브랜치>

   > 원격에서 로컬로 복사

6. clone <원격저장소><브랜치>

   > 원격에서 로컬로 복제

7. status

   > staging area의 상태 (git의 상태)

8. log

   > repository의 상태

9. git commit --amend

   > 바로 전commit과 staging area의 merge를 할때

10. git restore --staged <파일명>
    > staging area에 있는 파일을 working directory로 가져옴

![git cheat sheet](asset/gitcheatsheet.gif)

| 번호 | 이름   | 지역 |
| ---- | ------ | ---- |
| 111  | 홍길동 | 서울 |

문자코드와 인코딩

> 문자코드 : 문자와 숫자를 1:1 매핑시켜놓은 값이다.
> 컴퓨터가 사용하는 0과 1로 변환할때 사용되는 기준

진법(진수)

> 10 (사람), 2, 8, 16

> 기계: 0과 1만사용

Bit와 Byte

> Bit: 0과 1만 표현

> Byte: 비트 8개를 칸으로 구분지은것

진법의 범위

> 2진법: 0과 1

> 8진법: 0~7

> 10진법: 0~9

> 16진법 0~9, A~F - A(10) B(11) C(12) D(13)
> E(14) F(15)

숫자 5를 2진법으로 표현 : 101

문자 A(65)를 2진법(Byte)으로 표현 :
| 0 | 1 | 0 | 0 | 0 | 0 | 0 | 1 |
|---|---|---|---|---|---|---|---|

- 'a': 97
- 'A': 65
- 'O': 48

2진법을 10진법으로 바꾸기

> 1101₂ = 1x2³ + 1x2² + 0x2¹ + 1x2⁰

      =1x8 + 1x4 + 0x2 + 1x1
      =8 + 4 + 1
      =13

8진법을 10진법으로 바꾸기

> 257₈ = 2x8² + 5x8¹ + 7x8⁰  
> =2x64 + 5x8 + 7x1  
> =128 + 40 + 7  
> =175

16진법을 10진법으로 바꾸기

> 2AD₁₆ = 2x16² + Ax16¹ + Dx16⁰  
> =2x256 + 10x16 + 13x1  
> =512 + 160 + 13  
> =685
