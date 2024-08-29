#Write a program that calculates the mean of three input numbers.
#Write a program that calculates the standard deviation of three input numbers. 
import math
x1 = 2
x2 = 7
x3 = 9

mean = (x1 + x2 + x3) / 3
#print("The mean of these three numbers is", {mean})  

squaredDev1 = (x1 - mean)**2                   
squaredDev2 = (x2 - mean)**2
squaredDev3 = (x3 - mean)**2

squaredDevMean = (squaredDev1 + squaredDev2 + squaredDev3) / 3

StdDev = math.sqrt(squaredDevMean)

print("The standard deviation of the three numbers is", {StdDev})
#round(StdDev)          
