a = int(input())
b = int(input())
c = int(input())
if a == b == c:
    print('Равносторонний')
if a == b or b == c or a == c:
    print('Равнобедренный')
else:
    print('Разносторонний')
