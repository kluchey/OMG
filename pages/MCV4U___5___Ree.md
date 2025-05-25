# Let's form some strategies:  Specific Questions #.v-border-children
	- Is the point $\begin{bmatrix}3\\ 4\end{bmatrix}$ on the line $\begin{bmatrix}x\\ y\end{bmatrix}=\begin{bmatrix}-1\\ 3\end{bmatrix}+t\begin{bmatrix}5\\ 7\end{bmatrix}$
	  logseq.order-list-type:: number
		- *Solution*.
		  collapsed:: true
		  ---
			- To check if a point is on a vector equation, we need there to exist a value of $t\in\R$ that gives us this point using the equation for the line.
			  logseq.order-list-type:: number
				- If we substitute our $(3,4)$ into the equation, we can then solve for $t$.
				  logseq.order-list-type:: number
					- If $t$ is different from both equations (not equal) then the point is not on the line.
					  logseq.order-list-type:: number
					- If $t$ is ==[[consistent]]== then the point is on the line.
					  logseq.order-list-type:: number
			- logseq.order-list-type:: number
	- Is the point $\begin{bmatrix}3\\ 4\end{bmatrix}$ on the line $\begin{bmatrix}x\\ y\end{bmatrix}=t\begin{bmatrix}-1\\ 3\end{bmatrix}+\begin{bmatrix}5\\ -2\end{bmatrix}$
	  logseq.order-list-type:: number
		- *Solution*.
		  logseq.order-list-type:: number
		  collapsed:: true
		  ---
			- We will solve this by ==[[inspection]]==, a strategy you are allowed in higher maths when solving simple equations.
			  logseq.order-list-type:: number
			- By inspection, the solution $t=2$ demonstrates that:
			  logseq.order-list-type:: number
				- $$\begin{align*}
				  \begin{bmatrix} x\\ y\end{bmatrix}
				  &=t\begin{bmatrix}-1 \\ 3\end{bmatrix}+\begin{bmatrix}5\\-2\end{bmatrix} \\
				  &= (2)\begin{bmatrix}-1 \\ 3\end{bmatrix}+\begin{bmatrix}5\\-2\end{bmatrix} \\
				  &= \begin{bmatrix}-2 \\ 6\end{bmatrix}+\begin{bmatrix}5\\-2\end{bmatrix} \\
				  &= \begin{bmatrix}-2+5 \\ 6-2\end{bmatrix} \\
				  &= \begin{bmatrix}3 \\ 4\end{bmatrix}
				  \end{align*}$$
				- So $(3,4)$ is on the line.
	- What is your **strategy** to solve this problem?
	  logseq.order-list-type:: number
		- {{embed ((682fc283-167a-4783-aa8e-b38c9fbb8ffc))}}
		- *Solution*.
		  collapsed:: true
		  ---
			- We need to be knowledgeable about the symmetric equation. Its general form is
			  $$\frac{x-P_{x}}{d_{x}}=_{}\frac{y-P_{x}}{d_{y}}=\frac{z-P_{z}}{d_{z}}$$
			- Since the new line is ==[[parallel]]== we can use the same direction vector $\vec{d}=(d_x,d_y,d_z)$ as the original line. The new line needs to pass through the given point, so we let $\vec{P}$ be that point.
			- We let $t\in\R$ and substitute $\vec{d}$ and $\vec{P}$ into $\vec{v}=\vec{P}+t\vec{d}$.
	- What is your **strategy** to solve the 5c problem? How do 5a and 5b help? Do we need to know anything else from Unit 1 to be able to solve 5c?
	  logseq.order-list-type:: number
		- {{embed ((682fc283-1a69-4041-a488-2832ca1eaf96))}}
		  logseq.order-list-type:: number
	-