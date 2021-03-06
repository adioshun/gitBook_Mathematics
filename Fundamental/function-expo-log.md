# 지수 로그 함수 극한 

> 지수 함수 : y = f(x) = a^x 

## 1. 지수 법칙 

![](http://i.imgur.com/TG4PFRx.png)

> [로그의정의와공식증명](https://www.youtube.com/watch?v=aJ7j4QhAzk8)

### 1.1 정의

- 거듭제곱($$a^n$$): 어떤 수 a를 n번 곱한것을 a의 n 제곱이라 함(a=밑=기저, n=지수)
- 거듭제곱근($$x^n = a$$): n 제곱하여 실수 a가 되는 수 x를 a의 n 제곱근이라 한다. 

### 1.2 법칙  


#### A. [지수의 법](https://www.youtube.com/watch?time_continue=42&v=zsMTKe9f1bg)
- $$a^ma^n = a^{m+n}$$

- $$(a^m)^n = a^{mn}$$

- $$(ab)^n = a^n b^n$$

- $$(\frac{a}{n})^n = \frac{a^n}{b^n}$$

- $$ a^m \% a^n =  \frac{a^m}{a^n} $$
    - $$ a^{m-n} (m>n) $$
    - $$ 1 (m=n)  = \frac{a^m}{a^n} = 1 = a^{m-n} = a^0$$ 
    - $$ \frac{1}{a^{n-m}} (m < n) $$  

- $$a^0 = 1$$

- $$a^{-n} = \frac{1}{a^n}$$


#### B. 거듭 제곱근의 법칙 

- $$\sqrt[n]{a} \cdot \sqrt[n]{b} = \sqrt[n]{ab} $$

- $$\frac{\sqrt[n]{a}}{\sqrt[n]{b}} = \sqrt[n]{\frac{a}{b}}$$

- $$(\sqrt[n]{a})^m = \sqrt[n]{a^m}$$

- $$ \sqrt[m]{\sqrt[n](a)} = \sqrt[mn]{a}$$


### 1.3 [지수 함수와 그래프 ](https://youtu.be/zsMTKe9f1bg?t=1535)

![](https://i.imgur.com/7B5AG6i.png)

기준점 y = a^x에 대해서 
- y = a^{-ax} 는 x의 기호가 바뀌려면 y를 기준으로 대칭 해야 함 

---
## 2. [로그 ](https://www.youtube.com/watch?v=-lL3i7qGcbs)

### 2.1 로그의 정의 

$$a^x = b \rightarrow x = \log_a b$$
- a를 밑으로 하는 b의 로그 
- b를 $$\log_a{b}진수라 한다.  $$
- 밑(a)을 몇 제곱(x)해야 진수(b)가 되는가? 
- 지수함수의 지수를 기준으로 팀과 진수로 설명 하는것 
- 지수 함수의 역함수 = $$a^x = y에서 (x \leftrightarrow y)하면  \log_ay = x$$ (a의 x승은 y)
- 지수만을 떼어내서 복잡한 셈을 간단히 하는것 






### 2.2. 로그의 성질

- $$\log_a{1}=0, \log_a{a}=1$$

- $$\log_a{xy} = \log_a{x} + \log_a{y}$$   (곲셈을 덧셈으로 바꾸어 주어 공식 단순화시 사용)

- $$\log_a{\frac{x}{y}} = \log_a{x} - \log_a{y}$$ (나눗셈을 뺄셈으로 바꾸어 주어 공식 단순화시 사용)

- $$log_a{x^n} = n \cdot \log_a{x}$$

- $$ a^{log_ax} = x $$


### 2.3 로그의 공식

- 로그의 밑변환 공식 : $$\log_a{b}= \frac{\log_c{b}}{\log_c{a}}, (단 c > 0, c \neq 1)= \frac{1}{\log_ba}$$





### 2.4 종류 

#### A. 지수로그 

> 로그 함수는 큰 숫자를 넣으면 넣을수록 y값이 즉 함수 출력 값이 서서히 증가하는 성질을 가지고 있습니다. 따라서 로그 함수에 아무리 큰 숫자를 넣어도 출력은 별로 큰 값이 나오지 않습니다. 

> 조건부 확률을 최대화 해서 모델을 찾을때 로그 사용(eg. 우도 로그)
> - 로그 값을 취해서 확률을 최대화 시킬수 있음. 로그값의 확률이 1보다 작고 음수로 만들어 값을 분산시키므로 최적화 계산을 더 효율적으로 만듬 

확률값은 부동소수점으로 표현되는 값이 많다. 이런값의 곱셈을 하게 되면 언더플로우(Numerical underflow)문제에 직면 하게 된다. 그래서 곱셈을 덧셈으로 변환하여 문제 풀이 시행 

#### B. 일상생활에서 많이 쓰이는 상용로그 

- $$\log x = log (a \times 10^n) = log a + log 10^n = n + log a $$

- $$ 예: \log 1230000000 = log (1.23 \times 10^9) = log 1.23 + log 10^9 = 9 + log 1.23 $$


#### C. 컴퓨터공학에서 많이 쓰이는 자연로그 
- 자연로그는 아주 큰수를 계산하기 위해 만들어 짐 
- 큰수를 계산 하기 위한 조건 
    - 조건 1: 초항 a는 아주 큰 수여야 한다. 
    - 조건 2: 로그의 밑은 1보다 크면서 무한히 쪼개어 지는 무리수 e 
- **지수를 없앨수 있어 공식 단순화시 사용**

- $$\log_e{x} = ln(x)$$
    - $$e = 1 + \frac{1}{1}!+ \frac{1}{2}!+ \frac{1}{3}!...$$=2.718

> 자연로그라 불리는 이유? 무리수 e가 자연현상에서 증식으로 보여지는 여러 현상을 표현하기에 유용

###### [자연로그 성질]
- $$log_2{e} = \frac{\log_e{e}}{\log_e{2}} = \frac{1}{\log_e{2}}$$ : 로그의 밑변환 공식 


> e는 실수로 활용 분야에 따라 다양하게 불리운다. 자연상수(자연로그), 오일러수
> - 무리수: 두 정수의 비로 표현 할수 없는 실수, 분수로 나타낼수 없는 소수
> - 초월수




![](https://i.imgur.com/JlUtK68.png)




