---
layout: entry
title: 아이콘을 그리기 전에 고려할 것들
description: 아이콘을 그리기 전에 고려해야할 아이콘의 크기, 아이콘의 용도, 아이콘의 스타일을 이야기한다. 너무 당연한, 기초적인 내용이지만 그래서 막상 아이콘을 그리다보면 쉽게 간과하게 되는 내용들이다. 그렇기 때문에 가장 강조하고 싶은 내용이기도 하다.
publish: true
---

아이콘을 그리기에 앞서 아래와 같은 요소들을 생각해야 한다.

   * 아이콘의 크기
   * 아이콘의 용도
   * 아이콘의 스타일

## 아이콘의 크기

대체로 아이콘의 크기는 디자인적 요소라가 보다는 아이콘이 들어갈 장소에 맞게 결정된다. 일반적인 iOS UI에서는 [44-50px](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/BarIcons.html), android UI 에서는 [32dp](http://developer.android.com/design/style/iconography.html)를 사용한다. 그 외에도 웹이나 커스텀 UI등 아이콘이 들어가게 되는 맥락은 여러가지가 있으므로 자신의 프로젝트에 맞는 아이콘 크기를 결정하면 된다. 하지만 다양한 환경에도 불구하고 일반적인 아이콘 크기는 16px, 20px, 24px, 32px, 48px로 수렴되곤한다. 리사이징과 pixel perfection 등을 고려했을 때 가장 깔끔한 결과물을 낼 수 있 크기이므로 무리가 없다면 저 크기나 혹은 그 배수 크기로 아이콘을 그리기를 추천한다.


## 아이콘의 용도

아이콘의 용도 또한 디자이너의 의도보다는 프로젝트의 성격에 좌우되는 요소다. 지금 그리는 아이콘이 어디에 쓰일지를 생각해보는 일이다. 다 비슷비슷해 보이는 아이콘이지만 용도에 따라 디자인 기획이 크게 달라질 수 있다. 아이콘의 용도에는 대강 이런 것들이 있다. 

##### 정해진 한 곳에서만 쓰일 때

개인 블로그나 홈페이지의 메뉴 아이콘 같은 것을 예로 들 수 있다. 아이콘이 다른 곳에 사용될 가능성이 낮고, 정확히 어느 위치에 어떤 맥락으로 사용될 지 아는 경우이다. 이때는 아이콘이 놓일 공간에 가장 어울리는 디자인을 하면 된다. 

##### 하나의 제품이지만 여러 OS에서 쓰일 때 ( web, ios, android...)

아이콘이 갖는 함의는 동일하나 예측할 수 없는 다수의 공간에서 사용되는 경우다. 이때는 아이콘이 다른 크기로 제작되어야 할 수 있고, 특정 메타포의 경우에는 OS에 따라 다른 형상을 지닌다는 것을 염두해 디자인해야 한다.

##### 한 브랜드를 대표하며 여러 곳에서 쓰일 때

말 그대로 한 브랜드를 대표하는 아이콘이다. 이때는 아이콘이 다른 아이콘과 구별되는 대표성을 지닐만한 독특한 스타일을 지녀야 하며, 아이콘이 들어가게될 맥락을 미리 예측할 수 없다는 점을 유의해야한다. 

##### 아이콘 그 자체를 위한 완결된 셋트

주로 아이콘 디자이너들이 웹 상에서 판매하는 아이콘들이 이 경우에 속한다. 아이콘이 사용될 맥락을 미리 알 수 없고, 아이콘이 그만의 스타일을 지니며 set 로 제작된 다는 점은 위와 같지만 브랜드가 아닌 아이콘 자체가 스스로를 대변한다는 차이가 있다.


이처럼 아이콘이 어떤 용도로 사용될지에 따라 미리 계산할 점들과 접근 방식이 달라진다. 위의 예시들은 지금 생각나는 것들을 적은 것이고, 상황에 따라 더 다양한 용도의 아이콘이 있을 수 있다. 용도를 미리 생각하고 아이콘 디자인에 접근하면 나중에 발생하는 리사이징, 추출 방식의 변화, 아이콘 종류의 확장 등에 유연하게 대처 가능하다는 장점이 있다. 


## 아이콘의 스타일
 
아이콘의 크기와 용도가 정해지면 디자인 방향성을 정한다. 스스로 아이콘의 스타일을 떠올리기 어렵더라도 [dribbble](https://dribbble.com/search?q=icons), [behance](https://www.behance.net/search?field=131&search=icons)등 그래픽 사이트에서 검색해보면 다양한 아이콘 스타일들을 볼 수 있으니 참고해서 자신이 원하는 스타일이 어떤 것인지 구상해본다.

아이콘에는 여러 스타일이 있지만 크게 <q>속이 찬 아이콘</q>과 <q>속이 빈 아이콘(라인 아이콘)</q>으로 나누어볼 수 있다.[^icons_style] 이후의 포스팅에서는 요즘의 추세에 맞게 <q>라인 아이콘</q>에 초점을 맞춰 이야기해보려고 한다.

### 라인 아이콘 (Hollow icons, Line icons)
라인 아이콘의 스타일에는 세가지 요소가 크게 작용한다. 바로 <q>선의 굵기</q>, <q>선 끝 처리</q>, <q>모서리 처리</q>가 그것이다.

#### 선의 굵기
위에서 이야기한 16px, 20px,  24px, 32px, 48px 크기의 아이콘이라면 선의 굵기는 대게 1px, 2px, 3px 로 결정된다. 가장 얇은 선과 가장 굵은 선이 겨우 2px 차이밖에 나지 않으니 별 차이가 있으랴 싶지만 아이콘 전체의 크기가 20 - 50px임을 생각해보면 꽤 큰 차이다.

<div class="center">
<img src="https://33.media.tumblr.com/253f8a46ce9c0a76a7696f7994410e3d/tumblr_inline_n8pay9k2Ne1stjbwg.png" style="width:337px;"></div>

선 굵기는 꼭 한가지 일 필요는 없다. 표현하고자 하는 스타일에 따라 두가지 선을 쓰면서 굵은선은 외곽선, 얇은 선은 묘사선 등으로 사용하기도 한다. 

리사이징이 필요한 아이콘의 경우에는 아이콘 크기와 더불어 선의 굵기도 잘고려해야 crisp 한 결과물을 얻을 수 있다. 만약 아이콘을 처음 그리는 경우라면 어떤 점을 고려해야하는지 막막할 수도 있다. 그런 분들을 위한 더 구체적인 설명은 뒤이은 포스팅에서 실제 그리는 법과 함께 이야기해보겠다.

#### 선 끝 모양

<img src="/images/2014-07-14/stroke.png" style="width:190px;">

선 끝 모양에는 크게 둥근 모양과 각진 모양으로 나눌 수 있다. 이 끝을 어떻게 처리하느냐에 따라 아이콘의 인상이 달라진다.

#### 모서리 모양
         
모서리의 곡률(Radius)이다. 모서리가 직각일 수도 있고, radius가 2px, 3px일 수도 있다.

<div class="center">
<img src="https://33.media.tumblr.com/a105ec4ccef45ead03cbc180eb89fcb8/tumblr_inline_n8pcn4rwtD1stjbwg.png" style="width:329px;"></div>

보는 바와 같이 곡률이 날카로울 수록 세련된 인상을, 부드러울 수록 귀여운 인상을 준다.

아이콘 그리기에 서투른 사람들은 위에서 말한 세가지 요소를 규칙으로 정해두지 않고 여러 스타일을 혼용해서 쓰는 경우가 많다. 이 세가지만 같은 스타일을 유지해도 아이콘의 통일성과 완성도가 높아지므로 아이콘을 그릴때 꼭 유념해서 작업하도록 하자. (나는 프로젝트마다 위 세요소를 포스트잇에 적어서 모니터에 붙여놓는다.)

아이콘을 그리기 전에 알아야할 기초적인 내용은 모두 이야기했다. 다음 포스팅에서는 간단한 아이콘을 함께 그려보려고 한다.

[^icons_style]: iOS7이 나오기 전까지 대부분의 아이콘은 <q>속이 꽉 찬 아이콘</q>이었다. 때문에 속이 찼다는 스타일을 따로 지칭하지 않고 모두 <q>icons</q> 라고 칭했는데, iOS7에 선으로만 이루어진 아이콘이 등장하면서 이를 따로 <q>속이 빈 아이콘, 라인 아이콘(hollow icons, line icons)</q> 이라고 부르게 되었다. 본문에서는 iOS7 이전의 아이콘을 임의로 <q>속이 찬 아이콘</q>이라고 지칭했다.