# 삼각 함수

## [1. 호도법 ](https://www.youtube.com/watch?v=EnZbFxXkxn8)




각도를 재는 방법 : 원의 비율(파이)는 항상 일정하다는 **비율** 법칙을 이용 ( $$ \pi = \frac{L}{2r} = 3.14... ) $$

```
60진법으로 각을 계산 = 각도를 재는 일반적 방식 
 - 원을 360으로 나눈후 1도는 원의 1/360 
 - 단위 : 도-분-초 (1분 = 1/60도, 1초 = 1/60분)
 - 꼭 360으로 나누어야 하는가? 
 ```




![](https://i.imgur.com/kVTvCiM.png)

- 호도법 각도 = $$ \theta = \frac{l}{r} $$ 이고 라디안(rad)이라고 표현
- 호도법 호의 길이 = $$ l = r\theta $$
- 원의 $$\theta$$ 는 일반적 방식으로 360도 이므로 2 $$\pi$$로 볼수 있음 
- 1 rad = ($$\frac{180}{\pi}$$)도 = 57.3도
- 1도 = 0.017 rad
- 1 \pi = 180 도
- 호도법 장점 : 이전 60진법 방식대비 미분시 편함



##### 부채꼴의 넒이는 

- 전체원 S = $$ \pi r^2 $$
- 부채꼴 원 s = 원(S)에서 각도 \theta 비율 = S x ( $$\frac {\theta 도}{360도} = \pi r^2 \cdot \frac{l /r }{2 \pi} = r^2 \cdot \frac{1}{2} \cdot \frac{l}{r} = 1/2 rl$$



---

## 2. [삼각 함수](https://www.youtube.com/watch?time_continue=1&v=scqdoB1kl3g)


삼각형의 각도를 비율로 나타내는것 

|![](https://i.imgur.com/SPuCd3B.png)|![](https://i.imgur.com/14ils1b.png)|
|-|-|

- 한각의 sinA는 다른 각의 cosB이다. 
- 한각의 tanB는 다른각의 1/tanB이다. (역수)
- 각의 역수는 cosecA, secA등으로 정의 


직각 삼각형
- 피타고라스 정리 $$ c^2 = a^2 + b^2  $$
- sin^2 + cos^2 A 는 항상 1이다. 

###### 예) 60진법 각과 호도법간의 변환 (예각 = theta가 90도 미만,) 

> 특수각 : 20,60,등...예각의 경우 

![](https://i.imgur.com/5iRgzGf.png)

- 직각 삼각형은 높이가 1이면, 빗변은 2, 밑은 {루트 3} 법칙 성립 (피타고라스 정리) 
- 이때, sin30도는 빗변(2)분의 높이(1)이므로 1/2.


###### 예) 60진법 각과 호도법간의 변화 (일반각 = theta가 90도 미만 제약 없음)

![](https://i.imgur.com/gmleTBB.png)

위 공식을 이용하여서 $$ \theta $$ 나 $$ -\theta$$ 여도 계산 가능 (예각 여부 상관 없이) 

이때, x는 반지름(r), y= 호의 길이(l)로 보면 f(x)의 계산이 가능  

---

## 3. [삼각함수 관련 공식들 & 덧셈 공식](https://www.youtube.com/watch?v=o1cRDheoFCA)

### 3.1 삼각 함수 공식 
![](https://i.imgur.com/9Kyl1Y7.png)

- 검은색 : 각도가 \theta
 - 좌표는 (x,y)
 - sin \theta = y/r
 - cos \theta = x/4
 - tan \theta = y/x
- 파란색 : 180도에서 \theta 가 빠진 각 = \pi - \theta 
 - 좌표는 (-x,y)
 - sin (\pi - \theta) = y/r = sin \theta
- 초록색 : 180도에서 \theta 만튼 더한 각 = \pi + \theta
 - 좌표는 (-x, -y)
 - sin (\pi + \theta) = - sin \theta
 
 


![](https://i.imgur.com/6IOfQ7w.png)


- 검은색 : 기준 각도 \theta
 - 좌표는 : (x,y)
- 빨간색 : 기준각도 **더하기** 180도 = $$ \frac{\pi}{2} + \theta $$
 - 좌표는 : (-y, x)
 


### 3.2 덧셈 공식 

> sin (a + b)를 어떻게 계산 할까? (단순한, sin a + sin b로 되지 않음 = 선형성이 아님)

![](https://i.imgur.com/tl8ic1O.png)


활용 방법 
- 특수각이 아니어(75)도 특수각으로 만들(30+45)어서 표를 보고 답 구하기 
 - sin 75도 = sin (30도 + 45도) 
- **적분**에서 유용하게 사용 [[추후 설명]](https://youtu.be/o1cRDheoFCA?t=1320)
 - cos^2 a는 바로 적분이 안됨, 그런데 덧셈공식으로 적분이 가능한 모양($$\frac{1+cos2a}{2}$$) 으로 변경 가능


###### 덧셈 공식과 적분 
![](https://i.imgur.com/4urOFrO.png)


