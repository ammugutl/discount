# discount
t=int(input())
while t>0:
  a,b,c,d=map(int,input().split())
  s=a-c
  m=b-d
  if s>m:
    print("Second")
  elif(s<m):
    print("First")
  else:
    print("Any")
  t=t-1
