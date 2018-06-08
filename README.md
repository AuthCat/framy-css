# Framy - 매우 심플한 CSS 프레임워크

Framy는 기본적인 구성 요소들의 모음으로, 모든 웹 프로젝트에서 반응형과
현대적인 인터페이스로 웹 사이트를 개발 할 수 있습니다.

* __공식 웹사이트__ http://www.framycss.org
* __문서__ http://www.framycss.org/#/docs
* __미리보기__ http://demo.framycss.org

[![](https://data.jsdelivr.com/v1/package/npm/framy-css/badge?style=rounded)](https://www.jsdelivr.com/package/npm/framy-css)
[![npm](https://img.shields.io/npm/dt/framy-css.svg)](https://www.npmjs.com/package/framy-css)
[![npm](https://img.shields.io/npm/v/framy-css.svg)](https://www.npmjs.com/package/framy-css)
[![Bower](https://img.shields.io/bower/v/framy-css.svg)]()
[![npm](https://img.shields.io/npm/l/framy-css.svg)]()

## 사용 방법

### CDN

최신 버전을 유지하면서 사용:
```
// CSS
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/framy-css@latest/dist/css/framy.min.css">

// JS
<script src="//cdn.jsdelivr.net/npm/framy-css@latest/dist/js/framy.js"></script>
```

CSS flexbox 그리드만 사용:
```
// Just the CSS flexbox grid
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/framy-css@latest/dist/css/framy.grid.min.css">
```

또는 _latest_ 부분에 특정 버전을 삽입하여 사용:
```
// Just the CSS flexbox grid
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/framy-css@2.8.5/dist/css/framy.grid.min.css">
```

### npm을 통한 설치
```
npm install framy-css
```
CSS와 스크립트를 아래와 같이 삽입:
```
<link rel="stylesheet" href="node_modules/framy-css/dist/css/framy.min.css">

<script src="node_modules/framy-css/dist/js/framy.js"></script>
```

### Bower를 통한 설치
```
bower install framy-css
```
CSS와 스크립트를 아래와 같이 삽입:
```
<link rel="stylesheet" href="bower_components/framy-css/dist/css/framy.min.css">

<script src="bower_components/framy-css/dist/js/framy.js"></script>
```

## 개발
필요한 항목:
* [git](https://git-scm.com/)
* [npm](https://www.npmjs.com/get-npm)

Repository를 Clone 합니다. [git](https://git-scm.com/):
```
git clone https://github.com/aaroniker/framy-css.git
```
이제 [npm](https://www.npmjs.com/get-npm)을 설치해 주어야 합니다.
```
npm install
```
아래 명령어를 따라서 실행할 수 있습니다.
```
// Load & compile all icons to an icon font from ./src/icons/*.svg to ./dist/fonts/*
npm run icons

// Compile all .scss files to ./dist/css/framy.min.css
npm run css

// Compile all grid related .scss files to ./dist/css/framy.grid.min.css
npm run css-grid

// Watch all .scss files and recompile ./dist/css/framy.min.css & ./dist/css/framy.grid.min.css if they changed
npm run watch-css
```

## 리소스

* 인터페이스 폰트: https://github.com/rsms/inter
* Ikons(내장 아이콘) http://ikons.piotrkwiatkowski.co.uk
