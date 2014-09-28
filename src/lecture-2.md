#Area

##Outline

* Areas we know
* Approximations
* Summation notation
* Actual area

##Areas we know

Remember a long time ago when you learned how to compute areas? We are going to do that again, only we are going to step it up a notch. Let's start with the basics. What is the area of a rectangle with lenght $l$ and height $h$? Or how about a triangle with base $b$ and height $h$? These should be pretty easy. It turns out just knowing these two can help us find the area of a lot of different shapes. For example, consider a polygon. We can calculate the area by first dividing up the polygon into triangles and calculating the area of each triangle since we know how to do that.

###Picture

????????

?????????????

picture a rectangle, triangle, and polygon triangulated

?????????????????

??????????????

????????

##Approximations

With the niave methods above we can find the area of a lot of shapes, but we are still missing a lot. For example, what about a shape with curved sides? We will find these by approximating the shape with simpler shapes. To start off, consider the following picture showing the area under the graph of the function $f(x) = x^2 + 1$ on the interval $[0,2]$. We don't have the tools to find the area, but we can get pretty close by just drawing rectangles as shown in the figure.

????????

?????????????

picture area under the curve plus approximations with rectangles

?????????????????

??????????????

????????

###Left vs Right

There are a few ways to draw the approximating rectangles above. The two main methods we will use are "left endpoints" and "right endpoints". The side is based on which endpoint of the rectangle lies on the graph of the function.


????????

?????????????

picture area under the curve plus approximations with rectangles

?????????????????

??????????????

????????

###Example

Lets approximate the area under the curve $x^2+1$ on the interval $[0,2]$ using four rectangles with right endpoints. The area then is about the area of the rectangles. For each rectangle we calculuate the area in the usual way: width times height. We will always use equally spaced rectangles so the width will be the same for each of them. Since the interval has length $2 - 0 = 2$ and there are $4$ rectangles, this means each has width $\frac{2}{4} = \frac{1}{2}$. So the approximation for the area is $$A \approx (1/2)\cdot((1/2)^2+1) + (2/2)\cdot((2/2)^2+1) + (3/2)\cdot((3/2)^2+1) + (2)\cdot((2)^2+1) = 35/2 = 17.5$$.

Doing the same thing but with left end points we have $$A \approx (0)\cdot((0)^2+1) + (1/2)\cdot((1/2)^2+1) + (2/2)\cdot((2/2)^2+1) + (3/2)\cdot((3/2)^2+1) = 15/2 = 7.5$$.

????????????

?????????????????

another picture

?????

?????????

###Note

Eagle eyed readers will notice the difference in the results, one was an over estimate while the other an under. This is also clear just from looking at the pictures. See if you can figure out when left endpoints will overestimate and when right end points will overestimate.

###An arbitrary number of rectangles

Now approximate area of the curve $f(x) = x^2+1$, on the interval $[0,2]$, only using $n$ rectangles instead of $4$. The idea should be the same. Now the width of each rectangle will be $\frac{2}{n}$. The right end point of the first rectangle will be at $2/n$. The right end point of the second rectangle will be at $2\cdot 2/n$. The rest are similar. That means the height of the first rectangle will be $f(1\cdot 2/n)$ and the height of the second will b e $f(2\cdot 2/n)$. Putting this all together the approximate area is $$ A \approx 1\cdot\frac{2}{n}f(1\cdot 2/n) + 2\cdot\frac{2}{n}f((2\cdot 2/n) + \cdots + n\cdot\frac{2}{n}f(n\codt 2/n) $$

????????

??????????

?????

???????????????

??????????

##Summation Notation

You can sort of see how if we want to approximate the area under a curve, it's best to use a lot of rectangles. Only that means we have to add up a lot of different calculations which are all very similar. It would be a rediculous pain to write down a sum of that many terms. So it's helpful to have a little bit of notation to help keep track of everything.

* Let $[a,b]$ be the interval that we are looking at.
* Let $\Delta x$ be the width of the rectangles.
* Let $x_i = i\Delta x + a$. This is the right end point of the $i$th rectangle.
* Let $x_i^\ast$ represent any point in $[x_{i-1},x_i]$.

From these we can see that

* x_0 = a.
* $[x_{i-1},x_i]$ is the base of the $i$th rectangle, so $\Delta x = x_i - x_{i-1}$.
* The area of the $i$th rectangle using right endpoints is $f(x_i)\Delta x$.
* The area of the $i$th rectangle using left endpoings is $f(x_{i-1})\Delta x$.

???????????????????????????????????

???????????????????????????

????????????????????

???????????????