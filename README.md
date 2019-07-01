# TestJive.jl

|  **Build Status**               |
|:-------------------------------:|
|  [![][travis-img]][travis-url]  |


```
~/.julia/dev/TestJive/test$ julia runtests.jl
1/2 test1.jl
    Pass 1  (0.08 seconds)
2/2 test2.jl
    Pass 1  (0.01 seconds)
✅  All 2 tests have been completed.  (0.39 seconds)

~/.julia/dev/TestJive/test$ julia runtests.jl test1
1/1 test1.jl
    Pass 1  (0.07 seconds)
✅  All 1 test has been completed.  (0.34 seconds)

~/.julia/dev/TestJive/test$ julia runtests.jl test2
1/1 test2.jl
    Pass 1  (0.08 seconds)
✅  All 1 test has been completed.  (0.37 seconds)
```


[travis-img]: https://api.travis-ci.org/wookay/TestJive.jl.svg?branch=master
[travis-url]: https://travis-ci.org/wookay/TestJive.jl
