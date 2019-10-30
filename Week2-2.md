# Boundry test
### The number is odd or even?
```java
//test x=0 to determine the statement
if(x < 0){  //boundry shift
    return false;

} else{ 
    return true; //computational fault 
}
```
### Test case (natural mistake)
1. x =0  
figure out whether it is (x<=0 or x<0)
**on point = 0**  
2. x = 1  
figure out the statement (x<=1)
**off point = others**
3. x = -1  
the larger number in the boundry (may only find one possible mistake, eg:x==0->false)

-----------|(x=0)----------------->

### greater or smaller
1. x=y  
x=y=1
2. x>y  
x=1, y=0
3. x<y  
x=0,y=1

```java
if (x>=y){
    return true;
}else {
    return false;
}
```
one figure -> shift the line  
* two-dimensional boundry  
pick two cases on the line, two far from each other
* three-dimensional boundry  
pick three cases on points  
