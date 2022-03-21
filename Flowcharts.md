# Flowcharts
For flowchats, I'll use square boxes for descions and rounded boxes for everything else.
```mermaid
graph TD;
	A(Start here)-->B;
	B[Make a choice]-->|Option 1| C;
	B-->|Option 2| C;
	C(Death comes to us all);
```
Why? Becuase the diamon shapes (which apprently are meant to be used for descions) are really big and make it hard to see the whole flowchar on one screen. 
```mermaid
graph TD;
	A{Text goes here Text goes here}-->B;
	B{Text goes here Text goes here}-->C;
	C{Text goes here Text goes here};
```