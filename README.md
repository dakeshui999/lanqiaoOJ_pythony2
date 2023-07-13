乘积尾零
num = [5650,4542,3554]   
s = 1
for i in num :
  s = s*i
cnt = 0
while s%10 ==0:
  s //= 10
  cnt +=1
print(cnt)

