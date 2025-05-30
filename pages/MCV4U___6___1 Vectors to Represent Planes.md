# 3, 2, 1, Take off
	- >> Today our **goal** is to describe how to plot a plane in $\mathbb{R}^3$ using vector and parametric equations.
- ## Forced Recall #.v-self-border
	- Find a vector, $\vec{w}$, which is perpendicular to both $\vec{v}={}\begin{bmatrix}-5\\ 1\\ -5\end{bmatrix}$ and $\vec{u}={}\begin{bmatrix}1\\ 3\\ 11\end{bmatrix}$. #card #MCV4U #CV6
	  logseq.order-list-type:: number
		- *Solution.*
		  logseq.order-list-type:: number
		  collapsed:: true
			- We use the ==[[cross product]]==: $\vec{u}\times \vec{v}$.
			  logseq.order-list-type:: number
			- logseq.order-list-type:: number
			  $$\begin{matrix}\cancel{-5} & 1 & -5 & -5 & 1 & \cancel{-5}\\ \cancel{1} & 3 & 11 & 1 & 3 & \cancel{11}\end{matrix}$$
			- Then a perpendicular vector would be:
			  logseq.order-list-type:: number
			- logseq.order-list-type:: number
			  $$
			  \begin{bmatrix} 
			  1(11) - (-5)(3) \\ -5(1) - (-5)(11) \\ -5(3)-(1)(1) \end{bmatrix} 
			  = \begin{bmatrix} 
			  26 \\ 50 \\ -16 
			  \end{bmatrix}$$
			- Since this vector has large numbers, we will find a shorter, parallel vector:  Let
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
- ## Action #.v-self-border
	- ### Example 1.
		- Find vector and parametric equations of the plane with points $A(2,4,-2)$, $B(3,7,9)$, and $C(-2,8,4)$. What is going on here? Draw a diagram. Why can a diagram help solve this problem?
			- **Strategy.**
			  collapsed:: true
				- A plane is a flat surface. We are familiar with one plane very well, the ==[Cartesian plane]([[Cartesian]])==. How many vectors are needed to find any point on this plane?
				- You need two! An $\hat{x}=(1,0)$ and a $\hat{y}=(0,1)$. Using this scale, we can make any point on the plane.
				- In fact, we can use any scale like this. We could take $\hat{x}=(3,0)$ and a $\hat{y}=(0,\frac17)$. This wouldn't be as convenient for integer points but we could make it work.
				- So the xy-plane has equation $(x,y)=t(1,0)+k(0,1)$ for $t,k\in\R$.
				- Let's use two vectors in the same way but without being restricted to the x and y axis.
				- ![image.png](../assets/image_1748230564531_0.png){:height 324, :width 376}
					- Source:  #cite #later https://medium.com/@joshua.wheeler/introduction-to-linear-algebra-with-applications-to-machine-learning-image-compression-f5de08f120df
			- *Solution.*
			  collapsed:: true
				- ![image.png](../assets/image_1748230825110_0.png)
				  logseq.order-list-type:: number
					- Imagine this had points A, B, C instead of Q, P, R.
					  logseq.order-list-type:: number
					- Source:  #cite #LATER https://thejuniverse.org/PUBLIC/LinearAlgebra/LOLA/planes/find.html
					  logseq.order-list-type:: number
				- First we find vectors $\vec{AB}$ and $\vec{BC}$. These will be our "scale" or, as we will call them now, our two ==[direction vectors]([[direction vector]])==. In future courses, you will call these vectors your [[basis]].
				  logseq.order-list-type:: number
				- By ==[[inspection]]==, $\vec{AB} = (1,3,11)$ and $\vec{BC} = (-5, 1, -5)$.
				  logseq.order-list-type:: number
				- Let $t,k\in\R$. Then our plane may be represented by:
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{bmatrix}2\\ 4\\ -2\end{bmatrix}+t\begin{bmatrix}1\\ 3\\ 11\end{bmatrix}+k\begin{bmatrix}-5\\ 1\\ -5\end{bmatrix}$$
				- With parametric equations:
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{cases}
				  x &= 2 + t -5k \\
				  y &= 4 + 3t + k \\
				  z &= -2 + 11t -5k
				  \end{cases}$$
	- ### Example 2.
		- Find the vector and parametric equations of the plane that is perpendicular to the plane
			- $$\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}1\\ 2\\ 3\end{bmatrix}+t\begin{bmatrix}-2\\ 4\\ 6\end{bmatrix}+k\begin{bmatrix}1\\ 3\\ -4\end{bmatrix}$$
			- and contains the line
			- $$\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}-3\\ 4\\ 6\end{bmatrix}+q\begin{bmatrix}1\\ 0\\ 2\end{bmatrix}$$
			- for $t,k,q\in\R$. Draw the *roughest* diagram of this situation.
			- **Strategy.**
			  collapsed:: true
				- Find the cross product of the two direction vectors of the plane provided. This gives a direction which is perpendicular to the plane provided.
				  logseq.order-list-type:: number
				- If we need to contain the line, the position vector and the direction must both be on our new plane.
				  logseq.order-list-type:: number
				- Counting what we have, you can see we have two directions and one position. This is all we need to define the plane.
				  logseq.order-list-type:: number
			- *Solution.*
			  collapsed:: true
				- Cross product:
					- $$\begin{matrix}
					  \cancel{-2} & 4 & 6 & -2 & 4 & \cancel{6} \\
					  \cancel{1} & 3 & -4 & 1 & 3 & \cancel{-4}
					  \end{matrix}$$
					- Then a perpendicular vector would be:
					- $$
					  \begin{bmatrix} 
					  4(-4) - (6)(3) \\ 6(1) - (-2)(-4) \\ -2(3)-(4)(1) \end{bmatrix} 
					  = \begin{bmatrix} 
					  -34 \\ -2 \\ -10 
					  \end{bmatrix}$$
					- We'll set $\vec{d}_1= -\frac12 \begin{bmatrix} -34 \\ -2 \\ -10 \end{bmatrix} = \begin{bmatrix} 17 \\ 1 \\ 5 \end{bmatrix}$
				- Position and second direction:
					- $\vec{P}=\begin{bmatrix}-3\\ 4\\ 6\end{bmatrix}$
					- $\vec{d}_2=\begin{bmatrix} 1\\ 0\\ 2\end{bmatrix}$
				- Vector Equation: for $q,s\in\R$
					- $$\begin{bmatrix}x\\ y\\ z\end{bmatrix}
					  = \begin{bmatrix}-3\\ 4\\ 6\end{bmatrix}
					  + q\begin{bmatrix} 1\\ 0\\ 2\end{bmatrix}
					  + s \begin{bmatrix} 17 \\ 1 \\ 5 \end{bmatrix} $$
				- Parametric Equations:
					- $$\begin{cases}x=-3+q+17s\\ y=4+s\\ z=6+2q+5s\end{cases}$$
