## 行内与独行

### 独行公式
将公式插入到新的一行内，并且居中

- 方法：`$$公式内容$$`
- 范例：
```$$xyz$$```
- 显示
  $$xyz$$


## 上标、下标与组合

### 上标：`^`
- 预览代码：`$$x^4$$`
- 预览样式：
$$x^4$$
### 下标：`_`
- 预览代码：`$$x_1$$`
- 预览样式：
$$x_1$$
### 组合：`{}`
- 预览代码：`$$S_{2}O_{3}^{2+}$$`
- 预览样式：
$$S_{2}O_{3}^{2+}$$

## 汉字、字体与格式

### 字体控制：`\displaystyle`
- 预览代码：`$$\displaystyle \frac{x+y}{y+z}$$`
- 预览样式：
$$\displaystyle \frac{x+y}{y+z}$$
### 下划线：`\underline`
- 预览代码：`$$\underline{x+y}$$`
- 预览样式：
$$\underline{x+y}$$
### 标签：`\tag{数字}`
- 预览代码：`$$2x^2+3x+1=0   \tag{3}$$`
- 预览样式：
$$2x^2+3x+1=0   \tag{3}$$

- 上大括号：`\overbrace{算式}`
- 预览代码：`$$\overbrace{a+b+c+d}^{2.0}$$`
- 预览样式：
$$\overbrace{a+b+c+d}^{2.0}$$
### 下大括号：`underbrace{算式}`
- 预览代码：`$$a+\underbrace{b+c}_{1.0}+d$$`
- 预览样式：
$$a+\underbrace{b+c}_{1.0}+d$$
### 上下组合
- 预览代码：`$$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$$`
- 预览样式：
$$\overbrace{a+\underbrace{b+c}_{1.0}+d}^{2.0}$$
### 上位符号：
- `\stacrel{上位符号}{基位符号}`
- 预览代码：`$$3O_2 {\stackrel{\mathrm{_{放电}}}{=}} 2O_3$$`
- 预览样式：
$$3O_2 {\stackrel{\mathrm{_{放电}}}{=}} 2O_3$$
$$2S+3O_2 {{500℃} \atop {{\rightarrow} \atop {V_2O_5}} } SO_3$$
$$2S+3O_2 {{{500℃} \atop {\rightarrow}} \atop {_{V_2O_5}} } SO_3$$


## 占位符

- 两个quad空格：`\qquad`
- 预览代码：`$$x \qquad y$$`
- 预览样式：
$$x \qquad y$$
### quad空格：`\quad`
- 预览代码：`$$x \quad y$$`
- 预览样式：
$$x \quad y$$
### 大空格：`\`
- 预览代码：`$$x \ y$$`
- 预览样式：
$$x \ y$$
### 中空格：`\:`
- 预览代码：`$$x \: y$$`
- 预览样式：
$$x \: y$$
### 小空格：`\,`
- 预览代码：`$$x \, y$$`
- 预览样式：
$$x \, y$$
### 没有空格：
- 预览代码：`$$xy$$`
- 预览样式：
$$xy$$
### 紧贴：`\!`
- 预览代码：`$$x \! y$$`
- 预览样式：
$$x \! y$$

## 定界符与组合

