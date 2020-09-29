The Power of the Pipe (%>%)
========================================================
author: Jarren Santos
date: Last updated September 26, 2020
autosize: true



Assumptions
========================================================
I assume you swim in the following pools of knowledge prior to presenting this information.

1. bleep
2. bloop
3. blap



Background
========================================================
Background answers these questions:

1. What is a pipe?  
  a. Where does it come from?  
  b. How is it used?
2. What power does it possess?  
  a. Why should I be using this and not base R?



Prior to the Pipe
========================================================
Here I show implementations of code not using the pipe (probably some tidyverse data source).

1. Base R implementation
2. Arbitrary naming of functions/objects implementation
3. Repetitive overriding of functions/objects implementation



Pipe Conceptual Model
========================================================
Prior to showing the pipe in action, I present the pipe in proof of concept.

1. Pictures of me (or something else) progressively bringing along items.
2. Grocery store reference  
  a. Pick up grocery store items one by one, sacrificing a trip each time  
  b. Pick up all the grocery store items all in one trip
3. Super Mario (?!?!?)



Present to the Pipe
========================================================
Here I show implementations of code using the pipe (probably some tidyverse data source).

1. Look at the readability!
2. Look at the efficiency (i.e., no arbitrary naming, no repetitive override)!
3. Let's make sure to do another example after this!



With great (pipe) power comes great (pipe) responsibility
========================================================
You are not always going to want to use the pipe.

1. Maybe you shouldn't do your entire grocery shopping trip all at once.  
  a. If I buy all my ingredients at once, then I am going to have to figure out how to use all my items and minimize food waste.  
  b. If I split my grocery shopping into x number of trips, then it may allow me to accomplish something else (i.e., having fresh stock of produce).
2. Prior to saving Princess Peach, Super Mario doesn't have to defeat all the enemies, collect all the coins and stars, and complete the stage all at once.  
  a. Speed run  
  b. Collecting resources (i.e., stocking up on green mushrooms/lives to prepare for boss battles)  

Consider when it is best to use the pipe (along with its pipe alternatives!).



Why should I use the Pipe again?
========================================================
Here I show implementations of code using the pipe (probably some tidyverse data source).

1. Look at the readability!
2. Look at the efficiency (i.e., no arbitrary naming, no repetitive override)!



Slide With Code
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](slides-figure/unnamed-chunk-2-1.png)

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-3](slides-figure/unnamed-chunk-3-1.png)



References
========================================================
**{magrittr} Pipe (%>%)**

Garrett Grolemund and Hadley Wickham. 2020. Chapter 18: Pipes. *R for Data Science*. https://r4ds.had.co.nz/pipes.html.

Bradley Boehmke. 2016. Simplify Your Code with %>%. University of Cincinnati Business Analytics R Programming Guide. https://uc-r.github.io/pipe.

Stefan Milton Bache and Hadley Wickham. 2014. magrittr: A Forward-Pipe Operator for R. R package version 1.5. https://CRAN.R-project.org/package=magrittr.

{magrittr} %>% Documentation. https://magrittr.tidyverse.org/reference/pipe.html.



References (cont.)
========================================================
**Pipe (%>%) Alternatives**

Kun Ren. 2016. pipeR: Multi-Paradigm Pipeline Implementation. R package version 0.6.1.3. https://CRAN.R-project.org/package=pipeR.

Kun Ren. pipeR Tutorial. https://renkun-ken.github.io/pipeR-tutorial/index.html

Antoine Fabri. 2020. nakedpipe: Pipe Into a Sequence of Calls Without Repeating the Pipe Symbol. https://github.com/moodymudskipper/nakedpipe



References (cont.)
========================================================
**Critiques of the Pipe (%>%)**

Kun Ren. 2014. Differences between magrittr and pipeR. https://renkun.me/2014/08/08/difference-between-magrittr-and-piper/

John Mount and Nina Zumel. 2018. *Dot-Pipe: an S3 Extensible Pipe for R*. The R Journal, 2018(10:2). https://cran.r-project.org/web/packages/wrapr/vignettes/wrapr_pipe.pdf

