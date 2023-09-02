# Shopping_list
# You can add items you wanna buy .
data=[]
while True :
    name = input("Enter the Items : ")
    data.append(name)
    choice = input("Enter another Item ??(y/n) : ")
    if choice.casefold() == 'n':
        break
for elements in data:
    print(elements )
