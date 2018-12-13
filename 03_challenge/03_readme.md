- What part of the error message gave a clue:
```
TypeError: 'str' object cannot be interpreted as an integer
```

- How I set about solving the issue (e.g.: I Googled): I went to line 16 to see if it was a string
instead of a variable. Saw the `max_num` variable was set in line 28 where it was indeed a string.
So I took `16` out of quotes so it was an integar and changed it to `99`.

- Summary of what was learned: Read the error then work backwards through the traceback until you
find the cause. Also, even if the thing in quotes is a number it is still treated a a string.

