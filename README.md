#Оглавление

0. [less_1](#less 1)
    1. [Задача_№1](#Задача №1)


# less 1
### Задача №1
* Вывести на одной строке числа 99, 66 и 33 с одним пробелом между ними. Текст '99 66 33' не использовать.

| Ввод | Вывод |
|----------------:|----------------:|
|  | 99 66 33 |

<details>
<summary>Ответ</summary>

```python
a = 99
print (a, a - 33, a - 33*2)
```
</details>

___
### Задача №2
* Вывести на одной строке числа 25, 50 и 75 с двумя пробелами между ними. Текст '25 50 75' не использовать.

| Ввод | Вывод |
|----------------:|----------------:|
|  | 25  50  75 |

<details>
<summary>Ответ</summary>

```python
a = 25
print (a, a  * 2, a * 3, sep='  ')
```
</details>

___
### Напишите программу, которая выведет на экран сороку:
```
  _~_
 (o o)
   V
(  _  )
 M   M
```
<details>
<summary>Ответ</summary>

```python
print ('  _~_ \n (o o)\n   V  \n(  _  )\n M   M ')
```
или
```python
print ('  _~_ ')
print (' (o o)')
print ('   V  ')
print ('(  _  )')
print (' M   M ')
```
</details>

___
### Задача №2
* Узнай что произойдёт, если написать следующую команду: print('Yoda '*5). В ответ к этой задаче, напишите новую программу, которая выведет на экран слово "Загадка" 8 раз.

| Ввод | Вывод |
|----------------:|----------------:|
|  | Загадка Загадка Загадка Загадка Загадка Загадка Загадка Загадка |

<details>
<summary>Ответ</summary>

```python
print('Загадка '*8)
```
</details>

___
# less 2
### Задача №1
* Пользователь вводит с клавиатуры произвольное имя. Напишите программу, которая соответствующе приветствует пользователя.

| Ввод | Вывод |
|----------------:|----------------:|
| Кирилл | Привет, Кирилл ! |
|  | Как настроение? |
<details>
<summary>Ответ</summary>

```python
name = str(input())
print('Привет,', name, '!')
print('Как настроение?')
```
</details>

___
### Задача №2
* Составить программу, которая запрашивает имя человека и повторяет его на экране заданное число раз.

| Ввод | Вывод |
|----------------:|----------------:|
| Макс |  |
| 5 | МаксМаксМаксМаксМакс |
<details>
<summary>Ответ</summary>

```python
name = str(input())
a = int(input())
print(name*a)
```
</details>

___
### Задача №3
* Составить программу вывода на экран числа, вводимого с клавиатуры. Выводимому числу должно предшествовать сообщение «Вы ввели число ».

| Ввод | Вывод |
|----------------:|----------------:|
| 25 | Вы ввели число 25 |
<details>
<summary>Ответ</summary>

```python
a = str(input())
print('Вы ввели число', a)
```
</details>

___
### Задача №4
* Составить программу вывода на экран двух чисел, вводимых с клавиатуры. Вывод организовать в формате: «_ и _ – вот какие числа Вы ввели.».

| Ввод | Вывод |
|----------------:|----------------:|
| 12 |  |
| 34 | 12 и 34 – вот какие числа Вы ввели. |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
print(a, 'и', b, '– вот какие числа Вы ввели.')
```
</details>

___
### Задача №5
* Напишите программу, в которую вводится целое число, после чего на экран выводится следующее и предыдущее целое число. Например, при вводе числа 15 на экран должно быть выведено: Следующее за числом 15 число 16.

| Ввод | Вывод |
|----------------:|----------------:|
| 15 | Следующее за числом 15 число 16 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
print('Следующее за числом', a, 'число', a + 1)
```
</details>

___
### Задача №6
* В классной работе мы разобрали задачу нахождения суммы двух целых чисел. Напишите программу "Калькулятор", которая находит сумму, разность, произведение и частное двух произвольных вещественных чисел, введённых с клавиатуры.

| Ввод | Вывод |
|----------------:|----------------:|
| 10 | Сумма: 12.0 |
| 2 | Разность: 8.0 |
|  | Произведение: 20.0 |
|  | Частное: 5.0 |
<details>
<summary>Ответ</summary>

```python
a = float(input())
b = float(input())
print('Сумма:', a + b)
print('Разность:', a - b)
print('Произведение:', a * b)
print('Частное:', a / b)
```
</details>

___
### Задача №7
* Напишите программу для нахождения числа x, где x = a + b - 2 * c. Числа a, b и с вводятся с клавиатуры.

| Ввод | Вывод |
|----------------:|----------------:|
| 1 | x = -3 |
| 2 |  |
| 3 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
c = int(input())
print('x =', a + b - 2 * c)
```
</details>

___
### Задача №8
* Напишите программу для нахождения числа y, где y = 2 * b. При b = m + k. Числа m и k вводятся с клавиатуры.

| Ввод | Вывод |
|----------------:|----------------:|
| 2 | y = 8 |
| 2 |  |
<details>
<summary>Ответ</summary>

```python
k = int(input())
m = int(input())
print('y =', 2*(m + k))
```
</details>

___
### Задача №8
* На вход подаются два числа - длина и ширина прямоугольника. Напишите программу для нахождения периметра и площади прямоугольника.

| Ввод | Вывод |
|----------------:|----------------:|
| 4 | Периметр прямоугольника = 20 |
| 6 | Площадь прямоугольника = 24 |
<details>
<summary>Ответ</summary>

```python
x = int(input())
y = int(input())
print('Периметр прямоугольника =', 2*(x + y))
print('Площадь прямоугольника =', x * y)
```
</details>

___
### Задача №9
* На вход подаётся число - длина стороны куба. Напишите программу для нахождения площади и объёма куба.

| Ввод | Вывод |
|----------------:|----------------:|
| 2 | Площадь куба = 24 |
|  | Объём куба = 8 |
<details>
<summary>Ответ</summary>

```python
x = int(input())
print('Площадь куба =', 6 * x**2)
print('Объём куба =', x**3)
```
</details>

___
# less 3

### Задача №1
* Пользователь вводит с клавиатуры значение катетов a и b прямоугольного треугольника. Напишите программу, вычисляющую квадрат гипотенузы.

| Ввод | Вывод |
|----------------:|----------------:|
| 2 |  |
| 4 | 13 |
<details>
<summary>Ответ</summary>

```python
x = int(input())
y = int(input())
print(int(x ** 2 + y ** 2))
```
</details>

___
### Задача №2
* Пользователь вводит два целых числа. Напишите программу, выводящую сумму их модулей.

| Ввод | Вывод |
|----------------:|----------------:|
| -2 | 4 |
| 2 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
print(abs(a)+abs(b))
```
</details>

___
### Задача №3
* На вход поступает 4 числа. Первые два - стоимость килограмма конфет и печенья. Оставшиеся два - количество килограмм конфет и печенья, купленных в магазине. Найдите сумму покупки.

| Ввод | Вывод |
|----------------:|----------------:|
| 256 | 1024 |
| 128 |  |
| 2 |  |
| 4 |  |
<details>
<summary>Ответ</summary>

```python
costa = int(input())
costb = int(input())
a = int(input())
b = int(input())
print(a * costa + b * costb)
```
</details>

___
### Задача №4
* Известна стоимость монитора и системного блока. Сколько будут стоить 3 компьютера из этих элементов? N компьютеров?

| Ввод | Вывод |
|----------------:|----------------:|
| 2 | 18 |
| 4 | 6 |
| 1 |  |
<details>
<summary>Ответ</summary>

```python
monitor = int(input())
syst = int(input())
value = int(input())
print((monitor + syst) * 3)
print((monitor + syst) * value)
```
</details>

___
### Задача №5
* Два автомобиля едут навстречу друг другу с постоянными скоростями V1 и V2 км/ч. Определить, через какое время автомобили встретятся, если расстояние между ними было S км.

| Ввод | Вывод |
|----------------:|----------------:|
| 70 | 2 |
| 90 |  |
| 320 |  |
<details>
<summary>Ответ</summary>

```python
v1 = int(input())
v2 = int(input())
s = int(input())
print(int(s / (v1 + v2)))
```
</details>

___
### Задача №6
* Известно значение температуры по шкале Цельсия. Найти соответствующее значение температуры по шкале: а) Фаренгейта; б) Кельвина. Для пересчета по шкале Фаренгейта необходимо исходное значение температуры умножить на 1.8 и к результату прибавить 32, а по шкале Кельвина абсолютное значение нуля соответствует –273.15 градуса по шкале Цельсия.

