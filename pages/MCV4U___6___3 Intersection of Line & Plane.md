- #+BEGIN_CAUTION
  In this lesson, we imagine how a plane and a line can interact in three dimensions.
  #+END_CAUTION
- ## Warm Up
	- Grab a pencil and a piece of paper. How many *different* ways can this paper interact with the pencil? Which object is like a line and which is like a plane in this situation? Summarize all of the ways to interact with sketches.
- ## Action:  Examples #.v-self-border
	- Find the intersection (if any) for each of the following systems in $\R^3$, $k\in \R$ in each.
	  logseq.order-list-type:: number
		- $\begin{cases}\left(x,y,z\right)=\left(4,6,-2\right)+k\left(-1,2,1\right)\\ 2x-y+6z+14=0\end{cases}$
		  logseq.order-list-type:: number
			- *Solution.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- Substitute the parametric equations into the scalar plane equation:
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{align*}
				  2(4-k)-(6+2k)+6(-2+k)+14 &\stackrel{?}{=} 0 \\
				  8-2k-6-2k-12+6k+14 &= \\
				  4+2k &= \\
				  2k &= -4 \\
				  k &= \frac{-4}{2} \\
				  k &= -2
				  \end{align*}$$
				- Our point of intersection is defined by the parameter $k=-2$ so we will now calculate it:
				  logseq.order-list-type:: number
					- logseq.order-list-type:: number
					  $$\begin{align*}
					  (x,y,z) &= (4,6,-2)-2(-1,2,1) \\
					  &= (4+2,6-4,-2-2) \\
					  &= (6,2,-4)
					  \end{align*}$$
				- Therefore, we have one point of intersection, it is $(6,2,-4)$. We can verify this point by checking if it is also on the plane:
				  logseq.order-list-type:: number
					- logseq.order-list-type:: number
					  $$\begin{align*}
					  & 2(6)-(2)+6(-4)+14 \\
					  &= 12-2-24+14 \\
					  &= 0
					  \end{align*}$$
					- It is! So this is the PoI.
					  logseq.order-list-type:: number
		- $\begin{cases}x=5+k\\ y=4+2k\\ z=7+2k\\ 2x+3y-4z+7=0\end{cases}$
		  logseq.order-list-type:: number
			- *Solution.*
			  logseq.order-list-type:: number
				- Substitute the parametric equations into the scalar plane equation:
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{align*}
				  2(5+k)+3(4+2k)-4(7+2k)+7 &\stackrel{?}{=}0 \\
				  10+2k+12+6k-28-8k+7 &= \\
				  3+0k &= \\
				  3 &= 0
				  \end{align*}$$
				- We have reached a contradiction. This means we cannot substitute the line into the plane or else we will always get a contradiction, and so the line must be parallel to the plane.
				  logseq.order-list-type:: number
				- We can verify if the Line and Plane are parallel by
				  logseq.order-list-type:: number
		- $\begin{cases}\left(x,y,z\right)=\left(2,14,1\right)+k\left(-1,-1,1\right)\\ 3x-y+2z+6=0\end{cases}$
		  logseq.order-list-type:: number
			- *Solution.*
			  logseq.order-list-type:: number
			  collapsed:: true
				- Substitute the parametric equations into the scalar plane equation:
				  logseq.order-list-type:: number
				- logseq.order-list-type:: number
				  $$\begin{align*}
				  2(4-k)-(6+2k)+6(-2+k)+14 &=0 \\
				  8-2k-6-2k-12+6k+14 &= \\
				  4+2k &= \\
				  2k &= -4 \\
				  k &= \frac{-4}{2} \\
				  k &= -2
				  \end{align*}$$
				- Our point of intersection is defined by the parameter $k=-2$ so we will now calculate it:
				  logseq.order-list-type:: number
					- logseq.order-list-type:: number
					  $$\begin{align*}
					  (x,y,z) &= (4,6,-2)-2(-1,2,1) \\
					  &= (4+2,6-4,-2-2) \\
					  &= (6,2,-4)
					  \end{align*}$$
				- Therefore, we have one point of intersection, it is $(6,2,-4)$. We can verify this point by checking if it is also on the plane:
				  logseq.order-list-type:: number
					- logseq.order-list-type:: number
					  $$\begin{align*}
					  & 2(6)-(2)+6(-4)+14 \\
					  &= 12-2-24+14 \\
					  &= 0
					  \end{align*}$$
					- It is! So this is the PoI.
					  logseq.order-list-type:: number
- ## Consolidation
	- For this consolidation, review the examples you solved in the action. We will let $L$ represent a Line and $P$ represent a Plane.
	  logseq.order-list-type:: number
		- If $L$ and $P$ meet at one point of intersection, what do we expect to have found at the end of our algebraic solution?
		  logseq.order-list-type:: number
		- If $L$ and $P$ do not intersect, what do we expect to have found at the end of our algebraic solution?
		  logseq.order-list-type:: number
		- If $L\subset P$ ($L$ is contained by $P$), what do we expect to have found at the end of our algebraic solution?
		  logseq.order-list-type:: number
	- Find the intersection of each of the following:
	  logseq.order-list-type:: number
		- $\begin{cases}x=-2+k\\ y=1-k\\ z=2+3k\\ x+4y+z-4=0\end{cases}$
		  logseq.order-list-type:: number
		- $\begin{cases}\left(x,y,z\right)=\left(-1,3,4\right)+k\left(6,1,-2\right)\\ x+2y-z+29=0\end{cases}$
		  logseq.order-list-type:: number
		- $\begin{cases}\left(x,y,z\right)=\left(1,5,6\right)+k\left(1,-2,-2\right)\\ 2x-3y+4z+11=0\end{cases}$
		  logseq.order-list-type:: number
		- $\begin{cases}\frac{x-1}{4}=-y-2=z-3\\ 2x+7y+z+15=0\end{cases}$
		  logseq.order-list-type:: number
		- $\begin{cases}\left(x,y,z\right)=\left(-1,1,0\right)+k\left(-1,2,2\right)\\ 2x-2y+3z-1=0\end{cases}$
		  logseq.order-list-type:: number
	- *Answers:*
	  collapsed:: true
		- 2.a) the line lies on the plane b) (-19,0,10) c) the line is parallel to the plane d) (-11,1,0) e) The line and plane are parallel