- 小括号_{普通}：`()`
- 预览代码：`$$(内容)$$`
- 预览样式：
$$(内容)$$
### 小括号_{大}：`\big(\big)`
- 预览代码：`\big(内容\big)`
- 预览样式：
$$\big(内容\big)$$
### 小括号_{特大}：`\Big(\Big)`
- 预览代码：`$$\Big(内容\Big)$$`
- 预览样式：
$$\Big(内容\Big)$$
### 小括号_{超大}：`\bigg(\bigg)`
- 预览代码：`$$\bigg(内容\bigg)$$`
- 预览样式：
$$\bigg(内容\bigg)$$
### 小括号_{最大}：`\Bigg(\Bigg)`
- 预览代码：`$$\Bigg(内容\Bigg)$$`
- 预览样式：
$$\Bigg(内容\Bigg)$$
### 中括号：`[]`
- 预览代码：`$$[x+y]$$`
- 预览样式：
$$[x+y]$$
### 大括号：`\{ \}`
- 预览代码：`$$\{x+y\}$$`
- 预览样式：
$$\{x+y\}$$
### 自适应括号：`\left \right`
- 预览代码：`$$\left(x{yz}\right)$$`
- 预览样式：
$$\left(x{yz}\right)$$
### 括号组合：`{上位公式 \choose 下位公式}`
- 预览代码：`$${n+1 \choose k}={n \choose k}+{n \choose k-1}$$`
- 预览样式：
$${n+1 \choose k}={n \choose k}+{n \choose k-1}$$
### 上下组合：`{上位公式 \atop 下位公式}`
- 预览代码：`$$\{{x+y=2 \quad ① \atop 2x+3y=5 \quad ②}$$`
- 预览样式：
$$\{{x+y=2 \quad \atop 2x+3y=5 \quad }$$

## 四则运算

### 加法：`+`
- 预览代码：`$$x+y=z$$`
- 预览样式：
$$x+y=z$$
### 减法：`-`
- 预览代码：`$$x-y=z$$`
- 预览样式：
$$x-y=z$$
### 乘法：`\times`
- 预览代码：`$$x \times y=z$$`
- 预览样式：
$$x \times y=z$$
### 除法：`\div`
- 预览代码：`$$x \div y=z$$`
- 预览样式：
$$x \div y=z$$
### 加减：`\pm`
- 预览代码：`$$x \pm y=z$$`
- 预览样式：
$$x \pm y=z$$
### 减加：`\mp`
- 预览代码：`$$x \mp y=z$$`
- 预览样式：
$$x \mp y=z$$
### 点乘：`\cdot`
- 预览代码：`$$x \cdot y=z$$`
- 预览样式：
$$x \cdot y=z$$
### 星乘：`\ast`
- 预览代码：`$$x \ast y=z$$`
- 预览样式：
$$x \ast y=z$$
### 斜除：`/`
- 预览代码：`$$x/y=z$$`
- 预览样式：
$$x/y=z$$
### 分式：`\frac{分子}{分母}`
- 预览代码：`$$\frac{x+y}{y+z}$$`
- 预览样式：
$$\frac{x+y}{y+z}$$
### 分式：`{分子} \voer {分母}`
- 预览代码：`$${x+y} \over {y+z}$$`
- 预览样式：
$${x+y} \over {y+z}$$

## 高级运算

### 均值：`\overline{算式}`
- 预览代码：`$$\overline{xyz}$$`
- 预览样式：
$$\overline{xyz}$$
### 矢量：`\vec{矢量}`
- 预览代码：`$$\vec{x}$$`
- 预览样式：
$$\vec{x}$$
### 根号：`\sqrt`
- 预览代码：`$$\sqrt x$$`
- 预览样式：
$$\sqrt x$$
### 开方：`\sqrt[开方数]{被开方数}`
- 预览代码：`$$\sqrt[3]{x+y}$$`
- 预览样式：
$$\sqrt[3]{x+y}$$
### 对数：`\log`
- 预览代码：`$$\log(x)$$`
- 预览样式：
$$\log_{32}(x)$$
### 极限：`\lim`
- 预览代码：`$$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$`
- 预览样式：
$$\lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
### 极限：`\displaystyle \lim`
- 预览代码：`$$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$`
- 预览样式：
$$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
### 求和：`\sum`
- 预览代码：`$$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$`
- 预览样式：
$$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
### 求和：`\displaystyle \sum`
- 预览代码：`$$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$`
- 预览样式：
$$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$$
### 积分：`\int`
- 预览代码：`$$\int^{\infty}_{0}{xdx}$$`
- 预览样式：
$$\int^{\infty}_{0}{xdx}$$
### 积分：`\displaystyle \int`
- 预览代码：`$$\displaystyle \int^{\infty}_{0}{xdx}$$`
- 预览样式：
$$\displaystyle \int^{\infty}_{0}{xdx}$$
### 微分：`\partial`
- 预览代码：`$$\frac{\partial x}{\partial y}$$`
- 预览样式：
$$\frac{\partial x}{\partial y}$$
### 矩阵：`\begin{matrix} \end{matrix}`
- 预览代码：`$$\left[ \begin{matrix} 1 &2 &\cdots &4\5 &6 &\cdots &8\\vdots &\vdots &\ddots &\vdots\13 &14 &\cdots &16\end{matrix} \right]$$`
- 预览样式：
$$\left[ \begin{matrix} 1 &2 &\cdots &4 \\5 &6 &\cdots &8\\\vdots &\vdots &\ddots &\vdots \\13 &14 &\cdots &16\end{matrix} \right]$$

## 等式 & 不等式

### 等于：`=`
- 预览代码：`$$x+y=z$$`
- 预览样式：
$$x+y=z$$
### 大于：`>`
- 预览代码：`$$x+y>z$$`
- 预览样式：
$$x+y>z$$
### 小于：`<`
- 预览代码：`$$x+y<z$$`
- 预览样式：
$$x+y<z$$
### 大于等于：`\geq`
- 预览代码：`$$x+y \geq z$$`
- 预览样式：
$$x+y \geq z$$
### 小于等于：`\leq`
- 预览代码：`$$x+y \leq z$$`
- 预览样式：
$$x+y \leq z$$
### 不等于：`\neq`
- 预览代码：`$$x+y \neq z$$`
- 预览样式：
$$x+y \neq z$$
### 不大于等于：`\ngeq`
- 预览代码：`$$x+y \ngeq z$$`
- 预览样式：
$$x+y \ngeq z$$
### 不大于等于：`\not\geq`
- 预览代码：`$$x+y \not\geq z$$`
- 预览样式：
$$x+y \not\geq z$$
### 不小于等于：`\nleq`
- 预览代码：`$$x+y \nleq z$$`
- 预览样式：
$$x+y \nleq z$$
### 不小于等于：`\not\leq`
- 预览代码：`$$x+y \not\leq z$$`
- 预览样式：
$$x+y \not\leq z$$
### 约等于：`\approx`
- 预览代码：`$$x+y \approx z$$`
- 预览样式：
$$x+y \approx z$$
### 恒定等于：`\equiv`
- 预览代码：`$$x+y \equiv z$$`
- 预览样式：
$$x+y \equiv z$$

## 逻辑 & 集合

### 属于：`\in`
- 预览代码：`$$x \in y$$`
- 预览样式：
$$x \in y$$
### 不属于：`\notin`
- 预览代码：`$$x \notin y$$`
- 预览样式：
$$x \notin y$$
### 不属于：`\not\in`
- 预览代码：`$$x \not\in y$$`
- 预览样式：
$$x \not\in y$$
### 包含于：`\subseteq`
- 预览代码：`$$x \subseteq y$$`
- 预览样式：
$$x \subseteq y$$
### 真包含于：`\subset`
- 预览代码：`$$x \subset y$$`
- 预览样式：
$$x \subset y$$
### 真包含于：`\subsetneq`
- 预览代码：`$$x \subsetneq y$$`
- 预览样式：
$$x \subsetneq y$$
### 不包含于：`\not\subset`
- 预览代码：`$$x \not\subset y$$`
- 预览样式：
$$x \not\subset y$$
### 包含：`\supseteq`
- 预览代码：`$$x \supseteq y$$`
- 预览样式：
$$x \supseteq y$$
### 真包含：`\supset`
- 预览代码：`$$x \supset y$$`
- 预览样式：
$$x \supset y$$
### 真包含：`\supsetneq`
- 预览代码：`$$x \supsetneq y$$`
- 预览样式：
$$x \supsetneq y$$
### 不包含：`\not\supset`
- 预览代码：`$$x \not\supset y$$`
- 预览样式：
$$x \not\supset y$$
### 并集：`\cup`
- 预览代码：`$$x \cup y$$`
- 预览样式：
$$x \cup y$$
### 交集：`\cap`
- 预览代码：`$$x \cap y$$`
- 预览样式：
$$x \cap y$$
### 差集：`\setminus`
- 预览代码：`$$x \setminus y$$`
- 预览样式：
$$x \setminus y$$
### 同或：`\bigodot`
- 预览代码：`$$x \bigodot y$$`
- 预览样式：
$$x \bigodot y$$
### 同与：`\bigotimes`
- 预览代码：`$$x \bigotimes y$$`
- 预览样式：
$$x \bigotimes y$$
### 实数集：`\mathbb{R}`
- 预览代码：`$$\mathbb{R}$$`
- 预览样式：
$$\mathbb{R}$$
### 自然数集：`\mathbb{Z}`
- 预览代码：`$$\mathbb{Z}$$`
- 预览样式：
$$\mathbb{Z}$$
### 空集：`\emptyset`
- 预览代码：`$$\emptyset$$`
- 预览样式：
$$\emptyset$$

## 数学符号

### 无穷：`\infty`
- 预览代码：`$$\infty$$`
- 预览样式：
$$\infty$$
### 虚数i：`\imath`
- 预览代码：`$$\imath$$`
- 预览样式：
$$\imath$$
### 虚数j：`\jmath`
- 预览代码：`$$\jmath$$`
- 预览样式：
$$\jmath$$
### 一阶导数：`\dot{a}`
- 预览代码：`$$\dot{a}$$`
- 预览样式：
$$\dot{a}$$
### 二阶导数：`\ddot{a}`
- 预览代码：`$$\ddot{a}$$`
- 预览样式：
$$\ddot{a}$$
### 上—：`\bar{a}`
- 预览代码：`$$\bar{a}$$`
- 预览样式：
$$\bar{a}$$
### 上/：`\acute{a}`
- 预览代码：`$$\acute{a}$$`
- 预览样式：
$$\acute{a}$$
### 上√：`\check{a}`
- 预览代码：`$$\check{a}$$`
- 预览样式：
$$\check{a}$$
### 上\：`\grave{a}`
- 预览代码：`$$\grave{a}$$`
- 预览样式：
$$\grave{a}$$
### 上^：`\hat{a}`
- 预览代码：`$$\hat{a}$$`
- 预览样式：
$$\hat{a}$$
### 上︶：`\breve{a}`
- 预览代码：`$$\breve{a}$$`
- 预览样式：
$$\breve{a}$$
### 上~：`\tilde{a}`
- 预览代码：`$$\tilde{a}$$`
- 预览样式：
$$\tilde{a}$$
### 上。：`\mathring{a}`
- 预览代码：`$$\mathring{a}$$`
- 预览样式：
$$\mathring{a}$$
### 上箭头：`\uparrow`
- 预览代码：`$$\uparrow$$`
- 预览样式：
$$\uparrow$$
### 上箭头：`\Uparrow`
- 预览代码：`$$\Uparrow$$`
- 预览样式：
$$\Uparrow$$
### 下箭头：`\downarrow`
- 预览代码：`$$\downarrow$$`
- 预览样式：
$$\downarrow$$
### 下箭头：`\Downarrow`
- 预览代码：`$$\Downarrow$$`
- 预览样式：
$$\Downarrow$$
### 左箭头：`\leftarrow`
- 预览代码：`$$\leftarrow$$`
- 预览样式：
$$\leftarrow$$
### 左箭头：`\Leftarrow`
- 预览代码：`$$\Leftarrow$$`
- 预览样式：
$$\Leftarrow$$
### 右箭头：`\rightarrow`
- 预览代码：`$$\rightarrow$$`
- 预览样式：
$$\rightarrow$$
### 右箭头：`\Rightarrow`
- 预览代码：`$$\Rightarrow$$`
- 预览样式：
$$\Rightarrow$$
### 省略号底：`\ldots`
- 预览代码：`$$1,2,\ldots,n$$`
- 预览样式：
$$1,2,\ldots,n$$
### 省略号中：`\cdots`
- 预览代码：`$$x_1^2 + x_2^2 + \cdots + x_n^2$$`
- 预览样式：
$$x_1^2 + x_2^2 + \cdots + x_n^2$$
### 省略号竖：`\vdots`
- 预览代码：`$$\vdots$$`
- 预览样式：
$$\vdots$$
### 省略号斜：`\ddots`
- 预览代码：`$$\ddots$$`
- 预览样式：
$$\ddots$$

## 希腊字母

### A：`A`
- 预览代码：`$$A$$`
- 预览样式：
$$A$$
### α：`\alpha`
- 预览代码：`$$\alpha$$`
- 预览样式：
$$\alpha$$
### B：`B`
- 预览代码：`$$B$$`
- 预览样式：
$$B$$
### β：`\beta`
- 预览代码：`$$\beta$$`
- 预览样式：
$$\beta$$
### Γ：`\Gamma`
- 预览代码：`$$\Gamma$$`
- 预览样式：
$$\Gamma$$
### γ：`\gamma`
- 预览代码：`$$\gamma$$`
- 预览样式：
$$\gamma$$
### Δ：`\Delta`
- 预览代码：`$$\Delta$$`
- 预览样式：
$$\Delta$$
### δ：`\delta`
- 预览代码：`$$\delta$$`
- 预览样式：
$$\delta$$
### E：`E`
- 预览代码：`$$E$$`
- 预览样式：
$$E$$
### ϵ：`\epsilon`
- 预览代码：`$$\epsilon$$`
- 预览样式：
$$\epsilon$$
### Z：`Z`
- 预览代码：`$$Z$$`
- 预览样式：
$$Z$$
### ζ：`\zeta`
- 预览代码：`$$\zeta$$`
- 预览样式：
$$\zeta$$
### H：`H`
- 预览代码：`$$H$$`
- 预览样式：
$$H$$
### η：`\eta`
- 预览代码：`$$\eta$$`
- 预览样式：
$$\eta$$
### Θ：`\Theta`
- 预览代码：`$$\Theta$$`
- 预览样式：
$$\Theta$$
### θ：`\theta`
- 预览代码：`$$\theta$$`
- 预览样式：
$$\theta$$
### I：`I`
- 预览代码：`$$I$$`
- 预览样式：
$$I$$
### ι：`\iota`
- 预览代码：`$$\iota$$`
- 预览样式：
$$\iota$$
### K：`K`
- 预览代码：`$$K$$`
- 预览样式：
$$K$$
### κ：`\kappa`
- 预览代码：`$$\kappa$$`
- 预览样式：
$$\kappa$$
### Λ：`\Lambda`
- 预览代码：`$$\Lambda$$`
- 预览样式：
$$\Lambda$$
### λ：`\lambda`
- 预览代码：`$$\lambda$$`
- 预览样式：
$$\lambda$$
### M：`M`
- 预览代码：`$$M$$`
- 预览样式：
$$M$$
### μ：`\mu`
- 预览代码：`$$\mu$$`
- 预览样式：
$$\mu$$
### N：`N`
- 预览代码：`$$N$$`
- 预览样式：
$$N$$
### ν：`\nu`
- 预览代码：`$$\nu$$`
- 预览样式：
$$\nu$$
### Ξ：`\Xi`
- 预览代码：`$$\Xi$$`
- 预览样式：
$$\Xi$$
### ξ：`\xi`
- 预览代码：`$$\xi$$`
- 预览样式：
$$\xi$$
### O：`O`
- 预览代码：`$$O$$`
- 预览样式：
$$O$$
### ο：`\omicron`
- 预览代码：`$$\omicron$$`
- 预览样式：
$$\omicron$$
### Π：`\Pi`
- 预览代码：`$$\Pi$$`
- 预览样式：
$$\Pi$$
### π：`\pi`
- 预览代码：`$$\pi$$`
- 预览样式：
$$\pi$$
### P：`P`
- 预览代码：`$$P$$`
- 预览样式：
$$P$$
### ρ：`\rho`
- 预览代码：`$$\rho$$`
- 预览样式：
$$\rho$$
### Σ：`\Sigma`
- 预览代码：`$$\Sigma$$`
- 预览样式：
$$\Sigma$$
### σ：`\sigma`
- 预览代码：`$$\sigma$$`
- 预览样式：
$$\sigma$$
### T：`T`
- 预览代码：`$$T$$`
- 预览样式：
$$T$$
### τ：`\tau`
- 预览代码：`$$\tau$$`
- 预览样式：
$$\tau$$
### Υ：`\Upsilon`
- 预览代码：`$$\Upsilon$$`
- 预览样式：
$$\Upsilon$$
### υ：`\upsilon`
- 预览代码：`$$\upsilon$$`
- 预览样式：
$$\upsilon$$
### Φ：`\Phi`
- 预览代码：`$$\Phi$$`
- 预览样式：
$$\Phi$$
### ϕ：`\phi`
- 预览代码：`$$\phi$$`
- 预览样式：
$$\phi$$
### X：`X`
- 预览代码：`$$X$$`
- 预览样式：
$$X$$
### χ：`\chi`
- 预览代码：`$$\chi$$`
- 预览样式：
$$\chi$$
### Ψ：`\Psi`
- 预览代码：`$$\Psi$$`
- 预览样式：
$$\Psi$$
### ψ：`\psi`
- 预览代码：`$$\psi$$`
- 预览样式：
$$\psi$$
### Ω：`\v`
- 预览代码：`$$\Omega$$`
- 预览样式：
$$\Omega$$
### ω：`\omega`
- 预览代码：`$$\omega$$`
- 预览样式：
$$\omega$$
