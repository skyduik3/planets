# 1조 컴시설
2010136102 이정민
2014136103 임상훈
2016136095 이서영
2016136110 이현규

## 스마트 옷장

~~필요성~~

### 문제정의

* 옷장속에 들어있는 의류의 **정확한 파악**이 어려움
- 매일 아침 **적절한 코디**를 하기 어려움

### 요구사항

1. 시스템은 시스템 내부의 의류를 파악 할 수 있어야한다.
2. 시스템은 수집 보관하고 있는 데이터를 통해 의상코디를 제공 할 수 있어야 한다.
3. 시스템은 사용자의 데이터를 통해 학습 할 수 있어야한다.
4. 시스템은 정보처리를 신속히 해주어야한다.


### 해결방안

1. 시스템은 시스템 내부의 의류를 파악 할 수 있어야한다.
* RFID칩을 통해  옷장 내부의 의류를 파악 할 수 있어야한다.

2. 시스템은 수집 보관하고 있는 데이터를 통해 의상코디를 제공 할 수 있어야 한다.
* 2D아바타를 이용하여 코디 이미지를 제공한다.

3. 시스템은 사용자의 데이터를 통해 학습 할 수 있어야한다.
* RFID칩에 저장된 의류 정보를 활용하여 학습을한다.
* 선택된 코디를 기반으로 학습을 한다.

4. 시스템은 정보처리를 신속히 해주어야한다.
* 시스템은 최적화된 알고리즘을 이용한다.

                                
### 기존관련사례 조사
1.스마트 옷장_유사사례 논문
 첫번째 사례는 *스마트 옷장*입니다.
외부로부터 날씨 API를 받아 사용자에게 코디를 추천해줍니다.
[dbpia논문 링크](http://insight.dbpia.co.kr/metrics.do?nodedId=NODE06554464)
![연관이미지](./img/closet.jpg)

2.보도블럭 패턴_논문
 두번째 사례는 *보도블록 인식기술*입니다.
영상의 형태 패턴과 텍스처 특징을 이용하여 보도블럭을 인식하는 기술입니다.
[dbpia논문 링크](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01908129)
![연관이미지](./img/block.jpeg)

3.기계학습 의류 자동 매칭_논문
 세번째 사례는 *기계학습 의류 자동매칭기술*입니다.
해당 논문은 기본적인 **전문가의 트레이닝 데이터**와 이를 기반으로 한 기계학습모$
![IMAGE](./img/MachineTraining.PNG)
[기계학습을 활용한 상하의 의류 자동매칭 시스템](http://insight.dbpia.co.kr/article/metrics.do?nodeId=NODE01595278)

4.RFID 수납관리 시스템_특허
 네번째 사례는 *RFID 수납관리 시스템*입니다.
해당 논문은 RFID를 이용해서 물건들의 상태와 위치를 알 수 있고 관리하기 쉽도록 만들어놓은 시스템이다.
[RFID 기술을 이용한 세대 수납관리 시스템] : ![IMAGE](./img/RFID.PNG)
