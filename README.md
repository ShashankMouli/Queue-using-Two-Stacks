# Queue-using-Two-Stacks
n = int(input())

def queue(a):
    q = []
    
    if a[0] == 1:
        q.append(a[1])
    
    elif a[0] == 2:
        del q[0]
        
    elif a[0] == 3:
        print(q[0])
    
        
        
for i in range(n):
    a = list(map(int, input().strip().split()))
    queue(a)
