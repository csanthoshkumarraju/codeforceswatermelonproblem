# codeforceswatermelonproblem
---------------codeforces watermelon problem even or odd--------------------------------------
w = int(input())
if w > 2 and w <= 100:
    if w % 2 == 0:
        print('yes')
    else:
        print('no')
elif w == 2:
    print('no')
elif w == 1:
print('no')
