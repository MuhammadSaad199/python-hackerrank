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
