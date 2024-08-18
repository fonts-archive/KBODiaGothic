# KBO 다이아고딕체

[배포처 바로가기](https://www.koreabaseball.com/Reference/etc/KboFont.aspx)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `KBO Dia Gothic`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'KBO Dia Gothic';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'KBO Dia Gothic';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'KBO Dia Gothic';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/KBODiaGothic-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/subsets/KBODiaGothic-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/KBODiaGothic/subsets/KBODiaGothic-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "KBO Dia Gothic", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
KBO 다이아고딕의 지적 재산권은 (사)한국야구위원회에 있습니다. 
KBO 홈페이지를 통해 배포되는 KBO 글꼴은 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 재배포가 가능합니다. 
(단, 파일의 수정 및 폰트 자체를 판매하는 행위는 불가합니다.) 
정확한 사용 조건은 KBO 다이아고딕 라이선스를 참고하시기 바랍니다. 
글꼴 라이선스 문의 : 
kbop@koreabaseball.or.kr
```
