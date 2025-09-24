LAB01

1. ![Картинка1](./images/Lab01.Код%20работы%20номера%201.png)
```python
name = input('Имя:')
age = int(input('Возраст:'))
next_age = age + 1
print(f'Привет, {name}! Через год тебе будет {next_age}.')
```
2. ![Картинка2](./images/Lab01.Код%20работы%20номера%202.png)
```python
a = input('a:')
b = input('b:')

x = float(a.replace(',','.'))
y = float(b.replace(',','.'))

sum1 = x+y
avg1 = round((x+y)/2, 2)
print(f'sum={sum1}; avg={avg1}')
```
3. ![Картинка3](./images/Lab01.Код%20работы%20номера%203.png)
```python
price = float(input('Цена(₽):'))
discount = float(input('Скидка(%):'))
vat = float(input('НДС(%):'))

base = price * (1-discount/100)
vat_amount = base * (vat/100)
total = base + vat_amount

base_r = round(base, 2)
vat_r = round(vat_amount, 2)
total_r = round(total, 2)

print("База после скидки:", base_r, "₽")
print("НДС:              ", vat_r, "₽")
print("Итого к оплате:   ", total_r, "₽")
```
4. ![Картинка4](./images/Lab01.Код%20работы%20номера%204.png)
```python
m = int(input('Минуты:'))
h = m//60
mn = m%60
if mn < 10:
    print(f'{h}:0{mn}')
else:
    print(f'{h}:{mn}')
```
5. ![Картинка5](./images/Lab01.Код%20работы%20номера%205.png)
```python
st = str(input()) 
ini = '' 
while '  ' in st: 
    st = st.replace('  ', ' ') 
st = st.strip() 
for a in st: 
    if a.isupper(): 
        ini += a 
 
 
print(ini) 
print(len(st))
```