| Ввод | Вывод |
|----------------:|----------------:|
| 0.0 |  |
|  | 273.15 |
<details>
<summary>Ответ</summary>

```python
a = float(input())
print(float(a * 1.8 + 32))
print(float(273.15 + a))
```
</details>

___
# less 4

### Задача №1
* Пользователь вводит два целых числа. Напишите программу поиска наименьшего из них.

| Ввод | Вывод |
|----------------:|----------------:|
| 8 | 4 |
| 4 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
if a == b:
	print('равны')
elif a > b:
	print(b)
else:
	print(a)
```
</details>

___
### Задача №2
* Хочешь шутку? Программе на вход подаётся целое число. Если число равно 15, то выводит строку "До лето осталось 200 рублей. Шутка." Если число меньше 15 или больше, то выводит строку "Не дождёшься!"

| Ввод | Вывод |
|----------------:|----------------:|
| 14 | Не дождёшься! |
<details>
<summary>Ответ</summary>

```python
a = int(input())
if a == 15:
	print('До лето осталось 200 рублей. Шутка.')
else:
	print('Не дождёшься!')
```
</details>

___
### Задача №3
* Виртуальный ассистент "Аркаша" спрашивает пользователя: "Нравятся ли тебе роботы?". Если пользователь отвечает "да", то программа выводит строку "это немного странно" Если пользователь отвечает "не знаю", то программа выводит строку "определись уже" Если пользователь отвечает "нет", то программа выводит строку "восстание машин покажет"

| Ввод | Вывод |
|----------------:|----------------:|
| нет | восстание машин покажет |
<details>
<summary>Ответ</summary>

```python
a = str(input())
if a == 'да':
	print('это немного странно')
