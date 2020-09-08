#R-Programming-Assignment-2
#Peer-graded Assignment: Programming Assignment 2: Lexical Scoping
#Example usage
#copy and paste the below into the R studio console once the cachematrix.R file is opened in the R Studio.
	m <- matrix(c(1, 2, 3, 4), nrow=2, byrow=TRUE)
	m2 <- makeCacheMatrix(m)
	cacheSolve(m2)
	cacheSolve(m2)
	m2 <- makeCacheMatrix(m)
	cacheSolve(m2)
	cacheSolve(m2)

Below is the output...........from the console......
> #Example usage
> m <- matrix(c(1, 2, 3, 4), nrow=2, byrow=TRUE)
> m2 <- makeCacheMatrix(m)
> cacheSolve(m2)
     [,1] [,2]
[1,] -2.0  1.0
[2,]  1.5 -0.5
> cacheSolve(m2)
getting inversed matrix
     [,1] [,2]
[1,] -2.0  1.0
[2,]  1.5 -0.5
> m2 <- makeCacheMatrix(m)
> cacheSolve(m2)
     [,1] [,2]
[1,] -2.0  1.0
[2,]  1.5 -0.5
> cacheSolve(m2)
getting inversed matrix
     [,1] [,2]
[1,] -2.0  1.0
[2,]  1.5 -0.5


	
