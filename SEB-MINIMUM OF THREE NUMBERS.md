# Experiment No: 5 – SEB- find the largest among three Integer Numbers .

## AIM  
To write a Python program to find the largest among three Integer Numbers .

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223020031
# Name-Yazhini N
a=int(input())
b=int(input())
c=int(input())
if (a>b>c):
    print("The largest of the three a=",a,"b=",b,"c=",c,"is",a)
else:
    print("The largest of the three a=",a,"b=",b,"c=",c,"is",c)
```

## OUTPUT

## RESULT
Hence the largest among three Integer Numbers is founded
