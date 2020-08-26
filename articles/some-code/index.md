---
title: Some Code
date: 2020-08-26
excerpt: Check code display and syntax highlighting
cover: cover.jpg
tags:
  - tutorial
  - how-to
---

The goal of this short article is to show that **The Post** knows how to display code properly with syntax highlighting.  

So here is a JavaScript example:
```javascript
export function doThing(someArg) {
  if (someArg === 42) {
    return false
  } else {
    console.log('This is a nice message.')
    return true
  }
}
```

Here is a Python example:
```python
def do_thing(some_arg):
  if some_arg == 42:
    return False
  else:
    print("This is a nicee message")
    return True
```

Let's hope that sort of proves the point, but check the [original markdown](https://raw.githubusercontent.com/thepostio/thepostio-content/master/articles/some-code/index.md) to make sure you know how to write your own code blocks!