if a == 'не знаю':
	print('определись уже')
if a == 'нет':
	print('восстание машин покажет')
```
</details>

___
### Задача №4
* Напишите программу, которая получает три числа и выводит количество одинаковых чисел в этой цепочке.

| Ввод | Вывод |
|----------------:|----------------:|
| 9 | Все числа одинаковые |
| 9 |  |
| 9 |  |

| Ввод | Вывод |
|----------------:|----------------:|
| 8 | Два числа одинаковые |
| 9 |  |
| 8 |  |

| Ввод | Вывод |
|----------------:|----------------:|
| 7 |  |
| 8 |  |
| 9 |  |

<details>
<summary>Ответ</summary>

```python
a = str(input())
b = str(input())
c = str(input())
z = 0
if a == b:
	z = z + 1
if a == c:
	z = z + 1
elif b == c:
	z = z + 1
if z == 1:
	print('Два числа одинаковые')
if z == 2:
	print('Все числа одинаковые')
if z == 0:
	print('Нет одинаковых чисел')
```
</details>

___
### Задача №5
* На вход подаётся возраст - натуральное число. Если возраст от 0 до 19, то программа выводит строку "Школота". Если от 20 до 59, то программа выводит строку "Скукота". Если от 60 до 99, то программа выводит строку "Рохля". В остальных случаях "Вы в Вальхалле"

| Ввод | Вывод |
|----------------:|----------------:|
| 13 | Школота |

| Ввод | Вывод |
|----------------:|----------------:|
| 77 | Рохля |

<details>
<summary>Ответ</summary>

```python
print('Школота') if year >= 0 and year <= 19 else 0
print('Скукота') if year >= 20 and year <= 59 else 0
print('Рохля') if year >= 60 and year <= 99 else 0
print('Вы в Вальхалле') if year > 99 else 0
```
</details>

___
### Задача №6
* Вводятся год и номер месяца рождения человека, а так же год и номер месяца сегодняшнего дня (январь – 1 и т. д.). Определить возраст человека (число полных лет). В случае совпадения указанных номеров месяцев считать, что прошел полный год.

| Ввод | Вывод |
|----------------:|----------------:|
| 2001 | 20 |
| 5 |  |
| 2021 |  |
| 7 |  |

| Ввод | Вывод |
|----------------:|----------------:|
| 2011 | 9 |
| 5 |  |
| 2021 |  |
| 1 |  |

<details>
<summary>Ответ</summary>

```python
yearborn = int(input())
monthborn = int(input())
year = int(input())
month = int(input())
old = 0
if month < monthborn:
	old = year - yearborn - 1
