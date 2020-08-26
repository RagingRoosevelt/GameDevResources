# Godot Resources

## Utility Functions & Classes [[Util.gd](Util.gd)]

Save the file at the root level of your project and import into any script using the statement 
```godot 
const Util = preload('res://Util.gd')
```

### `Util.array_str(Array)->String`

Accepts an array and returns a string representation of the array in the format of `"['val1', 'val2', 'val3', ..., 'valN']"`.

### `Util.join(Array, String=',')->String`

Concatenates an array of objects formatted to stings with each element joined with the second argument (defaults to a comma).
 
