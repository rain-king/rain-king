# `$ whoami`
I'm an undergrad student with orientation towards Applied Mathematics and Computation. I've done most of the Math major coursework, some Computer Science and Data Analytics.

## Explaining some of my repos
My code in some of my projects is ad-hoc due the time restraints of having homework and lectures,
but I do not waste the opportunity to add a new concept I wanted to try in basic Python or C++/Rust.
I will try better implementations for HPC when the time permits.

### Linear Programming
For example these 2024 repos of linear programming simply have Simplex methods, but not the more interesting interior-point methods:
- [Simplex in Rust](https://github.com/rain-king/simplex_rs)
- [Simplex in Python](https://github.com/rain-king/simplex_py)
- [Dual Simplex in Rust](https://github.com/rain-king/dual_simplex)
- [Big-M Simplex Method in Rust](https://github.com/rain-king/big-m_simplex)

These are simply because I was taking Operations Research and doing these calculations by hand and I wanted a way to check on my work. I have plans to refactor these into a single Rust library project with an idiomatic way to select the method to use, like traits. I was using a crate for arrays back then, I wonder if it's up to date today, if I should write my own matrix math library, or use a different crate.

Since I got an interest for optimization methods in general now, I might write a few more general convex programming methods, though I might be more inclined to use a different language.

### Runge-Kutta 4 and Differential Equations of Higher Order
In 2020 I wrote [a Fortran program](https://github.com/rain-king/RK4-Hermite) to numerically test some (proven) hypothesis of Hermite polynomials regarding the Hermite differential equation
($\ddot{x}(t) - 2\dot{x}(t) t + \lambda x(t) = 0$). I hadn't taken either mathematical or numerical analysis, so it was challenging to get what was asked of me done, but it got done. I even wrote some code in Python to get a few graphs of what was happening.
Through the years the estimation aspect of mathematics has become one of my favorite topics, be it with noisy data or truncating a series to finite steps.

## Why I like Mathematics
I like having the formal definitions burned into my mind, they give you a "target" to identify when a complex problem arises.
If not for the theorems and applications, the language (and thus thinking) you get from it alone is worth it. For example I have these notes that are simply the basics of the respective theory:
- [Linear Algebra Notes in Spanish](https://github.com/rain-king/notas_algebra_lineal).
- [Introduction to Measure Theory Notes](https://github.com/rain-king/mathanalysis).
- 
The advanced parts I'd be interesting in going through only as much as another topic also uses them, as they are not as ubiquitous as the basic theory. I might write such notes in the future.

## How I read Math books
My way of going through books nowadays is more "exploratory" than sitting strictly through the classical "definition-theorem-proof" loop. While I used to sit with a notebook to truly learn the language in the past. Nowadays I grab theoretical books on applications like optimization and skim to see the major concepts. Now I only sit with a notebook when the language is ubiquitous in current papers I'm more interested in getting a basic grasp. 

