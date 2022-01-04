## 메이븐의 핵심이 pom.xml
> 의존을 추가한다 = 모듈을 추가한다.
![Image](https://i.imgur.com/X9wljIx.png)

### 어떻게? : 원격에서 찾아오는 것!
mvn compile 명령을 통해 인터넷에서 다운로드 해옴.
![Image](https://i.imgur.com/BCKpL3m.png)

=> 요로코롬 jar이 생성

![Image](https://i.imgur.com/JjI2gUN.png)

### 폴더 구조 유의
- src\main\java : 자바 소스 코드 위치
- src\main\resources : 자원 파일
- src\main\wepapp : 웹 어플리케이션 개발 시

### 메이븐은 인텔리제이의 경우 Add Configuration에서 임포트 가능!

![Image](https://i.imgur.com/LW0y1a1.png)


## 이후, build.gradle도 add configuration에서 잡아서 쓰면 됨!
![Image](https://i.imgur.com/LUPaCd5.png)