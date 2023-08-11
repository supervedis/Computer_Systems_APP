Suppose that x and y have byte values 0x66 and 0x39 ,
respectively. Fill in the following table indicating the byte values
of the different C expressions:  

|Expression |Value |Expression   |Value |
|:---       |:---  |:---         |:---  |
|x & y      |0x20  |x && y       |0x01  |
|x \| y     |0x7F  |x \|\| y     |0x01  |
|~x \| ~y   |0xDF  |!x \|\| !y   |0x00  |
|x & !y     |0x00  |x && ~y      |0x01  |
