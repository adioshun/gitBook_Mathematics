
# 개념수업 미분이란무엇인가
> 출처 : [개념수업 미분이란무엇인가](https://www.youtube.com/watch?v=2JvfRLgcmUI)



## 1. 개요



![](http://i.imgur.com/KO08KsE.png)

미분한다 = (한점에서의) 기울기를 구한다. = $$f\prime$$

기울기 구하는법
- 두점의 기울기(평균 변화율) : $$ \frac{f(x)-f(a)}{x-a} $$
- 한점의 기울기(순간 변화율) : $$ \lim_{x \rightarrow 0}\frac{f(x)-f(a)}{x-a} = f\prime(a)=\frac{d}{dx}f(x)$$

> 두점(x, a)의 사이를 아주 가깝게 하여 x=a로 만듬

## 2. 표현법/식
![](http://i.imgur.com/ed9FGRk.png)

- h를 이동거리(간격)으로 할때 : $$a+h \Leftarrow 많이 쓰임$$
- 변화량 x로 할때 : $$a+\Delta{x} $$
- 변활율 $$\frac{x}{y}$$로 할때 : $$\frac{\Delta x}{\Delta y} \Rightarrow \lim_{\Delta x \rightarrow 0}\frac{\Delta x}{\Delta y}\Rightarrow \frac{d x}{d y} $$


> $$\Delta$$ : Difference 의미(변화양), Delta라 읽음,

원래 $$\Delta = d $$는 같은것이지만 필요에 의해 둘을 다른 의미로 사용
- $$\Delta$$ : 변화량
- $$\ d$$ : $$\lim_{\Delta x \rightarrow 0}된 \Delta $$

|기호|의미||
|-|-|-|
|$$\Delta$$|인접한 두 변수의 차이||
|$$d$$|두변수의 극미한차이||
|$$\partial$$|다변수함수에 대한 하나의 변수에 대한 변화량(편미분)||
|$$\bar d$$|통계적인 변수의 변화량||




## 3. $$\frac{dy}{dx} = \frac{d}{dx}y$$에 대한 고찰

읽는법
- dx분에 dy
- dx에 대한 dy (일반적)

의미
- $$\frac{dy}{dx}$$: (dx에 대해) y를 미분 하라.
- y에 대한 식이다. eg. $$y = x^3 + 2x^2$$



### 3.1 곱의 미분 법칙
곱의 미분 = 한쪽만 미분한 것들의 합

$$(xy)\prime = x\prime y + y\prime x$$

### 3.2 나눗셈의 미분 법칙
$$(\frac{x}{y})\prime = \frac{x\prime y + y\prime x}{y^2}$$



### 3.2 $$\frac{1}{x}$$의 미분

$$y = \frac{1}{x} = x^{-1} \rightarrow y\prime = -x^{-2}$$

### 3.3 지수함수, 자연로그

$$y= e^x \rightarrow y\prime = e^x$$ (변화 없음)
$$y=\ln x \rightarrow y\prime = \frac{1}{x}$$
$$y=\ln{(ax+b)} \rightarrow y\prime = \frac{1}{(ax+b)}\times a$$


## 4. 미분의 적용

![](http://i.imgur.com/quvVJHM.png)


||지수함수|다항함수|
|-|-|-|
|원식|$$y=a^x$$|$$y=x^n$$|
|정의|a가 상수<br>$$y=a^x$$인 함수 단, $$a \neq 1$$|n이 상수|
|미분|$$y\prime=a^x \ln a$$|$$y\prime = n x^{n-1}$$|

> 출처 : [지수 로그 함수의 미분 로피탈 공식](https://youtu.be/si6ckKuXNBo)


### 4.1 지수 함수의 미분


미분 = 원식 $$\times$$ 미분식 $$\times$$ $$\ln a$$

$$y = a^{x{^2}+2x+3} \Rightarrow y\prime = a^{x{^2}+2x+3} \cdot (2x+2)\cdot \ln a$$

> 지수 함수의 역함수 : $$y=a^x \rightarrow y=\log_ax$$

#### A. 밑이 e인 지수 함수 ($$y=e^x$$)

$$y=e^x \Rightarrow y\prime = e^x \cdot \ln e \Rightarrow e^x $$ ($$\because \ln e $$=1이어서 생략)

> 미분을 했어도 값이 줄지 않음

$$y=e^{x^2+x} \Rightarrow y\prime = e^{x^2+x} \cdot (2x+1) \cdot \ln e $$



### 4.2 다항 함수의 미분 

|![](http://i.imgur.com/ruN0L8U.png)|![](http://i.imgur.com/pgiXrEh.png)|
|-|-|
|![](http://i.imgur.com/KQZOn04.png)|![](http://i.imgur.com/rnHPMzf.png)|

지수의 숫자를 앞으로 내리고 지수에서 그 대가로 1을 뺀다. 상수는 0이 된다.

> 출처 : [waylight3](http://waylight3.blog.me/220221644620)



### 4.2 로그 함수의 미분 

#### A. 지수로그($$y = \log_a x$$) 함수의 미분
로그 이후의 값으로 1/n을 만들고, 로그 밑 값으로 ln a만듬, 미분값 연결 


$$

y = \log_a x \Rightarrow y\prime = \frac{1}{(x)\ln(a)} x\prime

$$

- $$ y = \log_a (x^2+x) \Rightarrow y\prime = \frac{1}{(x^2+x)\cdot \ln (a)}(2x+1) $$



#### B. 자연로그($$\ln x = \log_e{x}$$) 함수의 미분

$$
y = \ln(f(x)) \Rightarrow \frac{1}{f(x)}f\prime(x)
$$


- $$y = \ln x = \log_e x \Rightarrow y\prime = \frac{1}{x (\ln e) } = \frac{1}{x}$$ ($$\because \ln e $$=1이어서 생략)



- $$y = \ln (x^2+2x) \Rightarrow y\prime = \frac{1}{x^2+2x(\ln e)}= \frac{1}{x^2+2x}(2x+1)$$





> $$\ln$$=자연 로그= 실수(e)를 밑으로 하는 로그(log)



###### [참고] 로피탈 공식 ($$\frac{0}{0}, \frac{\infty}{\infty}$$)


### 4.3 벡터 미분

> 참고 : 머신러닝에서 딥러닝까지 별첨A.1, [다크 프로그래머](http://darkpgmr.tistory.com/141), [[추천]데이어트사이언스 스쿨](https://datascienceschool.net/view-notebook/8595892721714eb68be24727b5323778/), [영문교과서](http://www.atmos.washington.edu/~dennis/MatrixCalculus.pdf)


- 행렬 미분은 정확하게는 미분이 아닌 `편미분(partial derivative)`이지만 표현 편의상 미분이라고 표현

- 데이터 분석은 대부분 스칼라(y=종속변수)를 벡터(x=독립변수)로 미분 하는 경우임 : $$\frac{\partial y}{\partial x_1},\frac{\partial y}{\partial x_2},\frac{\partial y}{\partial x_3}$$
- 결과는 그레이언트벡터(Gradient Vector)라고 하며 $$\triangledown y $$로 표기
$$
\nabla y =
\frac{\partial y}{\partial \mathbf{x}} =
\begin{bmatrix}
\dfrac{\partial y}{\partial x_1}\\
\dfrac{\partial y}{\partial x_2}\\
\vdots\\
\dfrac{\partial y}{\partial x_N}\\
\end{bmatrix}
$$

- 예시

$$f(x,y)= 2x^2 + 6xy +7y^2 -26x -56y +107 $$

$$
\nabla f =
\begin{bmatrix}
\dfrac{\partial f}{\partial x}\\
\dfrac{\partial f}{\partial y}\\
\end{bmatrix} =
\begin{bmatrix}
4x + 6y - 26\\
6x + 14y - 54\\
\end{bmatrix}
$$


### 4.5 삼각함수

> [미적분2 삼각함수 개념강의 초간단정리 사인법칙 코사인법칙](https://www.youtube.com/watch?v=A8S_ZAuWFjA)


##### [정리] 자주 쓰이는 벡터 미분

![](http://i.imgur.com/HlzCWHP.png)
[증명보기](http://blog.naver.com/enewltlr/220918689039)


# 적분

KL 은 적분으로 표현이 가능한데, 그 적분이 P 와 Q 라는 conditional density 의 변수에 대해 취해진다는 뜻으로 점을 찍은겁니다. 예를 들어 E[ f(y|x) ] 같은 기대값에서 y 에 대해 적분이 이루어지면 E[ f( . | x) ] 으로 표기합니다.






