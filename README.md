# Optimization (数理最適化手法)

## 参考

## 解析微分公式(導関数)
```math
    f'(\boldsymbol{x})= \lim_{h \to 0} \ \frac{f(\boldsymbol{x}-h) - f(\boldsymbol{x})}{h}
```
+ 分子の差分値 $f(\boldsymbol{x} - h) - f(\boldsymbol{x})$ で, 桁落ちするので精度が低い微分値を算出する.
+ できるだけ解析微分公式(導関数)を用いて微分値を算出すべき.

## 微分の連鎖律
```math
\begin{eqnarray}
    y &=& f(x), x = g(t)
    \
    \frac{dy}{dt} &=& \frac{dy}{dt} * \frac{dt}{dx}
    \
    y &=& (1 - \boldsymbol{x})^{2}, x = 3t + 2 \tag{e.g}
    \
    \frac{dy}{dt} &=& -2x, \frac{dx}{dt} = 3
    \
    \frac{dy}{dt} &=& -6x
\end{eqnarray}
```

## 数値微分
+ 愚直法
+ Runge-Kutta法(1次,2次,3次,4次) (デファクトスタンダード)

## 数値積分
+ ニュートン・コーツ法
+ 台形公式法
+ シンプソンの公式法

## 制約なし非線形問題
+ ニュートン法
+ 勾配降下法
+ 共役勾配降下法 
+ 焼きなまし法

### ニュートン法の派生種
+ 準ニュートン法
+ ガウス・ニュートン法
+ レーベンバック・マッカート法(LM法)

### 勾配降下法の派生種
+ SGD
+ RMSprop
+ Nesterov
+ Momentum
+ Adam
+ AdaDelta
+ AdaBoost
+ AdaMax
+ etc

### 制約あり非線形問題
+ ラグランジュの未定乗数法
+ KTK条件

## 制約なし線形問題
+ 線形計画法
+ 2次計画法 (2次の場合)


## 制約あり線形問題
+ a
+ b
+ c
+ 
    
