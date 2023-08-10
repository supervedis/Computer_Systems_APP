Write C expressions, in terms of variable <code>x</code> , for the following
values. Your code should work for any word size w ≥ 8. For
reference, we show the result of evaluating the expressions for
<code>x = 0x87654321</code> , with w = 32.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A. The least significant byte of x , with all other bits set to 0.[ <code>0x00000021</code> ] = <code>  x & 0xFF</code>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B. All but the least significant byte of x complemented, with
the least significant byte left unchanged [<code>0x789ABC21</code>]=<code>x ^ ~0xFF</code>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C. The least significant byte set to all ones, and all other
bytes of x left unchanged. [<code>0x876543FF</code>] = <code>x|0xFF</code>