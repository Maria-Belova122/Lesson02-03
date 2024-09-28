# ЗАДАНИЕ ПО ТЕМЕ "Стиль кода часть II. Цикл While"

my_list = [42, 69, 322, 13, 0, 99, -5, 9, 8, 7, -6, 5]
print(my_list)
# Кол-во элементов в списке my_list
length = len(my_list)
index = 0

while index < length:
    number = my_list[index]
    index = index + 1
    if number > 0:
        print(number)
    elif number == 0:
        continue
    else:
        break

print('Вывод закончен')