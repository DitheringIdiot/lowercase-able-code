# Lowercase-able svg code

## Close path command [9.3.4](https://www.w3.org/TR/SVG2/paths.html#PathDataClosePathCommand)

The close path command can be written as either `z` or `Z`.

```svg
<path d="M 1 1 L 2 0 Z" />
```

```svg
<path d="M 1 1 L 2 0 z`" />
```

## First command in a path *Citation needed*

Uppercase path commands are followed by absolute coordinates (coordinates relative to the point `0,0`)
Lowercase path commands are followed by relative coordiantes (coordinates relative to the current position of the path)

Since paths always begin at point `0,0` the first command in any path can always be lowercased.

```svg
<path d="M 1 1 L 2 0 Z" />
```

```svg
<path d="m 1 1 L 2 0 Z`" />
```