else:
	old = year - yearborn
print(old)
```
</details>

___
### Задача №7
* Пользователь вводит радиус круга и сторону квадрата. Программа должна сравнить их площади. Если площадь круга больше, то вывести "круг" Если площадь квадрата больше, то вывести "квадрат" Если они равны, то вывести "равны"

| Ввод | Вывод |
|----------------:|----------------:|
| 3 | круг |
| 2 |  |
<details>
<summary>Ответ</summary>

```python
R = int(input())
A = int(input())
Pi = float(3.14)
R = R ** 2 * Pi
A = A ** 2
if R == A:
	print('равны')
elif R > A:
	print('круг')
else:
	print('квадрат')
```
</details>

___
### Задача №8
* На вход программе подаётся число. Программа должна определить чётное ли число и вывести одну строку "чётное" или "не чётное".

| Ввод | Вывод |
|----------------:|----------------:|
| 7 | не чётное |
<details>
<summary>Ответ</summary>

```python
a = int(input())
if a % 2 == 0:
	print('чётное')
else:
	print('не чётное')
```
</details>

___
# less 5

### Задача №1
* Пользователь вводит двузначное число. Найдите произведение его цифр.

| Ввод | Вывод |
|----------------:|----------------:|
| 56 | 30 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = (a // 10) * (a % 10)
print(int(b))
```
</details>

___
### Задача №2
* Пользователь вводит трёхзначное число. Найдите сумму его цифр.

| Ввод | Вывод |
|----------------:|----------------:|
| 123 | 6 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
n = a % 100 // 10
n1 = a // 100
n2 = a % 10
print(int(n + n1 + n2))
```
</details>

___
### Задача №3
* Вводится два числа k и n. Напишите программу, которая проверяет делится ли число k на число n без остатка. Если делится, программа должна выводить строку "yes". Если нет, то "no".

| Ввод | Вывод |
|----------------:|----------------:|
| 6 | yes |
| 2 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
if a % b == 0:
	print('yes')
else:
	print('no')
```
</details>

___
### Задача №4
* Вводится три числа. Выведите цифры в порядке возрастания.

| Ввод | Вывод |
|----------------:|----------------:|
| 5 | 2 |
| 2 | 5 |
| 6 | 6 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
c = int(input())
if a >= b and a >= c:
	print(min(b,c), max(b,c), a)
elif b >= a and b >= c:
	print(min(a,c), max(a,c), b)
elif c >= b and c >= a:
	print(min(b,a), max(b,a), c)
```
или

```python
a = int(input())
b = int(input())
c = int(input())
list = [a, b, c]
list.sort()
for i in list:
	print(i, end='')
```
</details>

___
### Задача №5
* Студент Аркаша сдаёт экзамен. Напишите программу, выводящую оценку Аркадия за экзамен взамен на количество введённых балов. Если балл от 0 до 40 вывести "неудовлетворительно". Если балл от 41 до 60 вывести "удовлетворительно". Если балл от 61 до 80 вывести "хорошо". Если балл от 81 до 100 вывести "отлично".

| Ввод | Вывод |
|----------------:|----------------:|
| 96 | отлично |
<details>
<summary>Ответ</summary>

```python
a = int(input())
if a <= 40:
	print('неудовлетворительно')
