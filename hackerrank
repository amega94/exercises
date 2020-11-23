#Stopped in the middle

def intersection_update (set_A, set_B):
    set_A.intersection_update(set_B)
    
def update (set_A, set_B):
    set_A.update (set_B)

def symmetric_difference_update (set_A, set_B):
    set_A.symmetric_difference_update(set_B)

def difference_update (set_A, set_B):
    set_A.difference_update (set_B)
    
size_A = int(input())
set_A = set (map(int, input().split()))

num_operations = int(input().split()[0])

for _ in range(num_operations):
    command = input().split()[0]
    print("Command: ", command, len(command))
    set_X = set (map(int, input().split()))
    print("Debugging 1", set_X)
    if command == "intersection_update":
        intersection_update(set_A, set_X)
    elif command == "update":
        print("Debugging 2", set_X)
        update(set_A, set_X)
    elif command == "symmetric_difference_update":
        symmetric_difference_update(set_A, set_X)
    elif command == " difference_update operation":
        difference_update (set_A, set_X)
print(set_A)
print(sum(set_A))
