# How to profile your code in IPython
## Line profiling
### Using the built-in [prun magic](http://ipython.readthedocs.io/en/stable/interactive/magics.html#magic-prun)

```
%prun foo(1000)
```

### Using the [line-profiler](https://github.com/rkern/line_profiler) extension
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
