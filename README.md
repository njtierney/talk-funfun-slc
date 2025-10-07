# Practical Functions: Practically Magic

# Abstract

I think the highest value skillset in statistical programming is knowing how to write good functions. Functions are often taught as a tool to avoid repetition using the mnemonic DRY: Don't Repeat Yourself. Whilst DRY is both true and real, I think functions are at their best when they encapsulate expression and are easy to reason with. That is, DRY is sufficient, but not necessary. Writing good functions is more than esoteric aesthetics. We need to be able to reason with our code in statistics. We often don't have the capacity to write tests to show our code is "correct". Instead, we need to rely on our ability to reason with, trust, and verify that the code works as it should. I believe writing good functions that encapsulate expressions and are able to be reasoned with are how we can ensure our code, and therefore our methods, and our analyses, work as they should. In this talk I will discuss some practical ideas on writing a good function, how to identify bad ones, and how to move between the two states. 

# Slide available [here](https://njtierney.github.io/talk-funfun-slc/#/title-slide)

# Take home messages 

**Good** functions

1.  Manage **complexity**
2.  Explain and express **ideas**
3.  Can be **individually reasoned** with
4.  Take **iteration**

**Teaching** functions

-   Emphasise using functions to **express ideas**
    -   Avoiding repetion is a symptom of needing a function
-   Demonstrate **process**
    -   Demos & writing
-   Try and use practical functions, not only **toy** ones
-   Teach **debugging** alongside functions

My **challenge** to you

-   Start **sprinkling** functions into daily use
-   use `browser()` or other debugging tools
-   Read other people's code - peer review!
-   Question me - does this make sense?


# Thanks

-   Miles McBain
-   Nick Golding
-   Saras Windecker
-   August Hao
-   Chitra Saraswati
-   Hadley Wickham
-   Jenny Bryan
-   Joe Cheng
-   Roger Peng

# Resources

-   [**You have to be able to reason about it**](https://www.youtube.com/watch?v=J8qbRYa4430)
-   [**Many Models**](https://www.youtube.com/watch?v=rz3_FDVt9eg)
-   [**The design of everyday functions**](https://www.youtube.com/watch?v=Qne86lxjgtg)
-   [**Our colour of magic**](https://www.youtube.com/watch?v=ywK4qs5dJsg)
-   [**Code Smells and Feels**](https://www.youtube.com/watch?v=7oyiPBjLAWY)
-   [**From tapply to Tidyverse**](https://www.youtube.com/watch?v=5033jBHFiHE&t=1s)
-   [**Advanced R: Functions**](https://r4ds.had.co.nz/functions.html)
-   [**Tidy Design Principles**](https://design.tidyverse.org/)
-   [**Lexical Scope and Statistical Computing**](https://www.stat.auckland.ac.nz/~ihaka/downloads/lexical.pdf)
-   [**stat545 chapter on functions**](https://stat545.com/functions-part1.html)
-   [**Up and Down the Ladder of Abstraction**](https://worrydream.com/LadderOfAbstraction/)


# Colophon

  - Slides made using [quarto](https://github.com/quarto-dev/quarto)
  
Eventually, this theme will add these features in:

  - Colours taken + modified from [lorikeet theme from
    ochRe](https://github.com/ropenscilabs/ochRe)
  - Header font is **Josefin Sans**
  - Body text font is **Montserrat**
  - Code font is **Fira Mono**


# Bio

Dr. Nicholas (Nick) Tierney is a statistician, data scientist, and research software engineer with a PhD in Statistics and a Bachelor (Honours) in Psychological Science. He recently transitioned to private consulting, offering services in data analytics, modelling, code review, R package development, teaching, and mentoring.

Previously (2021-2025), Nick worked with [Prof. Nick Golding](https://www.thekids.org.au/contact-us/our-people/g/nick-golding/) at [The Kids Research Institute Australia](https://www.thekids.org.au/), maintaining the [greta R package](https://greta-stats.org/) for statistical modelling, and developing software and supporting the [Infectious Disease Ecology and Modelling team](https://www.thekids.org.au/our-research/brain-and-behaviour/child-health-analytics-research-program/infectious-disease-ecology-and-modelling/) as a [Research Software Engineer](https://researchsoftware.org/). Previously, he was a Research Fellow and Lecturer in Business Analytics at Monash University (2017-2020), collaborating with [Professor Dianne Cook](https://www.dicook.org/).

Nick is a passionate advocate for open-source software, having developed numerous R packages that improve data analysis workflows. His notable packages include [geotarget](https://ropensci.github.io/geotargets/) (geospatial pipelines) [visdat](https://docs.ropensci.org/visdat/) (pre exploratory data visualization), [naniar](https://naniar.njtierney.com/) (missing data analysis), [brolgar](https://brolgar.njtierney.com/) (longitudinal data exploration), 
[maxcovr](http://maxcovr.njtierney.com/) (optimisation), and [mmcc](http://mmcc.njtierney.com/) (MCMC diagnostics). Nick has also been actively writing about R and R related projects since 2013 at his blog, ["credibly curious"](https://www.njtierney.com/).

An outdoor enthusiast, Nick hiked the entire Pacific Crest Trail in 2023, completing a 5-month journey from Mexico to Canada. His personal blog at [njt.micro.blog](https://njt.micro.blog/) documents this adventure.
