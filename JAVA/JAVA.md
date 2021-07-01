# Today I Learned

  + 단축기

##### Ctrl+Shift+L 단축기 전체 목록보기

##### Ctrl+ +,- 폰트 크기 증가/감소

##### Ctrl+D 한 줄 삭제

##### Ctrl+alt+ ↓ (down) 행단위 복사

##### alt+shitf+A 멀티컬럼 편집

##### alt+up ,down 행단위 이동

##### tap 입력 들여쓰기

##### shift+tap 내여쓰기

##### Ctrl+i 자동 들여쓰기

##### Ctrl+/ , /* */ 주석(토글)

##### Ctrl+Space 자동완성

## 소스파일 가져오기 

###### Package Explorer에서 우 클릭(빈화면에서 우클릭) → Import 클릭 → 맨위에 General → Existing Projects into Workspace 기존의 프로젝트를 workspace로 가져오기 → Browse.. → 폴더선택 → 옵션에 Copy projects into workspace를 체크 → Finish !

## 소스파일 내보내기

###### Package Explorer에서 우 클릭(빈화면에서 우클릭) → Export → General → Archive File → 프로젝트 선택 → Save in Zip format( Zip형식으로 압축)





1. 변수(variable)란 ?

  ###### 하나의 값을 저정할 수 있는 메모리 공간!

2. 변수의 선언

  - 변수의 선언 이유 : 값(data)을 저장할 공간을 마련하기 위해서
    - 변수의 선언 방법 : 변수타입 변수이름 ; [ 세미콜론 ]

int age ; // 정수(int)타입의 변수 age를 선언


3. 변수에 값 저장하기

    ① 변수에 값 저장하기 ( '=' 는 등호가 아니라 대입 )
     ###### int age ; // 정수(int)타입의 변수 age를 선언
     ###### age = 25 ; // 변수 age에 25를 저장
     ###### int age = 25; // 위의 두 줄을 한 줄로

    ② 변수의 초기화 - 변수에 처음으로 값을 저장하는 것
     ###### [주의] 지역 변수는 읽기 전에 꼭! 초기화해야 함.
     ###### int x = 0; // 변수 x를 선언 후, 0으로 초기화
     ###### int y = 5; // 변수 y를 선언 후, 5로 초기화
     ###### int x = 0, y = 5; // 위의 두 줄을 한 줄로
     
4. 변수의 값 읽어오기

  ① 변수의 값이 필요한 곳에 변수의 이름을 적는다
     ###### int x = 0, y = 5; // 위의 두 줄을 한 줄로
    