if a >= 41 and a <= 60:
	print('удовлетворительно')
if a >= 61 and a <= 80:
	print('хорошо')
if a >= 81 and a <= 100:
	print('отлично')
```
</details>

___
### Задача №6
* Мальчик Аркаша страдает бессонницей. Для того чтобы заснуть он считает овец: одна овца, две овцы, три овцы... Напишите программу, которая на введённое число n (не превышает 10), выводит верное окончание слова "овца".

| Ввод | Вывод |
|----------------:|----------------:|
| 3 | 3 овцы |
<details>
<summary>Ответ</summary>

```python
a = int(input())
if a == 1:
	print(a, 'овца')
if a >= 2 and a <= 4:
	print(a, 'овцы')
if a >= 5 and a <= 10:
	print(a, 'овец')
```
</details>

___
### Задача №7
* Вводится целое положительное число N - количество минут с начала суток. Определите, сколько часов и минут будут показывать электронные часы в этот момент.

| Ввод | Вывод |
|----------------:|----------------:|
| 150 | 2 30 |
<details>
<summary>Ответ</summary>

```python
n = int(input())
hours = n % (60 * 24) // 60
minutes = n % 60
print(hours, minutes)
```
</details>

___
### Задача №8
* Длина Московской кольцевой автомобильной дороги — 109 километров. Байкер Аркаша стартует с нулевого километра МКАД и едет со скоростью v километров в час. На какой отметке он остановится через t часов?

Формат ввода
Программа получает на вход значение v и t. Если v>0, то Вася движется в положительном направлении по МКАД, если же значение v<0, то в отрицательном. (Гарантируется, что исходные числа — целые и находятся в промежутке от -1000 до +1000).

Формат вывода
Программа должна вывести целое число от 0 до 108 — номер отметки, на которой остановится Вася.

| Ввод | Вывод |
|----------------:|----------------:|
| 60 | 11 |
| 2 |  |

| Ввод | Вывод |
|----------------:|----------------:|
| 40 | 80 |
| 2 |  |

<details>
<summary>Ответ</summary>

```python
v = int(input())
t = int(input())
s = v * t
if s > 0:
	while s > 108:
		s = s - 109
	print(s)
if s < 0:
	while abs(s) > 108:
		s = s + 109
	print(109 + s)
```
</details>

___
# less 6

### Задача №1
* Аркаша открыл вклад в банке ОАО "Ждун". Начальная сумма вклада составляла 5000 рублей. По условиям вклада, каждый месяц на остаток на счёте начисляется 4 процента годовых. Напишите программу, которая выведет в ответ сумму на вкладе через n месяцев.

| Ввод | Вывод |
|----------------:|----------------:|
| 1 | 5017 |
<details>
<summary>Ответ</summary>

```python
money = 5000
month = int(input())
for i in range (month):
	money = money + (money * 0.04 / 12)
print(round(money))
```
</details>

___
### Задача №2
* Напечатать все нечетные числа из интервала [10, n].

| Ввод | Вывод |
|----------------:|----------------:|
| 46 | 11 |
|  | 13 |
|  | 15 |
|  | 17 |
|  | 19 |
|  | 21 |
|  | 23 |
|  | 25 |
|  | 27 |
|  | 29 |
|  | 31 |
|  | 33 |
|  | 35 |
|  | 37 |
|  | 39 |
|  | 41 |
|  | 43 |
|  | 45 |

<details>
<summary>Ответ</summary>

```python
a = int(input())
for a in range(10,a+1,1):
	if a % 2 != 0:
		print(a)
```
</details>

___
### Задача №3
* Напишите программу, находящую сумму цифр введённого числа.

| Ввод | Вывод |
|----------------:|----------------:|
| 123 | 6 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
z = 0
if a < 10 ** 9:
    while a > 0:
        x = a%10
        a //= 10
        z += x
print(z)
```
</details>

