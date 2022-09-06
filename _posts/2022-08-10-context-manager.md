---
layout: post
title: Context manager
---

# Unpacking Argument Lists

## Description

The reverse situation occurs when the arguments are already in a list or tuple but need to be unpacked for a function call requiring separate positional arguments. For instance, the built-in `range()` function expects separate start and stop arguments. If they are not available separately, write the function call with the `*`-operator to unpack the arguments out of a list or tuple:

## Code

```python
>>> args = [3, 6]
>>> list(range(*args))
```

## Output

![Image](/assets/images/unpack-arg/output.jpg)
