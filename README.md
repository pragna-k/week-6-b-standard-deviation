# week-6-b-standard-deviation
x<-scan()
n=length(x)
mean=0
p=0
k=0
for(i in 1:n){
  p=p+x[i]
}
mean=p/n
sprintf("Mean is %f",mean)
for(i in 1:n){
  k=k+((x[i]-mean)^2)
}
  v=k/n
  sd=sqrt(v)
  sprintf("Standard deviation is %f",sd)
  sprintf("variance is: %f",v)
  
  
  
  OUTPUT:
  > x<-scan()
1: 1
2: 5
3: 9
4: 7
5: 3
6: 6
7: 4
8: 8
9: 2
10: 10
11: 
Read 10 items
> n=length(x)
> mean=0
> p=0
> k=0
> for(i in 1:n){
+   p=p+x[i]
+ }
> mean=p/n
> sprint("Mean is %f",mean)
Error in sprint("Mean is %f", mean) : could not find function "sprint"
> sprintf("Mean is %f",mean)
[1] "Mean is 5.500000"
> for(i in 1:n){
+   k=k+((x[i]-mean)^2)
+ }
>   v=k/n
>   sd=sqrt(v)
>   sprintf("Standard deviation is %f",sd)
[1] "Standard deviation is 2.872281"
>   sprintf("variance is: %f",v)
[1] "variance is: 8.250000"
> 
