# RStudioProject
#1.1
f <- function(x){
     result <- x^3+x^2-6
     return(result)
}
example : f(1) = -4

#1.2
g <- function(a,b){
result <- a*b*(b-a)
return(result)
}
example : g(1,2) = 2

#1.3
h <- function(m,n){
result <- (sqrt(m)/n)+m-2*n
return(result)
}
example : h(2,3) = -3.528595

#2.1
f <- function(a,b){
result <- (a+b)%*%a%*%b
return(result)
}
a <- matrix(c(1,2,3,4), 2, 2, TRUE)
b <- matrix(c(1,2,3,4), 2, 2, TRUE)
example f(a,b) = 74  108
                  162  236

#2.2
h <- function(m,n){
result <- abs(m)%*%n - m%*%n
return(result)
}
m <- matrix(c(1,2,3,4), 2, 2, TRUE)
n <- matrix(c(1,2,3,4), 2, 2, TRUE)
example : h(m,n) = 0  0
                   0  0
            
#2.3
g <- function (x){
result <- solve(x)%*%x-2*%x
return(result)
}

#Constant Function
f <− function (x) {
     #suppose c=2
     fx <− 2
     return (fx)
     }
     input <− 0: 1 0

#Linear Function
f <- function (x){
   #a=3 and #b=5
   fx <− 3∗x+ 5
   return (fx)} 
   input <− −1:10
   plot (input, sapply (input,f) ,
   type="l",
   xlab = "x",
   ylab = "f(x)")
  
 #Quadric Function
 f <- function (x){
   fx <− 1∗x^2+5*x+12
   return (fx)}
   input <− 0:10
   plot (input, sapply (input,f) ,
   type="l",
   xlab = "x",
   ylab = "f(x)")
   
   #Polinomial Function
   f <- function (x){
   fx <− 1*x^3-4*x^2+1/2*x+5
   return (fx)}
   input <− seq(-10,10,0.5)
   plot (input, sapply (input,f) ,
   type="l",
   xlab = "x",
   ylab = "f(x)")
   
   #Rational Function
   f <- function (x){
   fx <− 5/x
   return (fx)}
   input <− seq(2,11,0.5)
   plot (input, sapply (input,f) ,
   type="l",
   xlab = "x",
   ylab = "f(x)")
