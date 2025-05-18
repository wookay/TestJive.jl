# TestJive.jl

|  **Build Status**                |
|:---------------------------------|
|  [![][actions-img]][actions-url] |

```
~/.julia/dev/TestJive/test$ julia runtests.jl
1/2 test1.jl
    Pass: 1  (compile: 0.06, recompile: 0.01, elapsed: 0.06 seconds)
2/2 test2.jl
    Pass: 1  (compile: 0.00, elapsed: 0.00 seconds)
✅  All 2 tests have been completed.  (compile: 0.06, recompile: 0.01, elapsed: 0.06 seconds)

~/.julia/dev/TestJive/test$ julia runtests.jl test2 test1
1/2 test2.jl
    Pass: 1  (compile: 0.06, recompile: 0.01, elapsed: 0.06 seconds)
2/2 test1.jl
    Pass: 1  (compile: 0.00, elapsed: 0.00 seconds)
✅  All 2 tests have been completed.  (compile: 0.06, recompile: 0.01, elapsed: 0.07 seconds)

~/.julia/dev/TestJive/test$ julia runtests.jl test1
1/1 test1.jl
    Pass: 1  (compile: 0.05, recompile: 0.01, elapsed: 0.06 seconds)
✅  All 1 test has been completed.  (compile: 0.05, recompile: 0.01, elapsed: 0.06 seconds)
```


[actions-img]: https://github.com/wookay/TestJive.jl/workflows/CI/badge.svg
[actions-url]: https://github.com/wookay/TestJive.jl/actions
