# 3, 2, 1, Take off
	- Today our **goal** is to describe how to plot a plane in $\mathbb{R}^3$ using vector and parametric equations.
- ## Forced Recall #.v-self-border
	- Find a vector, $\vec{w}$, which is perpendicular to both $\vec{v}={}\begin{bmatrix}-5\\ 1\\ -5\end{bmatrix}$ and $\vec{u}={}\begin{bmatrix}1\\ 3\\ 11\end{bmatrix}$.
	  logseq.order-list-type:: number
		- *Solution.*
		  logseq.order-list-type:: number
		  collapsed:: true
			- We use the ==[[cross product]]==: $\vec{u}\times \vec{v}$.
			  logseq.order-list-type:: number
			- logseq.order-list-type:: number
			  $$\begin{matrix}
			  \cancel{-5} & 1 & -5 & -5 & 1 & \cancel{-5} \\
			  \cancel{1} & 3 & 11 & 1 & 3 & \cancel{11}
			  \end{matrix}$$
			- Then a perpendicular vector would be:
			  logseq.order-list-type:: number
			- logseq.order-list-type:: number
			  $$
			  \begin{bmatrix} 
			  1(11) - (-5)(3) \\ -5(1) - (-5)(11) \\ -5(3)-(1)(1) \end{bmatrix} 
			  = \begin{bmatrix} 
			  26 \\ 50 \\ -16 
			  \end{bmatrix}$$
			- Since this vector is has large numbers and we will find a smaller parallel vector:  Let
			  logseq.order-list-type:: number
			- logseq.order-list-type:: number
			  $$\vec{w} = \frac12\begin{bmatrix}26\\ 50\\ -16\end{bmatrix}=\begin{bmatrix}13\\ 25\\ -8\end{bmatrix}$$
	- Prove $\vec{w}$ is perpendicular to $\vec{v}$ and $\vec{u}$ by showing that $w\cdot u=0=w\cdot v$.
	  logseq.order-list-type:: number
		- *Solution.*
		  logseq.order-list-type:: number
		  collapsed:: true
			- logseq.order-list-type:: number
			  $$\begin{align*}
			  & \begin{bmatrix}
			  13\\ 25\\ -8
			  \end{bmatrix}
			  \cdot\begin{bmatrix}
			  -5\\ 1\\ -5
			  \end{bmatrix} \\
			  =& 13\left(-5\right)+25\left(1\right)+\left(-8\right)\left(-5\right) \\
			  =& -65+25+40 \\
			  =& 0
			  \end{align*}$$
			- logseq.order-list-type:: number
			  $$\begin{align*}
			  & \begin{bmatrix}
			  13\\ 25\\ -8
			  \end{bmatrix}
			  \cdot\begin{bmatrix}
			  1\\ 3\\ 11
			  \end{bmatrix} \\
			  =& 13\left(1\right)+25\left(3\right)+\left(-8\right)\left(11\right) \\
			  =& 13+75-88 \\
			  =& 0
			  \end{align*}$$
			- It's like magic!
			  logseq.order-list-type:: number
- ## Action
	- ### Example 1.
		- Find vector and parametric equations of the plane with points $A(2,4,-2)$, $B(3,7,9)$, and $C(-2,8,4)$. What is going on here? Draw a diagram. Why can a diagram help solve this problem?
			- **Strategy.**
				- A plane is a flat surface. We are familiar with one plane very well, the ==[Cartesian plane]([[Cartesian]])==. How many vectors are needed to find any point on this plane?
				- You need two! An $\hat{x}=(1,0)$ and a $\hat{y}=(0,1)$. Using this scale, we can make any point on the plane.
				- In fact, we can use any scale like this. We could take
			- *Solution.*
				- First we find vectors $\vec{AB}$ and $\vec{BC}$.
				  logseq.order-list-type:: number