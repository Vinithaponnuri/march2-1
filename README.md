PROGRAM:
A=[]
m=int(input('enter no of rows: '))
n=int(input('enter no of columns: '))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    A.append(row)
print(A)
B=[]
m=int(input('enter no of rows: '))
n=int(input('enter no of columns: '))
for i in range(m):
    row=[]
    for j in range(n):
        k=int(input())
        row.append(k)
    B.append(row)
print(B)
result=[[0,0],[0,0]]
for i in range(m):
    for j in range(n):
        result[i][j]=[A[i][j]-B[i][j]]
print('resultant matrix is: ',end=' ')
for i in range(m):
    for j in range(n):
        print(result[i][j],end=' ')
    print()
OUTPUT:
enter no of rows: 2
enter no of columns: 2
                     9
                     8
                     7
                     6
                     [[9, 8], [7, 6]]
enter no of rows: 2
enter no of columns: 2
                     1
                     2
                     3
                     4
                    [[1, 2], [3, 4]]
resultant matrix is:  [8] [6] 
                      [4] [2] 
