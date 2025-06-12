# codeforces-nuralinnb7
1. 4A – Watermelon
Ссылка: https://codeforces.com/problemset/problem/4/A
Код Python:
w = int(input())
print("YES" if w > 2 and w % 2 == 0 else "NO")
Объяснение: Проверяем, можно ли разделить арбуз на две равные чётные части.
Скрин Accepted:
2. 71A – Way Too Long Words
Ссылка: https://codeforces.com/problemset/problem/71/A
Код Python:
n = int(input())
for _ in range(n):
 s = input()
 print(s[0] + str(len(s)-2) + s[-1] if len(s) > 10 else s)
Объяснение: Сокращаем длинные слова в формате “l10n”.
Скрин Accepted:
3. 158A – Next Round
Ссылка: https://codeforces.com/problemset/problem/158/A
Код Python:
n, k = map(int, input().split())
a = list(map(int, input().split()))
print(len([x for x in a if x >= a[k-1] and x > 0]))
Объяснение: Считаем количество участников, прошедших дальше.
Скрин Accepted:
4. 231A – Team
Ссылка: https://codeforces.com/problemset/problem/231/A
Код Python:
n = int(input())
c = 0
for _ in range(n):
 if sum(map(int, input().split())) >= 2:
 c += 1
print(c)
Объяснение: Считаем, сколько задач будет решено (≥2 участников).
Скрин Accepted:
5. 282A – Bit++
Ссылка: https://codeforces.com/problemset/problem/282/A
Код Python:
n = int(input())
x = 0
for _ in range(n):
 s = input()
 if '+' in s:
 x += 1
 else:
 x -= 1
print(x)
Объяснение: Увеличиваем или уменьшаем X в зависимости от действия.
Скрин Accepted:
6. 50A – Domino piling
Ссылка: https://codeforces.com/problemset/problem/50/A
Код Python:
m, n = map(int, input().split())
print((m * n) // 2)
Объяснение: Сколько доминошек 2×1 поместится на доске m×n.
Скрин Accepted:
7. 263A – Beautiful Matrix
Ссылка: https://codeforces.com/problemset/problem/263/A
Код Python:
for i in range(5):
 row = list(map(int, input().split()))
 if 1 in row:
 x, y = i, row.index(1)
print(abs(x - 2) + abs(y - 2))
Объяснение: Считаем шаги от центра до позиции “1” в матрице.
Скрин Accepted:
8. 339A – Helpful Maths
Ссылка: https://codeforces.com/problemset/problem/339/A
Код Python:
s = input().split('+')
s.sort()
print('+'.join(s))
Объяснение: Сортируем элементы выражения «1+2+3».
Скрин Accepted:
9. 112A – Petya and Strings
Ссылка: https://codeforces.com/problemset/problem/112/A
Код Python:
a = input().lower()
b = input().lower()
print(0 if a == b else -1 if a < b else 1)
Объяснение: Сравнение строк без учёта регистра.
Скрин Accepted:
10. 41A – Translation
Ссылка: https://codeforces.com/problemset/problem/41/A
Код Python:
s = input()
t = input()
print("YES" if s == t[::-1] else "NO")
Объяснение: Проверяем, являются ли слова зеркальными Составил: nuralinnb7
GitHub: https://github.com/nuralinnb7
