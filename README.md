## Labs for Finance and Markets for Engineers and Scientists

This repository holds the lab notebooks for the [Finance and Markets for Engineers and Scientists course at Cornell](https://varnerlab.github.io/CHEME-5660-Markets-Mayhem-Book/infrastructure.html).

### Overview
In today’s society, finance holds a vital position in both the progress of technology and the lives of individuals. Despite this, traditional engineering or physical science curriculums seldom teach financial forecasting, modeling, and decision-making. Many engineers and scientists pursue careers in finance and consulting, adding to the need for financial knowledge. This course aims to bridge these gaps by introducing engineers and scientists to financial systems, markets, and quantitative finance tools and approaches. We will model, analyze, and optimize financial systems and decision-making processes using engineering, statistics, data science, and machine learning tools.

### Topics
* [Lab 1b: HelloWorld. Installation of course packages and tools](CHEME-5660-Lab-1b-HelloWorld.ipynb)

### Installing Julia
This course uses the [Julia](https://julialang.org) programming language. You can find the installation instructions for Julia [here](https://julialang.org/downloads/).

### Installing Jupyter
The labs are provided as [Jupyter notebooks](https://jupyter.org); you can find the installation instruction for installing Jupyter [here](https://jupyter.org/install).  For the labs, we use [Julia](https://julialang.org) as our Jupyter notebook kernel; this requires the installation of the [IJulia](https://github.com/JuliaLang/IJulia.jl) package. 

To install [IJulia](https://github.com/JuliaLang/IJulia.jl) from the [Julia REPL](https://docs.julialang.org/en/v1/stdlib/REPL/) press the `]` key to enter [pkg mode](https://pkgdocs.julialang.org/v1/repl/) and the issue the command:

```
add IJulia
```

This will install the [IJulia](https://github.com/JuliaLang/IJulia.jl) package. If you already have Python/Jupyter installed on your machine, this process will also install a
[kernel specification](https://jupyter-client.readthedocs.io/en/latest/kernels.html#kernelspecs)
that tells [Jupyter](https://jupyter.org) how to launch [Julia](https://julialang.org) so we can use it in the notebook. You can then launch the [Jupyter notebook](https://jupyter.org) server the usual
way by running `jupyter notebook` in the terminal.

If you do NOT already have a python installation on your machine, we recommmed that you install [Anaconda](https://www.anaconda.com/products/individual) on your machine.  This will install a python distribution on your machine that includes [Jupyter](https://jupyter.org).  Once you have installed [Anaconda](https://www.anaconda.com/products/individual), you can install the [IJulia](https://github.com/JuliaLang/IJulia.jl) package.

### Disclaimer and Risks
This content is offered solely for training and informational purposes. No offer or solicitation to buy or sell securities or derivative products, or any investment or trading advice or strategy,  is made, given, or endorsed by the teaching team. 

Trading involves risk. Carefully review your financial situation before investing in securities, futures contracts, options, or commodity interests. Past performance, whether actual or indicated by historical tests of strategies, is no guarantee of future performance or success. Trading is generally inappropriate for someone with limited resources, investment or trading experience, or a low-risk tolerance.  Only risk capital that is not required for living expenses.

You are fully responsible for any investment or trading decisions you make. Such decisions should be based solely on your evaluation of your financial circumstances, investment or trading objectives, risk tolerance, and liquidity needs.
