Armed with the function inplace_swap from **Problem 2.10**
you decide to write code that will reverse the elements of an array by swapping elements from opposite ends of the array,
working toward the middle.
You arrive at the following function:
<code>  
1 void reverse_array(int a[], int cnt) {  
2     int first, last;  
3     for (first = 0, last = cnt-1; first <= last;first++,last–)  
6         inplace_swap(&a[first], &a[last]);  
7 }  
</code>  
A. For an array of odd length cnt = 2k + 1 , what are the
values of variables first and last in the final iteration of
function reverse_array?  
 <code>first = last = Math.floor(cnt) = k </code> This applies the ^ operation to the same element resulting to 0.  

 B. Why does this call to function inplace_swap set the
array element to 0?  
<code>first</code> and <code>last</code> refer to the same value resulting to <code>0</code> when the bitwise ^ is applied to the same element in the array.  

C. What simple modification to the code for reverse_array
would eliminate this problem?  
Change <code>first <= last;</code> in the for header    
to <code>first < last;</code>  
