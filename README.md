# AIC-assignment-162610
#Assignment of AIC PIAIC
#question 1
#Import the numpy package under the name np
import numpy as np
print("Malik Abdul Salam "+"CNIC number 6110147159205"+" ROll Number PIAIC 162610")
print("AIC Quarter 2")
print("Assignment # 1")
#question 2
#Create a null vector of size 10
print("creating a null vector of size 10")
x = np.zeros(10)
print(x)
#question 3
#Create a vector with values ranging from 10 to 49
print("Crating an array of size1 0-49")
v = np.arange(10,50)
print(v)
#question 4
#Find the shape of previous array in question 3
print("Shape of array of questio No. 3 is given below")
print(v.shape)
#question 5
#Print the type of the previous array in question 3
print("Printing the type of the previous array in question 3")
print(v.dtype)
#question 6
#Print the numpy version and the configuration
print("Printing the numpy version and the configuration")
print(np.__version__)
print("configuration of numpy is given below")
print(np.show_config())
print("Configuration of Numpy is ending here")
#question 7
#Print the dimension of the array in question 3
print("Printing the dimension of the array in question 3")
print(v.ndim)
#question 8
#Create a boolean array with all the True values
print("Creating a boolean array with all the True values")
bln_array = np.array([1, True, 1], dtype=bool)
print(bln_array)
#question 9
#Create a two dimensional array
print("Creating a two dimensional array")
two_d_array = np.array([[2, 4, 6], [6, 8, 10]], np.int32)
print(two_d_array)
#question 10
#Create a three dimensional array
print("Create a three dimensional array")
a_3d_array = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])
print(a_3d_array)
#question 11
#Reverse a vector (first element becomes last)
print("Reverse a vector (first element becomes last)")
orignal_array = np.arange(0, 21)
print("Original array:")
print(orignal_array)
print("Reverse array:")
orignal_array = orignal_array[::-1]
print(orignal_array)
#question 12
#Create a null vector of size 10 but the fifth value which is 1
print("Create a null vector of size 10 but the fifth value which is 1")
test_array=np.zeros(10)
test_array[4]=1
print(test_array)
#question 13
#Create a 3x3 identity matrix
print("Create a 3x3 identity matrix")
array_2D=np.identity(3)
print(array_2D)
#question 14
#Convert the data type of the given array from int to float
print("Convert the data type of the given array from int to float")
array_14= np.array([[12, 13], [14, 15], [16, 17]])
print(array_14.dtype)
array_14=array_14.astype(float)
print(array_14)
print(array_14.dtype)
#question 15
#Multiply arr1 with arr2..............................
#print("Multiply arr1 with arr2")
#arr1 = np.array([[1., 2., 3.],

 #           [4., 5., 6.]])

#arr2 = np.array([[0., 4., 1.],

 #          [7., 2., 12.]])
#result_of_q15 = np.dot(arr1,arr2)
#print(result_of_q15)
#question 16
#Make an array by comparing both the arrays......... i ma using greater than (>) comparitive opperator
print("Make an array by comparing both the arrays......... i ma using greater than (>)comparitive opperator")
arr1 = np.array([[1., 2., 3.],

            [4., 5., 6.]])

arr2 = np.array([[0., 4., 1.],

            [7., 2., 12.]])
print(np.greater(arr1, arr2))
#question 17
#Extract all odd numbers from arr with values(0-9)
print("Extract all odd numbers from arr with values(0-9)")
an_array=np.arange(1,10,2)
print(an_array)
#question 18
#Replace all odd numbers to -1 from previous array
print("Replace all odd numbers to -1 from previous array")
an_array = np.where(an_array%2==1, -1, an_array)
print(an_array)
#question 19
#Replace the values of indexes 5,6,7 and 8 to 12
print("Replace the values of indexes 5,6,7 and 8 to 12")
arr = np.arange(10)
arr[5:9]= 12
print(arr)
#question 20
#Create a 2d array with 1 on the border and 0 inside
print("Create a 2d array with 1 on the border and 0 inside")
arr_20 = np.ones((5,5))
arr_20[1:-1,1:-1] = 0
print(arr_20)
#question 21
#Replace the value 5 to 12
print("Replace the value 5 to 12........means we have to replace the valu 5 which is present in matrix with 12")
arr2d = np.array([[1, 2, 3],

            [4, 5, 6],

            [7, 8, 9]])
arr2d[arr2d==5]= 12
print(arr2d)
#question 22
#Convert all the values of 1st array to 64
print("Convert all the values of 1st array to 64...........................")
#question 22
#Make a 2-Dimensional array with values 0-9 and slice out the first 1st 1-D array from it
print("Make a 2-Dimensional array with values 0-9 and slice out the first 1st 1-D array from it")
arr_22 = np.random.randint(10, size=(3, 4))
print("original array was")
print(arr_22)
print("its firs row is sliced and given below")
print(arr_22[0, :])
#question 23
#Make a 2-Dimensional array with values 0-9 and slice out the 2nd value from 2nd 1-D array from it
print("Make a 2-Dimensional array with values 0-9 and slice out the 2nd value from 2nd 1-D array from it")
print(arr_22[1, 1])
#question 24
#Make a 2-Dimensional array with values 0-9 and slice out the third column but only the first two rows
print("Make a 2-Dimensional array with values 0-9 and slice out the third column but only the first two rows.........")
print(arr_22[2:2, :])
#question 25
#Create a 10x10 array with random values and find the minimum and maximum values
print("Create a 10x10 array with random values and find the minimum and maximum values")
arr_25 = np.random.randint(10, size=(10, 10))
print(arr_25)
print("maximum value in above matrix is given below")
print(np.max(arr_25))
print("mainimum value in avbove matrix is given below")
print(np.min(arr_25))
#question 26
#Find the common items between a and b
print("Find the common items between a and b")
a = np.array([1,2,3,2,3,4,3,4,5,6])
b = np.array([7,2,10,2,7,4,9,4,9,8])
print("common values between these two arrays are given below")
print(np.intersect1d(a, b))
#question 27
#Find the positions where elements of a and b match
print("Find the positions where elements of a and b match........................")
print(np.where(np.intersect1d(a, b)))
#question 28
#Find all the values from array data where the values from array names are not equal to Will
print("Find all the values from array data where the values from array names are not equal to Will...............question ki smj ni aai")
names = np.array(['Bob', 'Joe', 'Will', 'Bob', 'Will', 'Joe', 'Joe'])
data = np.random.randn(7, 4)
print(data)
#question 29
#Find all the values from array data where the values from array names are not equal to Will and Joe
print("Find all the values from array data where the values from array names are not equal to Will and Joe...........question ki smj ni aai")
#question 30
#Create a 2D array of shape 5x3 to contain decimal numbers between 1 and 15.
print("Create a 2D array of shape 5x3 to contain decimal numbers between 1 and 15. ")
arr_30 = np.random.rand(15, size=(5, 3))
print(arr_30)
#question 31
#Create an array of shape (2, 2, 4) with decimal numbers between 1 to 16.
print("Create an array of shape (2, 2, 4) with decimal numbers between 1 to 16. ")
