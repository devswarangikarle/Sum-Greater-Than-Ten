# Sum-Greater-Than-Ten
Ram has three digits a,  b, and c.    Since math isn't his strongest point, he asks you to determine if you can choose any two digits to make a sum greater or equal to 10.    Output "YES" if there is such a pair, and "NO" otherwise.

def sum_greater_than_ten(a, b, c):
    if a + b >= 10 or a + c >= 10 or b + c >= 10:
        return "YES"
    else:
        return "NO"

a, b, c = map(int, input().split())

result = sum_greater_than_ten(a, b, c)
print(result)
