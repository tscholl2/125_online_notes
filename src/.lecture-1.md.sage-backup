#Antiderivatives

##Outline

* Introduction
* Definitions
* Examples
* Applications
* Geometry

##Introduction

Remember back in differential calculus you learned all about derivatives and how to find them, for example $\frac{d}{dx}\left(x^3\right) = 3x^2$. In this course we will learn how to go backwards. So instead of having $f$ and finding $f'$, we will have $f'$ and try to recover $f$.

###Definition

A function $F$ is an *antiderivative* of a function $f$ if $F'(x) = f(x)$.

###Example

* $x^3$ is an antiderivative of $3x^2$.
* $x^2 + 3x + 1$ is an antiderivative of $2x + 3$.

###Example

It is important to realize that this really is backwards. In differential calculus you would say

* $3x^2$ is the derivative of $x^3$.
* $2x + 3$ is the derivative of $x^2 + 3x + 1$.

The eagle-eyed reader will notice another difference in the two examples. One uses the word "an" and the other uses "the". So the next thing to do is to ask why.

###Question

Why do we not say "the antiderivative"?

###Answer

The best answer to this question is another question. Is there another antiderivative of $2x + 3$ besides the one listed above? Yes! There is actually a lot of them. Another is $x^3 + 3x$. See how many you can write down. Is there a pattern?

So far we have found that everything of the form $x^2 + 3x + C$ (here $C$ is just some number like $1$ or $0$) is an antiderivative of $2x + 3$. So $x^2 + 3x + 17$ and $x^2 + 3x + \pi$ are both antiderivatives of $2x + 3$. A natural question at this point is: "Are there any others?". We can answer this with the following theorem:

###Theorem

No. That is, every antiderivative of $2x+3$ is of the form $x^2 + 3x + C$. In general, given a function $f$ and *any* antiderivative $F$, then *all* antiderivatives are of the form $F + C$ for some constant $C$.

Why should you think this is true? The actual answer requires a small amount of work, but the idea is to subtract any two antiderivatives. Say $F$ and $G$ are both antiderivatives of $f$, that is $F' = G' = f$. Then $(F - G)' = F' - G' = f - f = 0$. From here one can show that $F - G$ must be constant so $F = G + C$.

###Example

* The antiderivatives of $\sin(x)$ are all of the form $-\cos(x) + C$.
* The antiderivatives of $x^4$ are all of the form $\frac{x^5}{5} + C$.

###Warning

Don't forget the "$+C$".

###Practice

Find the general antiderivative of the following functions (see solutions at the bottom to check):

| Function        | Antiderivative |
|-----------------|----------------|
| $x^n$           | -              |
| $e^x$           | -              |
| $\cos x$        | -              |
| $\sin x$        | -              |
| $\sec^2 x$      | -              |
| $\sec x \tan x$ | -              |
| $\csc^2 x$      | -              |
| $x^{-1}$        | -              |


###Toughy

What are the antiderivatives of $\frac{x^2 + \sqrt{x}}{x}$?

Note we can rewrite this as $x + x^{-1/2}$ and then check that all antiderivatives are of the form $\frac{1}{2}x^2 + 2x^{1/2} + C$.

###A note on the +C

From above we know that there are many antiderivatives for a function. We represent the "general form" of an antiderivative by writing a "$+C$" on the end. But suppose we want a specific antiderivative. We do this by declaring intial conditions. For example, find an antiderivative $F$ of the function $f(x) = 2x$ such that $F(1) = 3$. Then we solve for the general antideriavtive, namely $F(x) = x^2 + C$ and use the initial conditions to find the correct value of $C$. Namely $3 = F(1) = 1^2 + C$ which solves to $C = 2$. So the specific antiderivative we need is $F(x) = x^2 + 2$.


##Applications

Recall in physics that the acceleration $a(t)$ is the derivative of velocity $v(t)$ which is the derivative of position $s(t)$. So with our new words we would say velocity is the antiderivative of acceleration and position is antiderivative of velocity.

###Example

Suppose a car is going somewhere, we don't care because we are mathematicians. But we do care that the car's velocity is given by $v(t) = 2t^3$.

##Geometry

You can reverse everything you learned in 124. For example if $F'(a) > 0$ then $F$ is increasing at $a$. Or reading backwards, if $F$, the antiderivative of $F'$, is increasing at $a$, then $F'(a)>0$.


###Picture

TO-DO?????????

???????

?????????????

???????????????????????

?????

?????????????????

##Solutions


| Function        | Antiderivative             |
|-----------------|----------------------------|
| $x^n$           | $\frac{1}{n+1}x^{n+1} + C$ |
| $e^x$           | $e^x + C$                  |
| $\cos x$        | $\sin x + C$               |
| $\sin x$        | $-\cos x + C$              |
| $\sec^2 x$      | $\tan x + C$               |
| $\sec x \tan x$ | $\sec x + C$               |
| $\csc^2 x$      | $-\cot x + C$              |
| $x^{-1}$        | $\ln |x| + C$              |