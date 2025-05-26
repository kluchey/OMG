# 3, 2, 1, Take off
	- Today our **goal** is to describe how to plot a plane in $\mathbb{R}^3$ using vector and parametric equations.
- ## Forced Recall #.v-self-border
	- Find a vector, $\vec{w}$, which is perpendicular to both $\vec{v}={}\begin{bmatrix}-5\\ 1\\ -5\end{bmatrix}$ and $\vec{u}={}\begin{bmatrix}1\\ 3\\ 11\end{bmatrix}$.
	  logseq.order-list-type:: number
		- *Solution.*
		  logseq.order-list-type:: number
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