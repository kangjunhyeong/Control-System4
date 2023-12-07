### 2018732004 강준형
![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/9f8a5336-effa-4939-aea4-36270de5a28b)  

![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/ce4fb29a-e2dd-4522-9dfb-37a8414de6f3)

$\ E(s) = \frac{R(s)}{1 + G(s)} $  

$R(s)=\frac{1}{s^2}$  

$E(s)=\frac{s+K_1}{s^2(s+K_1)+K}$  

$e_{ss} = \lim_{{s \to 0}} sE(s) = \lim_{{s \to 0}} \frac{s + K_1}{s(s + K_1) + K}=5$  

$K_1=5K$  

![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/d409d11d-c925-4811-a485-e770a90e357d)  

![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/d7fb5472-fcf8-4c8d-9f57-fd8582400f7c)  

$\tau_1=1, \tau_2=0, K=K_1K_2$  

$G(s)=\frac{K(s+1)}{s^2}$  

$1+G(s)H(s)=1+\frac{K(s+1)}{s^2}$  

$M_p = e^{-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}} \leq 0.05$  

$ln(e^{-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}})=ln(0.05)$  

$\-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}=-3$  

$\zeta=0.69$  

이제 식을 사용하면  

$s^2+2\zeta\omega_ns+\omega_n^2=0$  

$\omega_n^2=K, \ 2\zeta\omega_n=K$  

$\sqrt{K}=1.38$  
$K=1.9$  
계단입력일때  
$R(s)=\frac{1}{s}$  
$e_{ss} = \lim_{{s \to 0}} sE(s) = \lim_{{s \to 0}} s\frac{R(s)}{1+G(s)H(s)}=0$  

경사입력일때  
$R(s)=\frac{1}{s^2}$  
$e_{ss} = \lim_{{s \to 0}} sE(s) = \lim_{{s \to 0}} s\frac{R(s)}{1+G(s)H(s)}=0$  
