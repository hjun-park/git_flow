## git flow
RB-1.0.0 그리고 배포용 master 브랜치 2개가 있다고 가정,

<br>

### 01.

RB-1.0.0 에 대해서 새로운 기능을 개발하려면
해당 브랜치를 새로운 이름으로 브랜치 생성 
> ex) feat/add_count2

<br>

### 02. 

새로운 기능 개발이 완료되면 
<br>
> RB-1.0.0 <- feat/add_count2 병합

<br>

### 03.

테스트 후 배포를 하기 위해서는 
> master <- RB-1.0.0 병합

<br>

### 04. 
추후에 새롭게 기능 추가 하고싶으면 상황에 따라 버전 업 후에 01부터 반복
> RB-major.minor.patch 
