## 뷰의 필요성

### 보안, 필요성

#### 하나의 테이블, 혹은 여러 테이블에 대하여 특정 사용자나 조직의 관점에서 데이터를 바라볼 수 있도록 해주는 수단
#### 테이블이나 다른 뷰를 기초로 하여 생성되는 논리적인 가상 테이블이다.
#### 정의하기 위해서 사용된 테이블을 '기본 테이블(Base Table)' 이라고 한다.
#### 실제 데이터가 저장되지 않는다. 즉 별도의 기억공간이 존재하지 않는다. 

<br/>

## 시퀀스

#### 순차적인 숫자 값을 자동적으로 생성하기 위해  사용하는 오라클 객체
#### 주로 일차 값을 생성할 때나 아주 많은 데이터를 규칙성 있게 삽입할 때 사용된다.

<br/>

## 인덱스

#### 데이터를 빠르게 검색하기 위해서 아용하는 객채
#### 칼럼 또는 칼럼들의  조합에 생성한다.
#### 일반적으로 검색속도를 빠르게 하여 시스템의 전체 성능을 빠르게 하지만, 인덱스를 위한 추가공간이 필요하고 데이터의 변경작업이 자주 일어날때는 인덱스의 내용도 함꼐 수정되어야 하므로 성능이 저한된다.

<br/>
