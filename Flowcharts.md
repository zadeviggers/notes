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
```
graph TD;
	A{A}-->B;
	A{A}-->B;
	A{A}-->B;
	C[Are there any lone pairs of electrons?]-->|No| E;
	C-->|Yes| D;
	D(Polar.);
	E("Non-polar (probably, I think there are some edge cases though.)");
```