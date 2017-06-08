A lovely girl Lavendy is considering purchasing some land in Louisiana to build her
house on. In the process of investigating the land, she learned that the state of
Louisiana is actually shrinking by **50** square miles each year, due to erosion
caused by the Mississippi River. Since Lavendy is hoping to live in this house the
rest of her life, she needs to know if her land is going to be lost to erosion. 

After doing more research, Lavendy has learned that the land that is being lost forms a
semicircle. This semicircle is part of a circle centered at (0,0), with the line that
bisects the circle being the X axis. Locations below the X axis are in the water.
The semicircle has an area of 0 at the beginning of year 1. (Semicircle illustrated 
in the Figure.)

![Figure 1](http://acm.zju.edu.cn/onlinejudge/showImage.do?name=0000%2F1049%2F1049-2.gif)

Please write a function: erosion_year(x, y)

This function should take a coordinate of a land and returns how many years there will
be before the land is erosed. X and Y should be float numbers, and the return value
should be an integer.

With this function, please write a program and takes a number N, where N is the number
of coordinates that the user is going to supply next. Then for each coordindate, tell
the user the number of years.

Example:

```shell
Please enter the number of coordinates N: 2
Please input X for coordinate 1: 1.0
Please input Y for coordinate 1: 1.0
This property will begin eroding in year 1.
Please input X for coordinate 2: 25.0
Please input Y for coordinate 2: 0
This property will begin eroding in year 20.
```

Note: *Based on http://acm.zju.edu.cn/onlinejudge/showProblem.do?problemCode=1049*
