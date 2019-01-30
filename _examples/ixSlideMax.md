---
layout: examples
title: ixSlideMax
tags: []
index: 0
---

# ixSlideMax()

슬라이드 베너 Plugin (carousel)

&nbsp;
&nbsp;

## 기본설정
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/qbyegx/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## 세로형 설정
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/vLaoov/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## 아이템을 여러개 설정
move-length:2 로 설정하여 2개씩 이동하도록 설정
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/vLzBOb/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## 이이템이 반복되지 않도록 설정
A) loop:false 설정
loop:false 로 설정하여 이이템이 반복되지 않도록 설정
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/jWjWrO/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;

B) Paging 설정
loop:false, paging:true 로 설정하여 이이템이 반복되지 않으면서 Paging 설정
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/yedeVY/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## 시작시점 설정
datum-point를 설정하여 아이템이 화면에 걸치도록 설정, 설정시 양쪽에 짤리는 아이템은 1개로 계산하면 된다.
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/Wrgexw/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## Resize 설정
"resize" Method를 이용하여 윈도우 사이즈가 변할때마다 슬라이드 사이즈를 갱신해 준다.
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/EPrYOZ/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## 반응형웹 설정
A) 미디어쿼리 사용 (IE9~)
윈도우 사이즈가 특정 구간에 들어오면 슬라이드 설정을 변경한다.
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/MKLgLK/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;

B) 미디어쿼리 미사용
미디어쿼리를 사용할수 없을때 css의 class를 따로 설정하여 처리
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/yeZwrb/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## include-margin 설정
include-margin:true를 설정하여 CSS에 설정한 아이템의 width값에 margin값을 포함하여 계산한다.
이렇게 되면 아이템의 width값은 width - margin = 아이템 사이즈가 된다.
※아이템 사이즈가 %로 들어가야 하면서 margin은 고정 px로 설정되어야 할때 설정하여 사용한다.
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/BRXjmd/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>

&nbsp;
&nbsp;

## Slide간 이벤트 연계 설정
각 Slide의 변경 상태를 다른 Slide에 적용할때 사용한다.
<iframe allowfullscreen="true" allowtransparency="true" frameborder="no" height="266" scrolling="no" src="//codepen.io/blaxk/embed/aXBzmg/?height=266&amp;theme-id=0&amp;default-tab=result" style="width: 100%;"></iframe>
