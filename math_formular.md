## 行内与独行

### 行内公式
将公式插入到文章内

- 方法：`$公式内容$`
- 范例 
`前文$xyz$后文`
- 显示
  前文$xyz$后文

### 独行公式
将公式插入到新的一行内，并且居中

- 方法：`$$公式内容$$`
- 范例：
```$$xyz$$```
- 显示
  $$xyz$$


## 上标、下标与组合

|类型|符号|代码|呈现|
|-|-|-|-|
|上标|`^`|`$x^4$`|$x^4$|
|下标|`_`|`$x_1$`|$x_1$|
|组合|`{}`|`$S_{2}O_{3}^{2+}$`|$S_{2}O_{3}^{2+}$|

## 汉字、字体与格式

|类型|符号|代码|呈现|
|-|-|-|-|
|汉字形式|`\mbox{}`|`$V_{\mbox{初始}}$`|$V_{\mbox{初始}}$|
|字体控制|`\displaystyle`|`$\displaystyle \frac{x+y}{y+z}$`|$\displaystyle \frac{x+y}{y+z}$|
|下划线|`\underline`|`$\underline{x+y}$`|$\underline{x+y}$|
|标签|`\tag{数字}`|`$\tag{11}$`|$\tag{11}$|
|上大括号|`\overbrace{算式}`|`$\overbrace{a+b+c+d}^{2.0}$`|$\overbrace{a+b+c+d}^{2.0}$|
|下大括号|`underbrace{算式}`|`$a+\underbrace{b+c}_{1.0}+d$`|$a+\underbrace{b+c}_{1.0}+d$|
|上下组合|`——`|`$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$`|$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$|
|上位符号|`\stacrel{上位符号}{基位符号}`|`$3O_2 {\stackrel{\mathrm{_{放电}}}{=}} 2O_3$`|$3O_2 {\stackrel{\mathrm{_{放电}}}{=}} 2O_3$|

$2S+3O_2 {{500℃} \atop {{\rightarrow} \atop {V_2O_5}} } SO_3$

$2S+3O_2 {{{500℃} \atop {\rightarrow}} \atop {_{V_2O_5}} } SO_3$


