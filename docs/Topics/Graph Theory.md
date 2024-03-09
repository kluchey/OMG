# Optional:  Graph Theory

## Graphs - no, not *those* graphs

Tags #optional #supplementary #enrichment #coding

## Introductory Remarks

!!! Definition
	A *graph* is a set of vertices and a set of edges formed between vertices. **Analogy:**  Think of these objects like networks or connections between locations. These are **not** the same as graphs of equations / functions and are **not** bar graphs, pie graphs, etc.

!!! Example
	Given three vertices $\{A, B, C\}$, the following edges $\{AB, BC, AC\}$ connect our vertices to form a graph. Figure 1 is a visual which simplifies the math speak and is what you should really be visualizing when reading the sets. This is one of many topics in math where it is better to visualize the idea rather than be bogged down in the notation used to describe it in text.

```mermaid
graph LR
	title[Figure 1]
	title --- A
	style title stroke:#FFF
	linkStyle 0 stroke:#FFF,stroke-width:0;
	
	A((A)) --- B((B))
	B --- C((C))
	C --- A
```

Graphs are a topic primarily seen in coding but are used frequently to summarize in a math class. Importantly, students need to be taught to use graphs, such as [**flowcharts**](Flowcharts.md), and it cannot be assumed the knowledge of graphs is intuitive. Here is the most common example I have seen flowcharting used to summarize without explanation:  while discussing how to decide which trig formula to use in Grade 11 courses for right or [oblique](Trigonometry#Beyond Pythagorean Theorem) triangles.

```mermaid
graph TD
	A[Is the triangle <br> right angled?] -->|Yes| B[Do you have an angle <br> or need to find an angle?]
	B -->|No| F[Use the <br> Pythagorean <br> Theorem]
	B -->|Yes| G[Use <br> Soh Cah Toa]
	G --> Decision[You have any two items <br> in one of the following <br> lists and need the <br> remaining item:]
	Decision --> H[an angle, <br> its opposite side, <br> the hypotenuse]
	Decision --> I[an angle, <br> its adjacent side, <br> the hypotenuse]
	Decision --> J[an angle, <br> its opposite side, <br> its adjacent side]
	H --> Soh[Soh]
	I --> Cah[Cah]
	J --> Toa[Toa]
	
	
	A -->|No| C[Do you have one pair <br> of opposite side & angle <br> and one other side or angle?]
	C -->|Yes| D[Use the <br> Law of Sines]
	C -->|No| Last[Do you have all <br> three sides SSS or <br> a side sandwich SAS?]
	Last -->|Yes| E[Use the <br> Law of Cosines]
	Last -->|No| UhOh[Unsolvable <br> Triangle]



```

