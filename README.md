bash-live-split
===============

A small little live-split clone for bash

Usage
-----

Run with any number of arguments for split names - press `enter` to move to the
next one.  Process will exit when all arguments are exhausted.

```
$ ./bash-live-split introduction feature{1..5}
>>>> introduction         0m 17.641ms
>>>> feature1             1m 6.678ms
>>>> feature2             3m 3.181ms
>>>> feature3             5m 28.995ms
>>>> feature4             5m 29.967ms
>>>> feature5             5m 30.145ms
```

License
-------

MIT License
