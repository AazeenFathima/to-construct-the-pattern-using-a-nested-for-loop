# to-construct-the-pattern-using-a-nested-for-loop

n = 5

# Upper half
for i in range(n):
    for j in range(i):
        print('* ', end="")
    print('')

# Lower half
for i in range(n, 0, -1):
    for j in range(i):
        print('* ', end="")
    print('')

"""
Sample Output:

*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*
"""
