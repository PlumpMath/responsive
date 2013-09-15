Simple responsive framework
==========

just add _grid.scss to your sass folder and put this line in your main sass stylesheet:

```
@import 'grid';
```

and you're good to go! Currently, any element that has `fit-` somewhere in the name will be considered a column, and any element with `box-` will be considered a column wrapper.
You can customize breakpoints within _grid.scss by changing the variables `$huge`, `$big` or `$medium`.
