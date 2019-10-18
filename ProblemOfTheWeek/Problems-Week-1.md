### Problems from Part 1 & 2

#### 1 Writing to a file
Follow the following procedure to create a file with random alpbates.
 -  Using `import string` and defining *alphabet* = `string.ascii_lowercase`, create a function that take as input *alphabet* and  return a `dict` variable call *abc*. *abc* should contain numbers in the range [1, 26] as the keys and the corresponding alphabet as values.
 
 - Using the function above, create a text file that contain alphabets a-z in lower cases.  The file should contain exactly 10 lines, each having 13 characters that are picked at random. One way to achieve this is by using library (random)
 
 An example of lines in the file could be
 -- alowuthrueifj
 -- pqowutiehdtxh
 -- amslotrywrweq



#### 2. Searching for occurance of characters
a.  Define a function which will take a string 'name' as an argument. Search through the file if the alphabets in the word are present in the file, if yes return true else return the alphabets that are missing from the file when compared to the word.

b. Define another function to reads the odd lines in the file, return a histogram of the frequency of each of the letters. 

c.  Select the vowels and plot the histogram and title it `Random Vowels Histogram`



#### 3 Generator functions
Write a generator function named `oddGen` that takes two inputs (a, b) and generate odd numbers in that range with b > a



#### 4 Replacing numpy array values

Replace all odd numbers in arr with -1 without changing arr

Input: a = np.array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])

Desired Output: 

out = array([ 0, -1,  2, -1,  4, -1,  6, -1,  8, -1])

a = array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])


