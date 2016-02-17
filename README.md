# responsive-layout-mixin
A simple responsive SCSS layout mixin

# Usage
The mixin comes set up as a fluid 16 column grid with 2 breakpoints, so on large screens, a 16 column layout is used, on medium screens an 8 column grid is used and on small screens a 1 column grid is used.

The number of columns on the largest size is defined by the $columns variable, the medium size uses half this number and the smallest screens always use a 1 column layout.

Use the .span-* class to define how many columns an element should span on large screens.

The .push-* class adds a left margin equal to the given number of columns on large screens.

The .pull-* class adds a negative left margin equal to the given number of columns on large screens.

The .post-* class adds a right margin equal to the given number of columns on large screens.

The .post-pull-* class adds a negative right margin equal to the given number of columns on large screens.