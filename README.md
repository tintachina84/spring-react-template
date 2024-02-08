```
┌───────────────────────────────────────────────┐
                                       _       
     __ _  ___   ___  _ __ _ __ ___   (_) ___  
    / _` |/ _ \ / _ \| '__| '_ ` _ \  | |/ _ \ 
   | (_| | (_) | (_) | |  | | | | | |_| | (_) |
    \__, |\___/ \___/|_|  |_| |_| |_(_)_|\___/ 
    |___/                                      
			     🌩 𝘼𝙣𝙮𝙤𝙣𝙚 𝙘𝙖𝙣 𝙙𝙚𝙫𝙚𝙡𝙤𝙥!
└───────────────────────────────────────────────┘
```

# goormIDE
구름IDE에 오신 것을 환영합니다!

구름IDE는 개발자들을 위한 강력한 클라우드IDE입니다.

`즐거운 코딩하세요! -구름IDE팀-`

## Spring&React Boilerplate
 * 기술
	* 본 프로젝트는 `Spring Boot` `React`를 중점적으로 사용합니다.
 * 대상
 	* React와 Spring을 사용해보고 싶은 취준생
    * 풀스택을 목표로 하는 개발자 및 학생
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


## 🔧 Tip & Guide

* 명령어 기능
	* 실행 명령어를 등록해두면 우측 상단의 실행 버튼을 클릭하는 것만으로 프로젝트를 실행하실 수 있습니다.
	
* URL과 PORT
	* `프로젝트 > 실행URL과 포트`에서 포트와 URL을 확인 및 변경하실 수 있습니다.
	* 처음에는 Default 값이 들어가 있습니다.

* 유용한 단축키
	
| Shortcuts name     | Command (Mac) | Command (Window) |
| ------------------ | :-----------: | :--------------: |
| Copy in Terminal   | ⌘ + C         | Ctrl + Shift + C |
| Paste in Terminal  | ⌘ + V         | Ctrl + Shift + V |
| Search File        | ⌥ + ⇧ + F     | Alt + Shift + F  |
| Terminal Toggle    | ⌥ + ⇧ + B     | Alt + Shift + B  |
| New Terminal       | ⌥ + ⇧ + T     | Alt + Shift + T  |
| Code Formatting    | ⌥ + ⇧ + P     | Alt + Shift + P  |
| Show All Shortcuts | ⌘ + H         | Ctrl + H         |

## 💬 Support & Documentation

가이드를 보고 싶으시다면, [https://help.goorm.io/en/goormide](https://help.goorm.io/en/goormide)를 방문해주세요!