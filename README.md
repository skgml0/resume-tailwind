# Resume

## 목적

멋쟁이 사자 웹 프론트엔드 1기 과정 중 진행한 tailwind 이력서 대회 참가

## git 배포

https://skgml0.github.io/resume-tailwind/

## Tailwind란?

공식 사이트 : https://tailwindcss.com/

Utility-First의 편리함과 빠른 개발이 가능하다. 
스타일 코드도 HTML코드 안에 있기 때문에 HTML과 CSS 파일을 별도로 관리할 필요가 없다.


## 설치

- npm으로 Tailwind CSS 설치하기

```npm install tailwindcss@latest postcss@latest autoprefixer@latest```

- PostCSS 플러그인에 Tailwind CSS 추가하기

``` // postcss.config.js 등의 postcss 설정 파일
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},  
  },
};
```
- 설정 파일 생성하기

```npx tailwindcss init```

위의 명령어를 입력하면 프로젝트 루트에 아래의 설정 파일이 생성된다. 기본 스타일이나 플러그인 등을 설정할 수 있는 파일이다.
```
// tailwind.config.js
module.exports = {
  purge: [],
  darkMode: false, 
  // or 'media' or 'class' 
  theme: {
    extend: {},
  },
  variants: {},  
  plugins: [], 
};
```
