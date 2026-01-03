# Laboratory 2

Hey World! This is the first document.

This is a simple document[^1].

This is a new paragraph.

# Laboratory 3

## Math mode

A sentence with inline mathematics: $y = mx + c$

A second sentence with inline mathematics: $5^{2} = 3^{2} + 4^{2}$

A second paragraph containing display math. $$y = mx + c$$ See how the paragraph continues after the display.

### Inline math mode and mathematical notation

Superscripts $a^{b}$ and subscripts $a_{b}$

Some mathematics: $y = 2 \sin \theta^{2}$

### Display mathematics

A paragraph about a larger equation $$\int_{-\infty}^{+\infty} e^{-x^2} \, dx$$

A paragraph about a larger equation $$\int_{-\infty}^{+\infty} e^{-x^2} \mathop{}\!dx$$

A paragraph about a larger equation $$\begin{equation}
   \int_{-\infty}^{+\infty} e^{-x^2} \, dx
\end{equation}$$

## The amsmath package

Solve the following recurrence for $n, k\geq 0$: $$\begin{align*}
   Q_{n,0} &=1 \quad Q_{0,k} = [k=0]; \\
   Q_{n,k} &= Q_{n-1, k}+Q_{n-1, k-1}+\binom{n}{k},
   \quad\text{for $n$, $k>0$.}
\end{align*}$$

AMS matrices. $$\begin{matrix}
   a & b & c \\
   d & e & f
\end{matrix}
\quad
\begin{pmatrix}
   a & b & c \\
   d & e & f
\end{pmatrix}
\quad
\begin{bmatrix}
   a & b & c \\
   d & e & f
\end{bmatrix}$$

## Fonts in math mode

$\text{bad use } size \neq \mathit{size} \neq \mathrm{size}$ *$\text{bad use } size \neq \mathit{size} \neq \mathrm{size}$*

## Further amsmath alignments

Gather $$\begin{gather}
   P(x)=ax^{5} + bx^{4} + cx^{3} + dx^{2}+ ex + f\\
   x^{2}+1=10
\end{gather}$$

Multline $$\begin{multline*}
   (a+b+c+d)x^{5} + (b+c+d+e)x^{4}\\
   +(c+d+e+f)x^{3}+(d+e+f+a)x^{2}+(e+d+f+a+b)x\\
   +(f+a+b+c)
\end{multline*}$$

### Columns in math alignments

Aligned equations $$\begin{align*}
   a &= b+1 & c &= d+3 & e &= f+3\\
   r &= s^{2} & t &=u^{3} & v &= w^{4}
\end{align*}$$

- $\begin{aligned}[t]
          a&=b\\
          c&=d
      \end{aligned}$

- $\begin{aligned}
          a&=b\\
          c&=d
      \end{aligned}$

## Bold Math

$(x+y)(x-y)=x^{2}-y^{2}$

$(x+y)(x-y)=x^{2}-y^{2}$ $\pi r^2$

$(x+\mathbf{y})(x-\mathbf{y})=x^{2}-{\mathbf{y}}^{2}$

$\mathbf{\pi} r^2$

$(x+\mathbf{y})(x-\mathbf{y})=x^{2}-{\mathbf{y}}^{2}$

$(x+\bm{y})(x-\bm{y}) \bm{=} x^{2}-{\bm{y}}^{2}$

$\alpha + \bm{\alpha} < \beta + \bm{\beta}$

## Mathtools

$$\begin{pmatrix*}[r]
    10&11\\
    3&4\\
    -7&-8
\end{pmatrix*}$$

One two Three $$\log \alpha + \log \beta = \log(\alpha\beta)$$

## Mathematical alphabets

$$A + \mathfrak{A}+\mathbf{A} + \mathscr{A} + \mathbb{A}$$

[^1]: with a footnote