___
### Задача №4
* Пользователь вводит натуральное число. Напишите программу, выводящую в ответ количество цифр n в этом числе.

| Ввод | Вывод |
|----------------:|----------------:|
| 2443 | 2 |
| 4 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = int(input())
z = 0
while a > 0:
    x = a%10
    a //= 10
    if x == b:
        z += 1
print(z)
```
</details>

___
### Задача №5
* Напишите программу, выводящую числа от 1.0, 1.5, 2.0, 2.5 ... 10.5 в столбик.

| Ввод | Вывод |
|----------------:|----------------:|
|  | 1.0 |
|  | 1.5 |
|  | 2.0 |
|  | 2.5 |
|  | 3.0 |
|  | 3.5 |
|  | 4.0 |
|  | 4.5 |
|  | 5.0 |
|  | 5.5 |
|  | 6.0 |
|  | 6.5 |
|  | 7.0 |
|  | 7.5 |
|  | 8.0 |
|  | 8.5 |
|  | 9.0 |
|  | 9.5 |
|  | 10.0 |
|  | 10.5 |
<details>
<summary>Ответ</summary>

```python
for i in range(10, 110, 5):
    print(float(i) / 10)
```
</details>

___
### Задача №6
* Напишите программу, вычисляющую факториал заданного числа n.

| Ввод | Вывод |
|----------------:|----------------:|
| 4 | 24 |
<details>
<summary>Ответ</summary>

```python
a = int(input())
for i in reversed(range(a - 1, 0, -1)):
    a *= i
print(a)
```
</details>

___
### Задача №7
* Напишите программу, позволяющую ввести и напечатать 5 целых чисел. Условие: программа должна прерывать работу если введён нуль.

| Ввод | Вывод |
|----------------:|----------------:|
| 6 | 6 |
| 2 | 2 |
| 3 | 3 |
| 0 |  |
<details>
<summary>Ответ</summary>

```python
a = int(input())
b = []
while a != 0:
    b.append(a)
    if len(b) < 5:
        a = int(input())
    else:
        break
for i in b:
    print(i)
```
</details>

___
# Олимпийские задачки

## Задача №1
Одна крупная компания открывает новый большой офис. Как известно, открытие офиса связано с большим количеством трудностей. Системный администратор Олег решает задачу предоставления сотрудникам проводного доступа в интернет.

У Олега есть бесконечное количество проводов, но, к сожалению, в новом офисе есть только один разъём от провайдера для подключения интернета. Однако в распоряжении Олега имеется несколько разветвителей. Разветвитель имеет один входной разъём и от одного до трех выходных разъёмов. В разъем
от провайдера можно подключить или один компьютер или входной разъем одного разветвителя. В каждый выходной разъем разветвителя может быть подключен или один компьютер или другой разветвитель. Количество разветвителей в цепи подключений не органичено.

Всего в офисе есть Мкомпьютеров, которые необходимо подключить к интернету. В распоряжении Олега имеется А разветвителей с одним выходным разъёмом, В разветвителей с двумя выходными разъёмами и С разветвителей с тремя выходными разъёмами.

Напишите программу, определяющую максимальное число компьютеров в офисе, к которым можно провести проводной интернет.

### Формат входных данных

В первой строке вводится натуральное число N (1 ≤ N ≤ 100)— количество компьютеров в новом офисе.

Во второй строке вводится натуральное число А (17 ≤ А ≤ 100)- количество разветвителей с одним выходным разъёмом

В третьей строке вводится натуральное число В (1 ≤ В ≤ 100)- количество разветвителей с двумя выходными разъёмами.

В четвёртой строке вводится натуральное число С (7 ≤ С ≤ 100)- количество разветвителей с тремя выходным разъёмами.

### Формат результата

Необходимо вывести одно натуральное число — максимальное количество компьютеров, к которым можно подвести проводной доступ в интернет.

| Ввод | Вывод |
|----------------:|----------------:|
| 10 | 5 |
| 1 |  |
| 2 |  |
| 1 |  |
<details>
<summary>Ответ</summary>

```python
comp = int(input())
solo = int(input())
duo = int(input())
trio = int(input())
a = solo + duo * 2 + trio * 3 - duo - trio
if comp > a:
    print(a)
