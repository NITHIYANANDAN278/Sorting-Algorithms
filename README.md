# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
''' Developed by: NITHIYANANDAN N
Reg no.: 212222230099'''
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)




```
ii)	#Insertion Sort
```
''' Developed by NITHIYANANDAN N
Reg no.: 212222230099'''
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)






```

## Output:
![image](https://github.com/NITHIYANANDAN278/Sorting-Algorithms/assets/121784636/f8857a2b-7bfa-4bc1-8926-ddf3661639e5)
![image](https://github.com/NITHIYANANDAN278/Sorting-Algorithms/assets/121784636/067478b1-12f9-4539-b593-108e1c01d245)




## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
