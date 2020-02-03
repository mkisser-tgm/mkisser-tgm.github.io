# mkisser-tgm.github.io - 2020
- [My github](http://github.com/mkisser-tgm)

# Previous Years
- [2019](years/2019.md)

# Books I've read
- Elantris
- Warbreaker

# Ideas I stumble onto

## Data Oriented design - Mike Acton

CppCon 2014: Mike Acton "Data-Oriented Design and C++"

<https://www.youtube.com/watch?v=rX0ItVEVjHc>

Is a design principle for code that simplifies code by reducing states and optimizing for compiler and memory/cache/cpu performance. E.g. Why fetch only 1 bit for a boolean when you have 63 bits left in that cpu cycle for the memory lane. 

[Additional Resources](http://www.dataorienteddesign.com/site.php)

### Cache Misses

<https://www.extremetech.com/extreme/188776-how-l1-and-l2-cpu-caches-work-and-why-theyre-an-essential-part-of-modern-chips>

[PDF alternative](articles/2020/l1l2cache.pdf)

Taking from Ram takes a lot of time and so you need the cpu to to something useful in the meantime, instead of waiting 200 cycles on 1 bit for a bool.

