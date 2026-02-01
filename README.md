# program-to-implement-linear-search
numbers = [4,2,7,1,8,3,6]

f = 0 #flag
x = int(input(&quot;Enter the number to be found out: &quot;))
for i in range(len(numbers)):
if (x==numbers[i]):
print(&quot; Successful search, the element is found at position&quot;, i)
f = 1
break
if(f==0):
print(&quot;Oops! Search unsuccessful&quot;)
