# React Native Weather App

- 사용한 툴
    - 환경 : NodeJS
    - expo 
        - `npm install expo-cli --global`
        - 리액트 네이티브로 앱을 쉽게 만들 수 있도록 도와주는 툴
        - xcode, android studio를 사용할 필요 없이 iOS, Android 네이티브 앱을 만들 수 있다.
        - expo client로 앱을 빠르게 테스트 할 수 있다.
        - 앱 배포에 용이 : 코드를 업데이트하면 서버에 있는 코드가 업데이트된다. => client앱을 열때마다 서버에서 새로운 버전의 코드를 다운받아서 실행된다.
        - `Hot Reloading` : 코드에서 변경된 부분만 빠르게 리로딩된다.
        
    - React Native
        - 리액트 웹 앱을 빌드할 수 있게 도와주는 <b>UI 라이브러리</b>
        - html, css 어플리케이션을 생성하지 않는다.
        - 구동 원리 : JSX로 개발하고, 마지막에 컴파일링 할 때 iOS(Object-C),Android(Java) 네이티브 코드로 변환이 되어서 실행이 된다. 
        - 장점 : 커뮤니티가 크다. / iOS-Android간에 코드를 JSX로 공유할 수 있다. / 레이아웃을 flex box로 구현할 수 있다.

<br>

- React Native Project 시작
```
expo init weather-app
cd weather-app
yarn start //expo start
```
   