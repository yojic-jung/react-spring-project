## 리액트 웹서버 스펙
node -v  
v16.13.1  
npm -v  
8.3.0  

## "리액트-스프링부트 첫번째 연동" 커밋 내용
### 리액트 및 리액트 라이브러리 설치 명령어
npm install -g create-react-app  
npm install react-router-dom  
### 반영 내용
리액트 라우터 설정  
"react-router-dom": "^6.2.1" (package.json 파일에 설정)  
리액트 웹서버 was 프록시 설정  
"proxy": "http://localhost:8080" (package.json 파일에 설정)  
