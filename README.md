# #2. Postman
*Here I continued to learn how to create request in Postman and use autotests.*
### EP_1 (/first)  
```
http://162.55.220.72:5005/first
1. Отправить запрос.
2. Статус код 200
3. Проверить, что в body приходит правильный string.
```
![EP_1](https://github.com/artemlat/postman_hw_2/blob/main/EP_1.png)

### EP_2 (/user_info_3)

```
http://162.55.220.72:5005/user_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Проверить, что name в ответе равно name s request (name вбить руками.)
5. Проверить, что age в ответе равно age s request (age вбить руками.)
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)
7. Спарсить request.
8. Проверить, что name в ответе равно name s request (name забрать из request.)
9. Проверить, что age в ответе равно age s request (age забрать из request.)
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
11. Вывести в консоль параметр family из response.
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)
```
![EP_2(1)](https://github.com/artemlat/postman_hw_2/blob/main/EP_2(1).png)
![EP_2(2)](https://github.com/artemlat/postman_hw_2/blob/main/EP_2(2).png)
![EP_2(3)](https://github.com/artemlat/postman_hw_2/blob/main/EP_2(3).png)
![EP_2(4)](https://github.com/artemlat/postman_hw_2/blob/main/EP_2(4).png)
![EP_2(5)](https://github.com/artemlat/postman_hw_2/blob/main/EP_2(5).png)

### EP_3 (/object_info_3)

```
http://162.55.220.72:5005/object_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age s request (age забрать из request.)
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
8. Вывести в консоль параметр family из response.
9. Проверить, что у параметра dog есть параметры name.
10. Проверить, что у параметра dog есть параметры age.
11. Проверить, что параметр name имеет значение Luky.
12. Проверить, что параметр age имеет значение 4.
```

![EP_3(1)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(1).png)
![EP_3(2)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(2).png)
![EP_3(3)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(3).png)
![EP_3(4)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(4).png)
![EP_3(5)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(5).png)
![EP_3(6)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(6).png)
![EP_3(7)](https://github.com/artemlat/postman_hw_2/blob/main/EP_3(7).png)

### EP_4 (/object_info_4)

```
http://162.55.220.72:5005/object_info_4
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age из request (age забрать из request.)
7. Вывести в консоль параметр salary из request.
8. Вывести в консоль параметр salary из response.
9. Вывести в консоль 0-й элемент параметра salary из response.
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.
12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)
13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)
14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)
15. Создать в окружении переменную name
16. Создать в окружении переменную age
17. Создать в окружении переменную salary
18. Передать в окружение переменную name
19. Передать в окружение переменную age
20. Передать в окружение переменную salary
21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.
```
![EP_4(1)](https://github.com/artemlat/postman_hw_2/blob/main/EP_4(1).png)
![EP_4(2)](https://github.com/artemlat/postman_hw_2/blob/main/EP_4(2).png)
