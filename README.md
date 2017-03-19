# Breakpoint

## Description
An elegant sassy media query solution with minimal boilerplate using the Scss @content directive.

## Example
You can implement it like this:
```
.my-class{
  display: block;

  @include breakpoint(medium) {
    display: inline-block;
  }

  @include breakpoint(large) {
    display: inline;
  }
}
```
That's it!