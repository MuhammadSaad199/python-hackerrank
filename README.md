# python-hackerrank

1) square loops 
if __name__ == '__main__':
    n = int(input())
    for i in range(0,n):
        print(i*i)


2) if else condition
if __name__ == '__main__':
    n = int(input().strip())

if (n % 2 != 0) or (n>=6 and n<=20):
    print("Weird")
else:
    print("Not Weird")


3) leap year
   def is_leap(year):
    leap = False
    
    if(year%4==0 and year%100!=0) or (year%400==0):
       leap = True
    else: 
        leap = False
    
    return leap

year = int(input())
