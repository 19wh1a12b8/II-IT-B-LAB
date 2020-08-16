BINARY  SEARCH WITH

#AIM::To find the position of key element using Binaarysearch with recursion
Description::: Binary search is a searching algorthim for finding an element’s position in a sorted
array.in this element is always searched in the middle of a portion of an array .

##Step by Step procedure:
1.Elements:a[0]=3,a[1]=12,a[2]=24,a[3]=33,a[4]=36,a[5]=54,a[6]=60,a[7]=61,a[8]=92,a[9]=98
2.key elements= 12,92,33
3. 1 st key element = 12
4.Iteration 1:
Low = 0,High = 9,Mid = 4
a[4] = 36
12 &lt; a[4]
Iteration 2:
Low = 0,High = 4,Mid = 2
       a[4] = 36
       12 < a[4]
 Iteration 2:
       Low = 0,High = 4,Mid = 2
       a[2] = 29
       12< a[2]
 Iteration 3:
       Low = 0,High = 2,Mid = 1
       a[1] = 12
       12 = a[1]
Key element found at position ‘1’
