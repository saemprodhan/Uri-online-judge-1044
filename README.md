X = list(map(int,input().split()))
A,B = X
if (B%A==0) or (A%B==0):
    print("Sao Multiplos")
else:
    print("Nao sao Multiplos")

