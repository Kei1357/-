
tickets = int(input("Введите количество билетов: "))
total = 0
for i in range(tickets):
    age = int(input("Введите возраст посетителей: "))
    if 18 < age < 25:
        total += 990
    elif age > 25:
        total += 1390
if tickets > 3:
    total = total - (total * 10 // 100)
print("Сумма к оплате: ", total, "руб.")
