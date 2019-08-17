my_list = [1, 3, 5, 7, 9]


def benary(list, item):
    low = 0  # хранится номер ячейки в массиве наименьший
    high = len(list) - 1  # аналогично
    while low <= high:
        mid = (low + high)//2 # поиск среднее, запоминает ячейку
        quess = list[mid]
        if quess == item:
            return mid
        elif quess < item:
            low = mid + 1  # сдвиг по среднему в право
        else:
            high = mid - 1  # сдвиг по среднему в лево
    return None
print(benary(my_list, 3))

