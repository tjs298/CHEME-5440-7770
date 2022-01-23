# CHEME-5440-7770-Cornell-Spring-2022
Repository for CHEME 5440 and 7770 lectures, examples, problem sets, codes, etc. 

This repository holds lecture notes and example problems discussed in lecture. The problems are structured in [Pluto](https://github.com/fonsp/Pluto.jl) notebooks and use the [Julia](https://julialang.org) programming language. 

### Installing Julia and Pluto
[Julia](https://julialang.org) is open source, free and runs on all major operating systems and platforms. To install 
[Julia](https://julialang.org) and [Pluto](https://github.com/fonsp/Pluto.jl) please check out the tutorial for 
[MIT 18.S191/6.S083/22.S092 course from Fall 2020](https://computationalthinking.mit.edu/Fall20/installation/).

1. [Install Julia (we are using v1.7.x, newer versions of Julia should also work)](https://julialang.org/downloads/)
1. [Install Pluto.jl](https://github.com/fonsp/Pluto.jl#installation)
1. Clone this repo:
    ```bash
    git clone https://github.com/varnerlab/CHEME-5440-7770-Cornell-Spring-2022.git
    ```
1. From the Julia REPL (`julia`), run Pluto (a web browser window will pop-up):
    ```julia
    julia> using Pluto
    julia> Pluto.run()
    ```
    _Or you can simply type the following in a terminal:_
    ```bash
    julia -E "using Pluto; Pluto.run()"
    ```
1. From Pluto, open one of the `.jl` lecture notebook files located in the `CHEME-5440-7770-Cornell-Spring-2022/lectures` directory—enjoy!