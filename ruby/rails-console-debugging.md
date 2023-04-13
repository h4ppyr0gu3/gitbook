---
description: Debugging in Ruby on Rails
---

# Rails Console Debugging

if you don't know where a method is defined but you know the class you can type&#x20;

```
ClassName.method(:method_name).source
or 
ClassName.method(:method_name).source_location
```

obviously substituting the class name and method name to make it make sense