else:
    print(comp)
```
</details>

___
## Задача №2

Ваня и Дима играют в игру. Ваня загадывает 3 целых числа a, b, c. После чего Ваня выписывает на листочек в случайном порядке четыре числа равные a + b, b + c, с + a и a + b + c. Обозначим числа, записанные на листике, как X, Y, Z, Т. После этого Ваня передает этот листочек Диме и предлагает отгадать числа a, b, c.

По заданным четырем числам X, Y, Z, T напишите загаданные Ваней числа а, b, с.

Формат результата
Напишите три целых числа, загаданных Ваней числа, в любом порядке через пробел.

| Ввод | Вывод |
|----------------:|----------------:|
| 3 | 2 1 9 |
| 12 |  |
| 10 |  |
<details>
<summary>Ответ</summary>

```python
x = int(input())
y = int(input())
z = int(input())
t = int(input())
list = [x,y,z,t]
sum = max(list)
list.remove(sum)
for a in range(0, sum):
    for b in range (0, sum):
        for c in range(0, sum):
            if a + b + c == sum:
                if a + b == list[0] and a + c == list[1] and b + c == list[2] and a + b + c == sum:
                    print(a,b,c)
```
</details>

___
## Задача №3

Петя и Маша решили сыграть в игру. Изначально у Пети и Маши N и M яблок соответственно. Первым ходом Петя передает одно яблоко Маше. На второй ход Маша отдает Пете 2 яблока. Далее Петя передает Маше 3 яблока, и игра продолжается до тех пор, пока у одного из игроков не заканчиваются яблоки.
Формально, на шаге i + 1 получатель яблок из шага i передает второму игроку число яблок, равное переданному числу яблок на шаге i и еще одно.

Напишите программу, которая по заданным N и М вычислит через сколько шагов игра Пети и Маши закончится.

| Ввод | Вывод |
|----------------:|----------------:|
| 1 | 1 |
| 1 |  |

| Ввод | Вывод |
|----------------:|----------------:|
| 2 | 3 |
| 3 |  |

<details>
<summary>Ответ</summary>

```python
Petya = int(input())
Masha = int(input())
count = 0
while Petya > 0 and Masha > 0:
    Petya -= 1 + count
    Masha += 1 + count
    count += 1
    if Masha and Petya != 0:
        Petya += 1 + count
        Masha -= 1 + count
        count += 1
    else:
        break
print(count)
```
</details>

___
## Задача №4

Вчера на день рождения Максиму подарили телепорт (устройство для телепортации). Сегодня Максим хочет опробовать его по дороге в школу.

Улицу, на которой живет Максим, можно представить в виде координатной прямой, на которой дом Максима имеет координату A метров, школа — B метров, а скорость передвижения Максима равна 1 м/с. Телепорт открывает портал в любой точке и моментально перемещает пользователя на расстояние ровно C метров от текущего положения пользователя в сторону школы. Однако телепорт можно использовать только один раз.

Максим хочет как можно быстрее оказаться в школе. Максиму не обязательно использовать телепорт, но он может это сделать, если это ускоряет путь.

Напишите программу, которая по заданным числам А, В и С определит через какое наименьшее количество секунд Максим сможет оказаться в школе.

| Ввод | Вывод |
|----------------:|----------------:|
| 1 7 4 | 2 |
<details>
<summary>Ответ</summary>

```python
a, b, c = input (). split ()
a = int(a)
b = int(b)
c = int(c)
if abs(a) and abs(b) and abs(c) < 110:
    rast = b - a
    timetp = abs(rast) - c
    if abs(rast) > abs(timetp):
        print(timetp)
    else:
        print(abs(rast))
```
</details>
