Why.
Why would they do this???
Why do they have to normalize the input and output values?
That just makes it anoying to use.
Like, you need a wrapper function for the functions to be usable.
E.g.
```python
import colorsys

# Credit for this life-saving function goes to @cory-kramer on stack overflow.
#  Source: https://stackoverflow.com/a/24852375

def hsv_to_rgb(h, s, v):
 return tuple(abs(round((i * 255))) for i in colorsys.hsv_to_rgb(h, s, v))
```
Like, why?
Why do I need this??
It would honestly be better if there wasn't a built-in colour module in python becuase then there would be a good community-maintained one.

In fact, I just saw [This stack overflow answer](https://stackoverflow.com/a/26856771) which looks like it might be faster (it needs to be, becuase I'm running this every tick), so I might use that instead.