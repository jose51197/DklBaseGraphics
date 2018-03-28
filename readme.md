*Base Graphics for Diököl* is a implementation of R Base Graphics library using the Diököl environment.

![](DklBaseGraphics.jpg)

Examples of base graphics include:

-Waterfall chart: 

Inputs:

function waterfall(x,y,maximum, step,scale,values,data,colors,space)

x: x axis where to put it.

y: y axis where to put it.

maximum: Max value of the list.

step: how many steps to reach the maximum.(draws them)

scale: not used. as diokol has a native scale.

values: numbers for each column.

data: provides info on what each column represents.

colors: pattern for coloring the bars.

space: general variable to alter the space between the drawn chart.


![](WaterfallGraph.png)

*Clicked behavior:

![](WaterfallGraphClicked.png)

-Bar chart:

Inputs:

function bars(x,y,step,scale,values,data,colors,w,otherValues)

x: x axis where to put it.

y: y axis where to put it.

step: how many steps to reach the maximum.(draws them)

scale: not used. as diokol has a native scale.

values: values to be represented on the left

data: the numbers for each bar created.

colors: pattern for coloring the bar.

w: how wide is the bar going to be.

otherValues: Values to be represented in the bar separation. 

![](BarGraph1.png)

*Clicked behavior:

![](BarGraphClicked.png)

[Examples and Contributions](http://github.com/arce/DklBaseGraphics/wiki)