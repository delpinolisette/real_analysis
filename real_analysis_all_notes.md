# All Topics

Real Analysis (Part 2: Functions of several variables) Notes

goal : define all major concepts and their sub-concepts (recursive notes) !
```
.-----------------------------------------------------------------------------.
||Es| |F1 |F2 |F3 |F4 |F5 | |F6 |F7 |F8 |F9 |F10|                  C= AMIGA   |
||__| |___|___|___|___|___| |___|___|___|___|___|                             |
| _____________________________________________     ________    ___________   |
||~  |! |" |§ |$ |% |& |/ |( |) |= |? |` || |<-|   |Del|Help|  |{ |} |/ |* |  |
||`__|1_|2_|3_|4_|5_|6_|7_|8_|9_|0_|ß_|´_|\_|__|   |___|____|  |[ |]_|__|__|  |
||<-  |Q |W |E |R |T |Z |U |I |O |P |Ü |* |   ||               |7 |8 |9 |- |  |
||->__|__|__|__|__|__|__|__|__|__|__|__|+_|_  ||               |__|__|__|__|  |
||Ctr|oC|A |S |D |F |G |H |J |K |L |Ö |Ä |^ |<'|               |4 |5 |6 |+ |  |
||___|_L|__|__|__|__|__|__|__|__|__|__|__|#_|__|       __      |__|__|__|__|  |
||^    |> |Y |X |C |V |B |N |M |; |: |_ |^     |      |A |     |1 |2 |3 |E |  |
||_____|<_|__|__|__|__|__|__|__|,_|._|-_|______|    __||_|__   |__|__|__|n |  |
|   |Alt|A  |                       |A  |Alt|      |<-|| |->|  |0    |. |t |  |
|   |___|___|_______________________|___|___|      |__|V_|__|  |_____|__|e_|  |
|                                                                             |
`-----------------------------------------------------------------------------'

```


## Preliminaries:

go back and define these if I run into any issues. 

Metric Spaces
Limit in metric space
neighborhood in metric space
continuity in metric space
connectedness in metric space
completeness in metric space
compactness in metric space


vector space theory
basis of vspace
dimension of vspace
linear functional and operator
matrix

## Differentiation

### Differentiable functions of several real variables : 

we can characterize differentiability in a real function of several variables in the following ways: 

#### Linear Functional definition
according to [wolfram](https://mathworld.wolfram.com/LinearFunctional.html) (TODO check if this is the def in this course!)

A linear functional on a real vector space $V$ is a map/function $T: V \mapsto \mathbb{R}$ satisfying :

1. $T(v+w) = T(v) + T(w)$
2. $T(\alpha v) = \alpha T(v)$

(for complex vector spaces, $T$ maps into $\mathbb{C}$)


#### Definition 1 of a differentiable function of several variables :

A function $f$ in Euclidian domain $X \subset \mathbb{R}^n$ is called **differentiable** at a point $x_0$ if $\exists$ a linear functional $\alpha : \mathbb{R}^n \mapsto \mathbb{R}$ such that :

$$f(x) = f(x_0) + \alpha(x-x_0) + o(|x-x_0|)$$

(an identical way to state this is):

$$\lim_{h \to 0}\frac{f(x_0 + h) - f(x_0) -\alpha(h)}{h} = 0$$

TODO Questions : why the functional? why the limit? need motivation for this definition, ask on MSE or TA/professor. update: just found in textbook!

### Def 2 of a diff function of a single variable and a derivation

a function $f:(a,b) \mapsto \mathbb{R}$ is **differentiable** at $x_0 \in (a,b)$ if the limit :

$$f'(x_0) = \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h}$$ exists. 

This is the same as saying :

$$ \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h} - \frac{h}{h}f'(x_0)= f'(x_0) - f'(x_0) = 0$$

$$ \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0) -f'(x_0)h}{h}= 0$$

$$ \lim_{x \to x_0} \frac{f(x_0 + h) - f(x_0) -f'(x_0)h}{h}= 0$$

### Defenition 2 of a differentialble function of several variables
from marsden (clearer def)

### Derivative as a Linear Functional 

### Derivative as a linear operator

### Exercises on Derivatives:

from Marsden:

1. Compute $Df(x)$ for $f: \mathbb{R} \mapsto \mathbb{R}$ defined by $f(x) = sin(x)$. 

### Partial and Directional derivatives

### Differentiability and continuity

### second derivative as bilinear map

### symmetry of mixed partials


## Differentiation and Application

Euclidian Domains 

Smooth functions and smooth maps

Chain rule

higher derivatives as polylinear maps

taylor formula

maxima and minima

conditional extremum

## Results in Higher Dimensions

Inverse function theorems

Implicit function theorems

Jacobian matrix

## Differential Geometry Peek

(not in textbook)

Smooth submanifolds in $\mathbb{R}^n$
- list examples

## Integration and Other Topics

(not in textbook)

Integration theory for functions of several variables

Reimann integral

methods of computation 

change of variables

Fubinis theorem

differential forms

vector analysis in $\mathbb{R}^3$

## More DG

(not in textbook)

Distributions on smooth manifolds

dirac delta function 

support of a distribution

spaces of test functions - see syllabi for examples

ordinary functions as regular distributions 

operations on distributions 

## Fourier

(not in textbook)

fourier series

characters of the circle group $\mathbb{T}$

hillbert spaces

properties of fourier coefficients



## More Fourier

(not in textbook)

Fourier transform on $\mathbb{R}$

characters of $\mathbb{R}$

Schwartz space $S\mathbb(R)$

direct and inverse fourier transforms

the plancherel formula 


