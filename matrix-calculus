# Matrix Calculus

Lecture by Farrukh Rahman, transcribed by Matthew Caseres

## Scalar-valued functions of a single variable

Use the chain rule to take the derivative of the function below.

$$
\begin{array}{l}
f: \mathbb{R} \rightarrow \mathbb{R}, \quad x \in \mathbb{R}\\
y=f(x)=x^{2} \ln \left(x^{2}\right) \\
y^{\prime}=\frac{d f}{d x}=2x\left(1+\ln\left(x^{2}\right)\right)\\
\end{array}
$$

## Vector-valued functions of a single variable

A function can take a single variable and output a vector.

$$
\begin{array}{l}
\begin{array}{l}
f: \mathbb{R} \rightarrow \mathbb{R}^{3} \\
f(x)=\left[\begin{array}{l}
f_{1} \\
f_{2} \\
f_{3}
\end{array}\right] = \left[\begin{array}{c}
3 x^{2}+x \\
e^{x} \\
\ln (x)
\end{array}\right]
\end{array}\\
\frac{d f}{d x}=\left[\begin{array}{c}
\frac{d f_{1}}{d x} \\
\frac{\partial f_{2}}{d x} \\
\frac{d f_{3}}{d x}
\end{array}\right]=\left[\begin{array}{c}
6 x+1 \\
e^{x} \\
\frac{1}{x}
\end{array}\right] \in \mathbb{R}^{3 \times 1}\\
\end{array}
$$

## Matrix valued functions of a single variable

Differentiate each function with respect to the variable.

$$
\begin{array}{l}
f(x)=\left[\begin{array}{ll}
f_{1} & f_{2} \\
f_{3} & f_{4}
\end{array}\right]=\left[\begin{array}{ll}
\cos (x) & \sin (x) \\
e^{x} & \tanh (x)
\end{array}\right] \\
\frac{d f}{d x}=\left[\begin{array}{ll}
\frac{\partial f_{1}}{\partial x} & \frac{\partial f_{2}}{\partial x} \\
\frac{\partial f_{3}}{\partial x} & \frac{\partial f_{4}}{\partial x}
\end{array}\right]=\left[\begin{array}{ll}
-\sin (x) & \cos (x) \\
e^{x} & 1-\tanh ^{2}(x)
\end{array}\right]
\end{array}
$$

## Scalar-valued functions of a multiple variables

We take the derivative with respect to the transposed elements of $x$.

$$
x = \left[\begin{array}{l}
x_{1} \\
x_{2} \\
x_{3}
\end{array}\right]
\\
$$

$$
y = x_1x_2x_3
$$

$$
\frac{dy}{dx} = \left[\begin{array}{l}
\frac{\partial y}{\partial x_1} &
\frac{\partial y}{\partial x_2}  &
\frac{\partial y}{\partial x_3} 
\end{array}\right] = \left[\begin{array}{l}
x_2x_3 &
x_1x_3 &
x_1x_2
\end{array}\right]
$$

This is in numerator layout. 

## Scalar-valued functions of matrices

We take the derivative with respect to the transposed elements of $x$. This is a generalization of the previous case.

$$
\begin{array}{l}
f: \mathbb{R}^{2 x 3} \rightarrow  \mathbb{R} \\
x=\left[\begin{array}{lll}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23}
\end{array}\right] \\
f(x)=\sum_{i} \sum_{j} x_{i j} \\
\frac{\partial y}{\partial x}=\left[\begin{array}{ll}
\frac{\partial f}{\partial x_{11}} & \frac{\partial f}{\partial x_{21}} \\
\frac{\partial f}{\partial x_{12}} & \frac{\partial f}{\partial x_{22}} \\
\frac{\partial f}{\partial x_{13}} & \frac{\partial f}{\partial x_{23}}
\end{array}\right]=\left[\begin{array}{ll}
1 & 1 \\
1 & 1 \\
1 & 1
\end{array}\right] \in \mathbb{R}^{3 \times 2} \\
\end{array}
$$


## Vector-valued functions of multiple variables

We differentiate each function in the vector with respect to the vector $x$. Each component function $f_i$ is treated as a scalar-valued function when differentiated.

