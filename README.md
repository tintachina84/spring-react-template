
 * 상세 설명
	* 본 프로젝트는 스프링 부트와 리액트의 보일러플레이트입니다.
    * 프로젝트 실행법에 대해서는 아래 Usage를 참고해주세요.
    * 스프링은 8080, 리액트는 3000번 포트에서 실행되고, 도메인은 `프로젝트 > 실행URL과포트` 에서 확인하실 수 있습니다.
    * 자유롭게 활용해주세요!
 * 폴더구조
 ```
/back
	/src
        /main
            /java
                /com
                    /example
                        /[name]
                            [nameController].java
                            [nameService].java
                        App.java
            /resources
        /test
    /target
/front
    /public
	/src
        /api
        /components
            [name]
        /config
        App.js
    .env.development
 ```

## 🎨 Usage      
0. [구름 블로그 포스팅](https://blog.goorm.io/springreact/)으로 실행법 확인

1. URL과 포트 확인
   1. 상단 메뉴바의 `프로젝트 > 실행URL과포트` 클릭하기
   2. 8080포트와 3000포트로 도메인이 등록되어있는지 확인하기
   3. 등록되어 있지 않다면 등록하기
   4. 등록된 도메인으로 `front/.env.development`에 주소 바꾸기
   
2. 의존성 확인
   1. front 폴더에 `node_modules`가 설치되어 있는지 확인하기
   2. 설치되어 있지 않다면 front 폴더에서 `npm install`
   
3. 프로젝트 시작하기
   * 스크립트 이용하기
       * `./start.sh`를 터미널에 입력하기
   * 직접 입력하기
       * `cd front && npm run start`
       * `cd back && ./mvnw spring-boot:run`
   * 명령어 기능 이용하기
       * 우측 상단의 `Run project` 실행 버튼 클릭

4. 프로젝트 종료하기
    * 스크립트 이용하기
        * `./exit.sh`를 터미널에 입력하기
    * 직접 종료하기
        * `netstat -nlp | grep :3000`를 입력하여 포트 확인
        * `kill -9 ${port}`
        * `netstat -nlp | grep :8080`을 입력하여 포트 확인
        * `kill -9 ${port}`₩
