Each of these colors can be represented as a bit vector of
length 3, and we can apply Boolean operations to them.

A. The complement of a color is formed by turning off the
lights that are on and turning on the lights that are off.
What would be the complement of each of the eight
colors listed below?

|R   |G   |B   |Color  |~R  |~G  |~B  |Color(~)|
|:---|:---|:---|:---   |:---|:---|:---|:---    |
|0   |0   |0   |Black  |1   |1   |1   |Black   |
|0   |0   |1   |Blue   |1   |1   |0   |Yellow  |
|0   |1   |0   |Green  |1   |0   |1   |Magenta |
|0   |1   |1   |Cyan   |1   |0   |0   |Red     |
|1   |0   |0   |Red    |0   |1   |1   |Cyan    |
|1   |0   |1   |Magenta|0   |1   |0   |Green   |
|1   |1   |0   |Yellow |0   |0   |1   |Blue    |
|1   |1   |1   |white  |0   |0   |0   |Black   |

B. Describe the effect of applying Boolean operations on
the following colors:  
Blue | Green = Cyan  
Yellow & Cyan = Green  
Red ^ Magenta = Blue  