$$
\begin{array}{l}
f: R^{3} \rightarrow R^{2} \quad \vec{x}=\left[\begin{array}{l}
x_{1} \\
x_{2} \\
x_{3}
\end{array}\right] \quad \\ f(\vec{x})=\left[\begin{array}{l}
f_{1} \\
f_{2}
\end{array}\right]=\left[\begin{array}{l}
x_{1}+x_{1} x_{2} + x_1x_3\\
x_{1}^{2}+2 x_{3}
\end{array}\right]\\
\displaystyle\frac{d f(\vec{x})}{d \vec{x}}=\left[\begin{array}{l}
\displaystyle\frac{df_{1}}{dx} \\
\displaystyle\frac{df_{2}}{dx}
\end{array}\right]=\left[\begin{array}{lll}
\frac{\delta f_{1}}{\delta x_{1}} & \frac{\delta f_{1}}{\partial x_{2}} & \frac{\delta f_{1}}{\delta x_{3}} \\
\frac{\delta f_{2}}{\partial x_{1}} & \frac{\delta f_{2}}{\delta x_{2}} & \frac{\partial f_{2}}{\partial x_{3}}
\end{array}\right]=\left[\begin{array}{lll}
1+x_2+x_3 & x_1 & x_1 \\
 \quad \quad 2x_1 & 0 & 2
\end{array}\right]
\end{array}
$$

### Another example (identity function)

$$
\begin{aligned}
x &=\left[\begin{array}{l}
x_{1} \\
x_{2} \\
x_{3}
\end{array}\right] \\
f(x) &= \left[\begin{array}{l}
f_{1} \\
f_{2} \\
f_{2}
\end{array}\right]=\left[\begin{array}{l}
x_{1} \\
x_{2} \\
x_{3}
\end{array}\right] \\
\frac{\partial f}{\partial x} &=\left[\begin{array}{l}
\frac{\partial f_{1}}{\partial x} \\
\frac{\partial f_{2}}{\partial x} \\
\frac{\partial f_{3}}{\partial x}
\end{array}\right]=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]
\end{aligned}
$$

## Vector-valued functions of a matrix

We differentiate each function in the vector with respect to the matrix $x$.

$$
f: \mathbb{R}^{2 \times 3} \rightarrow \mathbb{R}^{4}\\
$$

$$
x=\left[\begin{array}{lll}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23}
\end{array}\right]\\
$$

$$
f(x)=\left[\begin{array}{l}
f_{1} \\
f_{2} \\
f_{3} \\
f_{4}
\end{array}\right]=\left[\begin{array}{lll}
\sum_{i} \sum_{j} x_{i j}  \\
x_{11}x_{22}x_{23} \\
x_{12}x_{21} \\
x_{21}x_{22}x_{23}
\end{array}\right]
$$

$$
\frac{df}{dx}= \left[\begin{array}{l}
\displaystyle\frac{df_{1}}{dx} \\
\displaystyle\frac{df_{2}}{dx} \\
\displaystyle\frac{df_{3}}{dx} \\
\displaystyle\frac{df_{4}}{dx}
\end{array}\right] =
\left[\begin{array}{cc}
\left[\begin{array}{ll}
1 & 1 \\
1 & 1 \\
1 & 1 \\
\end{array}\right] \\
\left[\begin{array}{ll}
x_{22} x_{23} & 0 & \\
0 & x_{11} x_{23} \\
0 & x_{11} x_{22}
\end{array}\right] \\
\left[\begin{array}{ccc}
0 & x_{12} \\
x_{21} & 0 \\
0 & 0 & \\
\end{array}\right] \\
\left[\begin{array}{ccc}
0 & x_{22} x_{23} \\
0 & x_{21} x_{23} \\
0 & x_{21} x_{22}
\end{array}\right]
\end{array}
\right] \in \mathbb{R}^{4\times3\times2}
$$

According to Wikipedia numerator layout is "lay out according to **y** and $\mathbb{x}^T$" and that denominator layour is "according to $\mathbb{y}^T$ and $\mathbb{x}$". No examples here are in denominator format, and the slides seem to follow this rule as well. This is why everything is in the shape of $y$ and then nested inside it is in the shape of $x^T$.


## Matrix-valued functions of multiple variables

Much the same as for vector-valued functions. Regardless the dimension of $x$ the answer will be

$$
f(x)=\left[\begin{array}{l}
f_{11} & f_{12} \\
f_{21} & f_{22} \\
\end{array}\right]
$$

$$
\frac{df}{dx}=\left[\begin{array}{l}
\displaystyle\frac{df_{11}}{dx} & \displaystyle\frac{df_{12}}{dx} \\
\displaystyle\frac{df_{21}}{dx} & \displaystyle\frac{df_{22}}{dx} \\
\end{array}\right]
$$

So we have a $2\times2\times \left(\text{the dimensions from } \displaystyle\frac{df_{ij}}{dx}\text{ which are same as }x^T\right)$.
