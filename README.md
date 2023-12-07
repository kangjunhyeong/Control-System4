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

(a)  
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
(b)  
계단입력일때  
$R(s)=\frac{1}{s}$  
$e_{ss} = \lim_{{s \to 0}} sE(s) = \lim_{{s \to 0}} s\frac{R(s)}{1+G(s)H(s)}=0$  

경사입력일때  
$R(s)=\frac{1}{s^2}$  
$e_{ss} = \lim_{{s \to 0}} sE(s) = \lim_{{s \to 0}} s\frac{R(s)}{1+G(s)H(s)}=0$  

![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/14cf9375-dd7f-4254-b4b1-419f343f71ae)  
![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/7951b8f7-9756-4842-94ec-0cc0de7215e3)  
![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/2ea13542-8dac-404f-b6ad-01e4f905cd75)  
(a)  
$I=25Kgm^2, r(t)=t (t>0), e_{ss}=0.01$  
$G(s)=\frac{K_1K_2}{s(Is+K_1K_2K_3)}$  
$T(s)=\frac{K_1K_2}{s(Is+K_1K_2K_3)+K_1K_2}$  
$e_{ss}=\lim_{{s \to 0}}sE(s)=\lim_{{s \to 0}}s(1-T(s))R(s)=\lim_{{s \to 0}}\frac{(Is+K_1K_2K_3)}{s(Is+K_1K_2K_3)+K_1K_2}=K_3=0.01m$  

(b)  
$Is^2+K_1K_2K_3s+K_1K_2=0, K_1K_2=K$  
$s^2+0.0004Ks+0.04K=0$  
$s^2+2\zeta\omega_ns+\omega_n^2=0$  
$2\zeta\omega_n=0.0004K, \omega_n^2=0.04K$  
$K=\zeta^2 \cdot 10^6$  
$M_p = e^{-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}} \leq 0.1$  
$ln(e^{-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}})=ln(0.1)$  
$\-\frac{\zeta \pi}{\sqrt{1-\zeta^2}}=-2.3$  
$\zeta=0.6, K=600000$  

![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/fbb7c57f-fa78-45df-80da-c99b9aa8008f)  
(a)  
![image](https://github.com/kangjunhyeong/Control-System4/assets/144297425/4df3fd46-3963-410d-a3f4-13ba09ad144e)  
(b)  