## 占位符
|类型|符号|代码|呈现|
|-|-|-|-|
|两个quad空格|`\qquad`|`$x \qquad y$`|$x \qquad y$|
|quad空格|`\quad`|`$x \quad y$`|$x \quad y$|
|大空格|`\`|`$x \ y$`|$x \ y$|
|中空格|`\:`|`$x \: y$`|$x \: y$|
|小空格|`\,`|`$x \, y$`|$x \, y$|
|没有空格||`$xy$`|$xy$|
|紧贴|`\!`|`$x \! y$`|$x \! y$|

## 定界符与组合

|类型|符号|代码|呈现|
|-|-|-|-|
|$小括号_{普通}$|`()`|`$(内容)$`|$(内容)$|
|$小括号_{大}$|`\big(\big)`|`\big(内容\big)`|$\big(内容\big)$|
|$小括号_{大}$|`\Big(\Big)`|`$\Big(内容\Big)$`|$\Big(内容\Big)$|
|$小括号_{大}$|`\bigg(\bigg)`|`$\bigg(内容\bigg)$`|$\bigg(内容\bigg)$|
|$小括号_{大}$|`\Bigg(\Bigg)`|`$\Bigg(内容\Bigg)$`|$\Bigg(内容\Bigg)$|
|中括号|`[]`|`$[x+y]$`|$[x+y]$|
|大括号|`\{ \}`|`$\{x+y\}$`|$\{x+y\}$|
|自适应括号|`\left \right`|`$\left(x{yz}\right)$`|$\left(x{yz}\right)$|
|括号组合|`{上位公式 \choose 下位公式}`|`${n+1 \choose k}={n \choose k}+{n \choose k-1}$`|${n+1 \choose k}={n \choose k}+{n \choose k-1}$|
|上下组合|`{上位公式 \atop 下位公式}`|`$\{{x+y=2 \quad ① \atop 2x+3y=5 \quad ②}$`|$\{{x+y=2 \quad ① \atop 2x+3y=5 \quad ②}$|

## 四则运算

|类型|符号|代码|呈现|
|-|-|-|-|
|加法|`+`|`$x+y=z$`|$x+y=z$|
|减法|`-`|`$x-y=z$`|$x-y=z$|
|乘法|`\times`|`$x \times y=z$`|$x \times y=z$|
|除法|`\div`|`$x \div y=z$`|$x \div y=z$|
|加减|`\pm`|`$x \pm y=z$`|$x \pm y=z$|
|减加|`\mp`|`$x \mp y=z$`|$x \mp y=z$|
|点乘|`\cdot`|`$x \cdot y=z$`|$x \cdot y=z$|
|星乘|`\ast`|`$x \ast y=z$`|$x \ast y=z$|
|斜除|`/`|`$x/y=z$`|$x/y=z$|
|分式|`\frac{分子}{分母}`|`$\frac{x+y}{y+z}$`|$\frac{x+y}{y+z}$|
|分式|`{分子} \voer {分母}`|`${x+y} \over {y+z}$`|${x+y} \over {y+z}$|

## 高级运算

|类型|符号|代码|呈现|
|----|-|-|-|
|均值|`\overline{算式}`|`$\overline{xyz}$`|$\overline{xyz}$|
|矢量|`\vec{矢量}`|`$\vec{x}$`|$\vec{x}$|
|根号|`\sqrt`|`$\sqrt x$`|$\sqrt x$|
|开方|`\sqrt[开方数]{被开方数}`|`$\sqrt[3]{x+y}$`|$\sqrt[3]{x+y}$|
|对数|`\log`|`$\log(x)$`|$\log_{32}(x)$|
|极限|`\lim`|`$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$`|$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$|
|极限|`\displaystyle \lim`|`$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$`|$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$|
|求和|`\sum`|`$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$`|$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$|
|求和|`\displaystyle \sum`|`$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$`|$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$|
|积分|`\int`|`$\int^{\infty}_{0}{xdx}$`|$\int^{\infty}_{0}{xdx}$|
|积分|`\displaystyle \int`|`$\displaystyle \int^{\infty}_{0}{xdx}$`|$\displaystyle \int^{\infty}_{0}{xdx}$|
|微分|`\partial`|`$\frac{\partial x}{\partial y}$`|$\frac{\partial x}{\partial y}$|
|矩阵|`\begin{matrix} \end{matrix}`|`$\left[ \begin{matrix} 1 &2 &\cdots &4\5 &6 &\cdots &8\\vdots &\vdots &\ddots &\vdots\13 &14 &\cdots &16\end{matrix} \right]$`|$\left[ \begin{matrix} 1 &2 &\cdots &4 \\5 &6 &\cdots &8\\\vdots &\vdots &\ddots &\vdots \\13 &14 &\cdots &16\end{matrix} \right]$|

## 等式 & 不等式

|类型|符号|代码|呈现|
|----|-|-|-|
|等于|`=`|`$x+y=z$`|$x+y=z$|
|大于|`>`|`$x+y>z$`|$x+y>z$|
|小于|`<`|`$x+y<z$`|$x+y<z$|
|大于等于|`\geq`|`$x+y \geq z$`|$x+y \geq z$|
|小于等于|`\leq`|`$x+y \leq z$`|$x+y \leq z$|
|不等于|`\neq`|`$x+y \neq z$`|$x+y \neq z$|
|不大于等于|`\ngeq`|`$x+y \ngeq z$`|$x+y \ngeq z$|
|不大于等于|`\not\geq`|`$x+y \not\geq z$`|$x+y \not\geq z$|
|不小于等于|`\nleq`|`$x+y \nleq z$`|$x+y \nleq z$|
|不小于等于|`\not\leq`|`$x+y \not\leq z$`|$x+y \not\leq z$|
|约等于|`\approx`|`$x+y \approx z$`|$x+y \approx z$|
|恒定等于|`\equiv`|`$x+y \equiv z$`|$x+y \equiv z$|

## 逻辑 & 集合

|类型|符号|代码|呈现|
|----|-|-|-|
|属于|`\in`|`$x \in y$`|$x \in y$|
|不属于|`\notin`|`$x \notin y$`|$x \notin y$|
|不属于|`\not\in`|`$x \not\in y$`|$x \not\in y$|
|包含于|`\subseteq`|`$x \subseteq y$`|$x \subseteq y$|
|真包含于|`\subset`|`$x \subset y$`|$x \subset y$|
|真包含于|`\subsetneq`|`$x \subsetneq y$`|$x \subsetneq y$|
|不包含于|`\not\subset`|`$x \not\subset y$`|$x \not\subset y$|
|包含|`\supseteq`|`$x \supseteq y$`|$x \supseteq y$|
|真包含|`\supset`|`$x \supset y$`|$x \supset y$|
|真包含|`\supsetneq`|`$x \supsetneq y$`|$x \supsetneq y$|
|不包含|`\not\supset`|`$x \not\supset y$`|$x \not\supset y$|
|并集|`\cup`|`$x \cup y$`|$x \cup y$|
|交集|`\cap`|`$x \cap y$`|$x \cap y$|
|差集|`\setminus`|`$x \setminus y$`|$x \setminus y$|
|同或|`\bigodot`|`$x \bigodot y$`|$x \bigodot y$|
|同与|`\bigotimes`|`$x \bigotimes y$`|$x \bigotimes y$|
|实数集|`\mathbb{R}`|`$\mathbb{R}$`|$\mathbb{R}$|
|自然数集|`\mathbb{Z}`|`$\mathbb{Z}$`|$\mathbb{Z}$|
|空集|`\emptyset`|`$\emptyset$`|$\emptyset$|

## 数学符号

|类型|符号|代码|呈现|
|-|-|-|-|
|无穷|`\infty`|`$\infty$`|$\infty$|
|虚数i|`\imath`|`$\imath$`|$\imath$|
|虚数j|`\jmath`|`$\jmath$`|$\jmath$|
|一阶导数|`\dot{a}`|`$\dot{a}$`|$\dot{a}$|
|二阶导数|`\ddot{a}`|`$\ddot{a}$`|$\ddot{a}$|
||`\bar{a}`|`$\bar{a}$`|$\bar{a}$|
||`\acute{a}`|`$\acute{a}$`|$\acute{a}$|
||`\check{a}`|`$\check{a}$`|$\check{a}$|
||`\grave{a}`|`$\grave{a}$`|$\grave{a}$|
||`\hat{a}`|`$\hat{a}$`|$\hat{a}$|
||`\breve{a}`|`$\breve{a}$`|$\breve{a}$|
||`\tilde{a}`|`$\tilde{a}$`|$\tilde{a}$|
||`\mathring{a}`|`$\mathring{a}$`|$\mathring{a}$|
|上箭头|`\uparrow`|`$\uparrow$`|$\uparrow$|
|上箭头|`\Uparrow`|`$\Uparrow$`|$\Uparrow$|
|下箭头|`\downarrow`|`$\downarrow$`|$\downarrow$|
|下箭头|`\Downarrow`|`$\Downarrow$`|$\Downarrow$|
|左箭头|`\leftarrow`|`$\leftarrow$`|$\leftarrow$|
|左箭头|`\Leftarrow`|`$\Leftarrow$`|$\Leftarrow$|
|右箭头|`\rightarrow`|`$\rightarrow$`|$\rightarrow$|
|右箭头|`\Rightarrow`|`$\Rightarrow$`|$\Rightarrow$|
|省略号底|`\ldots`|`$1,2,\ldots,n$`|$1,2,\ldots,n$|
|省略号中|`\cdots`|`$x_1^2 + x_2^2 + \cdots + x_n^2$`|$x_1^2 + x_2^2 + \cdots + x_n^2$|
|省略号竖|`\vdots`|`$\vdots$`|$\vdots$|
|省略号斜|`\ddots`|`$\ddots$`|$\ddots$|

## 希腊字母

|字母|符号|代码|呈现|
|-|-|-|-|
|A|`A`|`$A$`|$A$|
|α|`\alpha`|`$\alpha$`|$\alpha$|
|B|`B`|`$B$`|$B$|
|β|`\beta`|`$\beta$`|$\beta$|
|Γ|`\Gamma`|`$\Gamma$`|$\Gamma$|
|γ|`\gamma`|`$\gamma$`|$\gamma$|
|Δ|`\Delta`|`$\Delta$`|$\Delta$|
|δ|`\delta`|`$\delta$`|$\delta$|
|E|`E`|`$E$`|$E$|
|ϵ|`\epsilon`|`$\epsilon$`|$\epsilon$|
|Z|`Z`|`$Z$`|$Z$|
|ζ|`\zeta`|`$\zeta$`|$\zeta$|
|H|`H`|`$H$`|$H$|
|η|`\eta`|`$\eta$`|$\eta$|
|Θ|`\Theta`|`$\Theta$`|$\Theta$|
|θ|`\theta`|`$\theta$`|$\theta$|
|I|`I`|`$I$`|$I$|
|ι|`\iota`|`$\iota$`|$\iota$|
|K|`K`|`$K$`|$K$|
|κ|`\kappa`|`$\kappa$`|$\kappa$|
|Λ|`\Lambda`|`$\Lambda$`|$\Lambda$|
|λ|`\lambda`|`$\lambda$`|$\lambda$|
|M|`M`|`$M$`|$M$|
|μ|`\mu`|`$\mu$`|$\mu$|
|N|`N`|`$N$`|$N$|
|ν|`\nu`|`$\nu$`|$\nu$|
|Ξ|`\Xi`|`$\Xi$`|$\Xi$|
|ξ|`\xi`|`$\xi$`|$\xi$|
|O|`O`|`$O$`|$O$|
|ο|`\omicron`|`$\omicron$`|$\omicron$|
|Π|`\Pi`|`$\Pi$`|$\Pi$|
|π|`\pi`|`$\pi$`|$\pi$|
|P|`P`|`$P$`|$P$|
|ρ|`\rho`|`$\rho$`|$\rho$|
|Σ|`\Sigma`|`$\Sigma$`|$\Sigma$|
|σ|`\sigma`|`$\sigma$`|$\sigma$|
|T|`T`|`$T$`|$T$|
|τ|`\tau`|`$\tau$`|$\tau$|
|Υ|`\Upsilon`|`$\Upsilon$`|$\Upsilon$|
|υ|`\upsilon`|`$\upsilon$`|$\upsilon$|
|Φ|`\Phi`|`$\Phi$`|$\Phi$|
|ϕ|`\phi`|`$\phi$`|$\phi$|
|X|`X`|`$X$`|$X$|
|χ|`\chi`|`$\chi$`|$\chi$|
|Ψ|`\Psi`|`$\Psi$`|$\Psi$|
|ψ|`\psi`|`$\psi$`|$\psi$|
|Ω|`\v`|`$\Omega$`|$\Omega$|
|ω|`\omega`|`$\omega$`|$\omega$|

字母	实现	字母	实现



