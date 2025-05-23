# Questions
	- Is the point $\begin{bmatrix}3\\ 4\end{bmatrix}$ on the line $\begin{bmatrix}x\\ y\end{bmatrix}=\begin{bmatrix}-1\\ 3\end{bmatrix}+t\begin{bmatrix}5\\ 7\end{bmatrix}$
	  logseq.order-list-type:: number
		- *Solution*.
			- To check if a point is on a vector equation, we need there to exist a value of $t\in\R$ that gives us this point using the equation for the line.
			  logseq.order-list-type:: number
				- If we substitute our $(3,4)$ into the equation, we can then solve for $t$.
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
	- Is the point $\begin{bmatrix}3\\ 4\end{bmatrix}$ on the line $\begin{bmatrix}x\\ y\end{bmatrix}=\begin{bmatrix}-1\\ 3\end{bmatrix}+t\begin{bmatrix}5\\ -2\end{bmatrix}$
	  logseq.order-list-type:: number
		- *Solution*.
		  logseq.order-list-type:: number
	- Is the point $\begin{bmatrix}3\\ 4\end{bmatrix}$ on the line $\begin{bmatrix}x\\ y\end{bmatrix}=t\begin{bmatrix}-1\\ 3\end{bmatrix}+\begin{bmatrix}5\\ -2\end{bmatrix}$
	  logseq.order-list-type:: number
		- *Solution*.
		  logseq.order-list-type:: number
			- logseq.order-list-type:: number
	- What is your **strategy** to solve this problem?
	  logseq.order-list-type:: number
	  
	  Find the vector equation of a line parallel to $7-x=\frac{y+5}{3}=\frac{z+26}{2}$ and passing through the point $(1,-2,9)$.
	  ---
	- Thinking & Application
	  logseq.order-list-type:: number
		- What do we know about the coordinates of every vector located on the xz-plane?
		  logseq.order-list-type:: number
			- *Solution*.
			  logseq.order-list-type:: number
			  collapsed:: true
			  ---
				- We know the y-coordinate is $0$. I.e. every vector looks like $(\#, 0, \#)$.
				  logseq.order-list-type:: number
		- Find the equation of the line which has a direction vector perpendicular to the xy-plane and passing through the origin. This line has another name, what is it?
		  logseq.order-list-type:: number
			- *Solution*.
			  logseq.order-list-type:: number
			  collapsed:: true
			  ---
				- A vector perpendicular to the xy-plane is $(0,0,1)$ and if this line passes through $(0,0,0)$ then we know the equation is, for $t\in\R$:
				  logseq.order-list-type:: number
				  $$(x,y,z)=t(0,0,1)$$
				- This line has the name "z-axis".
				  logseq.order-list-type:: number
		- Suppose A is on line 1 and B is on line 2. Find the coordinates of A and B such that $\vec{AB}$ is perpendicular to both lines. $t,k\in\R$
		  logseq.order-list-type:: number
		  $$\begin{cases} L_1: & \langle x,y,z \rangle = \langle 0,17,-10 \rangle +k\langle 2,0,1 \rangle \\ L_2: & \langle x,y,z \rangle =\langle 13,30,19 \rangle +t\langle 5,6,5 \rangle \end{cases}$$
			- *Solution*.
			  logseq.order-list-type:: number
			  collapsed:: true
			  ---
				- **Strategy**:
				  logseq.order-list-type:: number
					- This is a complicated one, let's break it down.
					  logseq.order-list-type:: number
					- If you made A a vector, what would it need to look like? What does every vector on $L_1$ look like? Use parameters to get a formula for the vector A.
					  logseq.order-list-type:: number
					- Do the same for vector B.
					  logseq.order-list-type:: number
					- Now get the vector $\vec{AB}$ from these formulas. It should be a rather large vector with multiple variables making up its components.
					  logseq.order-list-type:: number
					- This vector needs to be perpendicular to two known vectors. You see the word perpendicular which should cue up either:  dot product or cross product.
					  logseq.order-list-type:: number
						- When it comes to solving unknowns, use the dot product.
						  logseq.order-list-type:: number
						- The cross product is better for situations in which you need to create a vector which is perpendicular.
						  logseq.order-list-type:: number
					- Dot product your large formula based vector with each direction vector. You will get two equations in two variables, $t,k$, from doing this. Solve for both $t$ and $k$ with this system and then you can get points A and B from $t$ and $k$ using earlier formulas.
					  logseq.order-list-type:: number