# Java IoList Project
- java, Oracle을 사용한 Console Project
- eClipese 의 Console 환경에서 java를 사용한 DBMAS 핸들링
- 상품관리, 고객관리, 상품구매(장바구니)를 관리하는 Project

## 필요한 3rd party LIB
- ojdbc*.jar, mybatis.jar

## Maven Project
- java project 로 설정된 기본 형식을 Maven Project 로 변환한다 : 프로젝트에서 우클릭 > project > configure > convert maven project
- pom.xml 이라는 xml 파일이 생성된다

### POM.xml
- POM : `Project Object Model` 프로젝트에 필요한 3rd JDK를 쉽게 관리하기 위한 도구
- Maven Projcet 를 컴파일하고, Build 하는데 필요한 설정 정보를 담고있는 파일