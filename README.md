#乘积尾零
num = [5650,4542,3554]   
s = 1
for i in num :
  s = s*i
cnt = 0
while s%10 ==0:
  s //= 10
  cnt +=1
print(cnt)
#相乘
for i in range(1,1000000008):
  if (i * 2021)%1000000007==999999999:
    print(i)
    break
#平方和
sum = 0
for i in range(1,2020):
  s = str(i)
  if '2' in s or '0' in s or '1' in s or '9' in s:
    sum += i*i
    print（sum）