- ## Consolidation #.v-self-border
	- Explain the different parts of the vector equations of a plane:  $\vec{v}=\vec{P}+t\vec{u}+k\vec{w}$, $t,k\in\R$.
	- #### Practice #later
		- Decide whether each equation would make a line or a plane. Use $t,k\in\R$ for all parts.
		  logseq.order-list-type:: number
			- $\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}1\\ 2\\ 3\end{bmatrix}+t\begin{bmatrix}4\\ 5\\ 6\end{bmatrix}+k\begin{bmatrix}7\\ 8\\ 9\end{bmatrix}$
			  logseq.order-list-type:: number
			- $\left(x,y,z\right)=\left(1,2,3\right)+k\left(7,8,9\right)$
			  logseq.order-list-type:: number
			- $\begin{cases}x=3+4k\\ y=4\\ z=t\end{cases}$
			  logseq.order-list-type:: number
			- $\left(x,y,z\right)=t\left(4,5,6\right)+k\left(7,8,9\right)$
			  logseq.order-list-type:: number
			- 🔥 $\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}1\\ 0\\ -1\end{bmatrix}+t\begin{bmatrix}3\\ 0\\ 6\end{bmatrix}+k\begin{bmatrix}-1\\ 0\\ -2\end{bmatrix}$
			  logseq.order-list-type:: number
			- *Solutions.*
			  collapsed:: true
				- Plane. Two parameters or two directions.
				  logseq.order-list-type:: number
				- Line. One parameter or one direction.
				  logseq.order-list-type:: number
				- Plane. Two parameters, trickier to spot them.
				  logseq.order-list-type:: number
				- Plane. Two parameters, no position vector.
				  logseq.order-list-type:: number
				- Line. Parallel directions, so we can set $k = -2t$ and get the line $(x,y,z)=(1,0,-1)-t(3,0,6)$.
				  logseq.order-list-type:: number
		- Find the vector equation of a plane that contains the points $A(1,2,3)$, $B(-3, 4, 5)$, and $C(-4,5,2)$.
		  logseq.order-list-type:: number
		  collapsed:: true
			- *Answer.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- Answers may vary. Here is one.
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}1\\ 2\\ 3\end{bmatrix}+t\begin{bmatrix}-4\\ 2\\ 2\end{bmatrix}+k\begin{bmatrix}-5\\ 3\\ -1\end{bmatrix}$$
		- For the plane defined by $\begin{cases}x=2t \\ y=-3t+2k \\ z= -1 -3t-2k \end{cases}$
		  logseq.order-list-type:: number
			- Find the coordinates of any point on the plane.
			  logseq.order-list-type:: number
			  collapsed:: true
				- *Solution.*
				  logseq.order-list-type:: number
				  collapsed:: true
					- Easiest point is likely the position vector, which we don't need to test to see if it is in the plane. The position vector is $(0,0,-1)$.
					  logseq.order-list-type:: number
					- Checking, this would be $t=k=0$.
					  logseq.order-list-type:: number
			- What are the direction vectors for the plane?
			  logseq.order-list-type:: number
			  collapsed:: true
				- *Solution.*
				  logseq.order-list-type:: number
				  collapsed:: true
					- $\vec{d}_1=(2,-3,-3)$ and $\vec{d}_2=(0,2,-2)$.
					  logseq.order-list-type:: number
			- What point corresponds to $t=-1$ and $k=3$?
			  logseq.order-list-type:: number
			  collapsed:: true
				- *Solution.*
				  logseq.order-list-type:: number
				  collapsed:: true
					- logseq.order-list-type:: number
					  $$\begin{align*}
					  & (x,y,z) \\
					  &=(2(-1), -3(-1)+2(3), -1-3(-1)-2(3)) \\
					  &=(-1, 9,-3)
					  \end{align*}$$
			- What values of $t$ and $k$ give the point $(0,6,-7)$?
			  logseq.order-list-type:: number
			  collapsed:: true
				- *Solution.*
				  logseq.order-list-type:: number
				  collapsed:: true
					- Set $(x,y,z)=(0,6,-7)$ then:
					  logseq.order-list-type:: number
					- $x = 2t \implies 0 = 2t \implies t = 0$
					  logseq.order-list-type:: number
					- $y=-3t+2k \implies 6 = 0 +2k \implies k = 3$
					  logseq.order-list-type:: number
					- Checking Consistency:
					  logseq.order-list-type:: number
					  $z = -1-3(0)-2(3)=-1-6=-7$ Good!
		- Find the parametric equations for the plane passing through the points $A(1,1,0) and $B(4,5,-6)$ with direction vector $\vec{d}=(7,1,2)$. Be sure to define your parameters with a let statement.
		  logseq.order-list-type:: number
		  collapsed:: true
			- *Answer.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- $\begin{cases}x=1+3t+7k\\ y=1+4t+1k\\ z=-6t+2k\end{cases}$
				  logseq.order-list-type:: number
		- Explain why $(x,y,z)=(1,2,3)+t(2,5,10)+k(-4,-10,-20)$ for $t,k\in\R$ is not actually a plane.
		  logseq.order-list-type:: number
		  collapsed:: true
			- *Solution.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- The direction vectors are parallel. Notice that:
				  logseq.order-list-type:: number
				- $\begin{bmatrix}2\\ 5\\ 10\end{bmatrix}=-\frac12\begin{bmatrix}-4\\ -10\\ -20\end{bmatrix}$
				  logseq.order-list-type:: number
				- We need two non-parallel direction vectors to describe a plane.
				  logseq.order-list-type:: number
		- Find the vector equation of the plane passing through the point $(2,3,-5)$ and containing the line
		  logseq.order-list-type:: number
		  collapsed:: true
		  $$(x,y,z)=(1,6,3)+t(1,4,0)$$
		  for $t\in R$. Can you reuse $t$ in your plane equation? Why or why not?
			- *Answer.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- $\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}1\\ 6\\ 3\end{bmatrix}+t\begin{bmatrix}1\\ 4\\ 0\end{bmatrix}+k\begin{bmatrix}1\\ -3\\ -8\end{bmatrix}$
				  logseq.order-list-type:: number
		- The plane $(x,y,z) = (1,2,3)+t(1,2,5)+k(1,-1,3)$ for $t,k\in\R$ intersects the y and z axes at the points $A$ and $B$ respectively. Determine the equation of the line passing through $A$ and $B$.
		  logseq.order-list-type:: number
		  collapsed:: true
			- *Answer.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- $\begin{bmatrix}x\\ y\\ z\end{bmatrix}=\begin{bmatrix}0\\ 3\\ 0\end{bmatrix}+t\begin{bmatrix}0\\ 3\\ 2\end{bmatrix}$
				  logseq.order-list-type:: number
			- **Strategy.**
			  logseq.order-list-type:: number
			  collapsed:: true
				- What do we already know about a point on the y-axis? We know that $x=z=0$. Therefore, the point $(0,y,0)$ is on the y-axis. This can give us **one** equation in two variables, $t$ and $k$.
				  logseq.order-list-type:: number
				- To get a second equation in $t,k$ we will use the z-axis point, or $(0,0,z)$.
				  logseq.order-list-type:: number
				- We use substitution or elimination to get $t$ and $k$.
				  logseq.order-list-type:: number
				- We use $t,k$ to find the points $A$ and $B$ from the original vector equation of the plane.
				  logseq.order-list-type:: number
				- We find $\vec{AB}$ and use it as our direction vector. Then we use one of either point $A$ or $B$ as our position vector.
				  logseq.order-list-type:: number
		- Why is there no symmetric equation for any plane?
		  logseq.order-list-type:: number
		  collapsed:: true
			- *Idea.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- Having two parameters means why can no longer solve for just one of them. We could make something like a symmetric equation but, say if we solved for $t$, the new symmetric equation would still need to have $k$ input. The purpose of the symmetric equation was to eliminate all parameters.
				  logseq.order-list-type:: number