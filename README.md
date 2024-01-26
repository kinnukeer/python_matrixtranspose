# python_matrixtranspose
x=[[0,0],[0,0],[0,0]];
for i in range(0,3):
  for j in range(0,2):
    value=int(input("enter x matrix: "))
    x[i][j]=value
  print("\n x matrix is \n")
  for r in x:
    print(r)
  result=[[0,0,0],[0,0,0]]
for i in range(len(x)):
  for j in range(len(x[0])):
    result[j][i]=x[i][j]
print("\n transpose of matrix: ")
for r in result:
  print(r)
