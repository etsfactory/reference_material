# How to use the profiler
## Line profiling
In a command line:

```
pip install line-profiler
```

In the IPython console.

First, load the `line_profiler` extension:

```
%load_ext line_profiler
```

Then, line profile your function `foo` (for example):

```
%lprun -f foo foo(1000)
```
