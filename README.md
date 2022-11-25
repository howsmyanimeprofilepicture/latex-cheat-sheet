# 알면 좋고 몰라도 상관없는 LaTEX 관련 노하우들
## KaTEX vs. MathJax

* 웹에서 사용되는 LaTEX 엔진은 일반적으로 KaTEX와 MathJax, 이렇게 두가지 엔진이 사용됩니다.
* Github 같은 경우 MathJax가 사용되며, Velog 같은 경우 KaTEX를 사용합니다.
* 제가 느끼기에는 KaTEX가 조금 더 많은 문법들을 지원하는 것 같습니다. 
* 그래서 KaTEX 엔진에서는 렌더링되던 LaTEX 스크립트들이 MathJax 환경에서는 종종 에러를 보이곤 합니다.
* 하지만 MathJax 환경에서 렌더링 되던 스크립트들이 KaTEX에서 에러를 발생시키는 경우는 아직까지 경험해보지 못했습니다.

$$
f(x) = x^2 \tag{Eq 1.}
$$


$$
\int_{\infty}^{\infty} ㅋㅋ
$$

$$
\infty~\text{ㅋㅋ}
$$

$$
\mathbf X
$$

$$
\vec x
$$

$$
\mathbb R
$$

$$
\mathcal D
$$


$$
\sim
$$

$$
\approx
$$

$$
\propto
$$

$$
\therefore
$$
