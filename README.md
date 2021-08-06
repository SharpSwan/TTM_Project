# TTM BitCoin RSI Alert v.1.0 21/06/30

* 현재 발견된 오류

1.텔레그램 토큰 입력시 프로그램 꺼짐

→ 자기가 생성한 텔레그램 봇에게 아무 메세지나 한개 보내놓고 다시 시도해보세요

<br>
<br>

## Introducion

---
<img src ="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMimage.gif?raw=true">

<br>
<br>

안녕하세요 TTM 코인 RSI 알리미 개발자입니다. ***이 프로그램은 바이낸스와 업비트의 RSI를 실시간으로 계산하여 알림을 받을 수 있는 프로그램***입니다. RSI(relative strength index, 상대강도지수)는 주식, 선물, 옵션 등의 기술적 분석에 사용되는 보조지표로 1978년 미국의 월레스 와일더(J. Welles Wilder Jr.)가 개발하여 오랜 시간의 테스트를 견뎌내고 현재까지도 많이 사용되고 있습니다. 이 프로그램은 RSI를 활용하여 비트코인 매매를 하는 분들에게 편의성을 제공해드리고자 합니다.

RSI에 대한 글은 저의 [네이버 블로그](https://blog.naver.com/qqwert21) 를 참고해주세요.

후원은 강요가 아니니 편하게 사용하신 후 따뜻한 댓글 하나만 부탁드립니다. 😊

<br>
<br>


## Purpose of this porject

---

이 프로젝트의 목적은 불편함의 개선과 편의성의 제공입니다. 매매를 하면서 여러가지 불편함이 있었습니다. 시간봉 별로 RSI를 확인하고 싶을때, 차트를 계속 바꾸는게 불편했습니다. 다른 종목의 가격와 RSI를 알고 싶을때도 불편했습니다.

TTM RSI 알리미를 사용하시면 

**1. RSI를 매번 차트를 바꾸는 것보다 훨씬 편하게 확인할 수 있습니다.**

**2. 여러 종목의 가격과 RSI를 동시에 확인할 수 있습니다.**

**3. RSI를 활용한 매매 전략의 중요한 30, 70 지수에서 PC와 핸드폰, 스마트워치로 알림을 받을 수 있습니다.**

여러분들의 매매에 많은 도움이 되리라 생각합니다.

<br>


## How to use it?

---

**TTM이 작동하기 위해서는 코인 종류 선택, 시간봉 선택이 필요**합니다.

그리고 **알림 설정을 위해선 텔레그램 토큰 입력이 필요**합니다.

아래 세팅을 맞추시면 작동합니다.

- [TTM설정(코인 종류, 텔레그램 토큰 입력)](#암호화폐-설정)

- [시간봉 선택](#시간봉-선택)

- [거래소 선택](#거래소-선택)

<br>

## TTM 코인 RSI 알리미 구성 (클릭시 해당 부분으로 이동)

---

### 1.메인화면

- [알림](#텔레그램-알림) : 텔레그램, TTM 프로그램 알림
- [항상 위](#항상-위) : 항상 위 모드
- [시간봉 선택](#시간봉-선택) : 1분, 5분, 15분, 1시간, 4시간 선택 가능
- [거래소 선택](#거래소-선택) : 바이낸스, 업비트 선택 가능

### 2.배너

- [배너](#배너) : 배너 종류 설명

### 3.메뉴

- [TTM 설정](#암호화폐-설정): 암호화폐 종류 선택, 텔레그램 토큰 입력
- [개발자](#개발자) : 개발자 연락 방법
- [도움말](#도움말) 
- [후원](#후원)
- [about](#about)


### 프로그램 필요 사양

---

|구분|지원|미지원|
|:---:|:---:|:---:|
|OS|윈도우10|윈도우7, macOS|
|용량|87MB 이상||
|램|100MB 이상||

---

### **1. 메인화면**

<br>

### **텔레그램 알림**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TeleAlert.jpg?raw=true">

<br>

체크하면 텔레그램 알림이 옵니다. 그 전에 설정에서 **봇 토큰을 입력해야합니다.**
별도로 ID 입력은 필요 없으나 **자신이 만든 봇에 메시지를 보내놓으면 ID를 인식** 하여 답장으로 알림을 보냅니다. 매번 이렇게 할 필요는 없고 ID를 찾지 못하여 프로그램이 실행되지 않는 경우에만 한번씩 해주시면 됩니다. 알림은 RSI 30 밑으로 하락, 30위로 돌파 70 밑으로 하락, 70위로 돌파 구간을 나눠서 알림을 보냅니다. 

<br>

### **TTM 알림**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMalert.jpg?raw=true">

<br>

프로그램 자체 알림입니다. 텔레그램이 아닌 알림을 받고 싶으시면 체크하시면 됩니다. 비프음과 함께 알림이 오는데 알림 구간에서 오래 걸쳐있으면 알림 창이 너무 많이 뜰 수 있으므로 주의해주세요. 

<br>

### **항상 위** 

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMalwaysTop.gif?raw=true">

박스를 체크하면 TTM 프로그램이 항상 위로 고정됩니다. 프로그램의 목적상 항상 위로 고정시켜서 PC로 다른 작업을 하거나, 차트를 조금 덜 보기 위함이므로 꼭 필요한 기능이라 생각하여 넣었습니다.

<br>

### **RSI**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/color.gif?raw=true">

**과매수** 구간에 진입하면 글씨가 **빨간색**으로 바뀝니다.

**과매도** 구간에 진입하면 글씨가 **파란색**으로 바뀝니다.

<br>

### **시간봉 선택**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/ttmtime.jpg?raw=true">

시간봉을 선택할 수 있습니다. **1분, 5분, 15분, 1시간 4시간 선택 가능**합니다. 일봉 이상의 RSI의 경우 느리게 움직이기 때문에 잦은 확인이 필요하진 않으므로 고려하지 않았습니다. 4시간이면 충분하다고 생각했습니다. 

<br>

### **거래소 선택**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMexchange.jpg?raw=true">
<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMexchange.gif?raw=true">

바이낸스 거래소와 업비트 거래소를 선택할 수 있습니다. 중간에 변경도 가능합니다.
**바이낸스는 선물 차트 기준,업비트는 원화 차트 기준**입니다. 왔다갔다하면서 확인도 가능하고, **프로그램을 두번 켜서 하나는 바이낸스, 하나는 업비트를 확인하여도 됩니다.**
***API로딩에 제한이 있으므로 두개켜서 업비트 두개, 바이낸스 두개를 켜놓지 마세요.*** 

<br>

## **2.툴바**

---

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMban.jpg?raw=true">

메뉴들의 바로가기 입니다. 툴바를 만든 이유는 코인 설정을 할때 메뉴로 들어가기 위해 클릭을 두번해야되는 번거로움을 클릭 한번으로 최소화하고자 만들었습니다. 보고싶지 않은 경우에는 마우스 오른쪽 버튼을 눌러서 끄실 수 있습니다.

<br>


## **3. 메뉴**

---

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/TTMmenu.gif?raw=true">

<br>
<br>

### **TTM 설정**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/settingCoin.jpg?raw=true">

### **암호화폐 설정**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/settingCoin.jpg?raw=true">

암호화폐를 최소 1~ 최대 5개까지 고를 수 있습니다. **영문 대문자 약자**로 타이핑해야 하며 **자동완성 기능**이 있으므로 쉽게 찾을 수 있습니다. 선택 거래소에 없는 코인은 
메인 테이블 화면에서 '미설정'이 출력 됩니다. **적용 버튼을 눌러야만 적용**되고 그냥 닫기를 누르면 적용되지 않습니다.

<br>

### **텔레그램 설정**

<img src="https://github.com/SharpSwan/SharpSwan.github.io/blob/master/assets/img/TTM/RSI/writeToken.jpg?raw=true">

텔레그램 토큰을 입력합니다. **적용 버튼을 눌러야만 적용**되고 그냥 닫기를 누르면 적용되지 않습니다. ***만약 토큰 입력시에 프로그램이 꺼지면 텔레그램 봇에 메세지를 하나 보내놓고 다시 시도해보세요***

<br>

### **개발자**

이 프로그램 개발자에게 연락할 수 있습니다. 원하는 기능이나 불편함이 있으면 의견 남겨주세요. 

<br>

### **도움말**

프로젝트 페이지로 이동합니다.

<br>

### **후원**

개발자에게 후원을 할 수 있습니다. 


### **about**

본 프로그램은 저작권 등록이 되어있습니다. 상업적, 개인적 이득을 위해서 사용하시면 법적인 책임을 물을 수 있습니다. 그리고 될 수 있으면 어떤 문제가 생길지 모르기 때문에 공식적인 루트를 통해서만 다운해주시기 바랍니다. 다들 성투 하시길 바랍니다!

-----------