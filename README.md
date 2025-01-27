This repository demonstrates a subtle bug related to the iteration order of Lua's `pairs` function when used with nested tables.  The `pairs` iterator does not guarantee any specific order, which can lead to unexpected results if your code relies on a particular order. The example shows a recursive function that processes nested tables. The output may vary depending on Lua's implementation and version due to the unpredictable iteration order of `pairs`.