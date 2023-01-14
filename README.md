</div>
<div id="header" align="center">

<img src ="https://media.giphy.com/media/J5B00esp0BoiCrqdCe/giphy.gif" />
  <hr/>
  <img src="https://img.shields.io/badge/python-v3.7-green" />



</div>

EN
==

MAIN 
--
This library is used to generate a password with settings.

PURPOSE
--
The library can be used to generate a password in your code. The function for the library is easy to use, the user only fills in the basic settings, the rest is done by random.

INSTALLATION
--
Navigate to the directory you are using, and write:
```
pip install genp

```

USAGE HOWTO
--
To generate a password, simply import the library and call the `password_generation()` function

NOTE that the function accepts 4 variables:`
1. whether to use numbers (If yes -  True, otherwise False ).
2. Whether to use letters (If yes - True, otherwise False ).
3. Whether to use special characters (If yes - True, otherwise False ).
4. The length of the password to be generated (enter an integer, unlimited ).
![image](https://user-images.githubusercontent.com/79650307/212470755-2f9c1009-31bc-4a67-b557-237aea0e2133.png)



EXAMPLE #1
---
```
pip install genp
python
>>from genp import password_generation
>>password_generation(True,True,True,19)
'J+J@<U^]jk5SS~w]}k,'

```
In this case, the function has generated a password that includes all the settings: numbers, letters, and special characters.


EXAMPLE #2
---

```
pip install genp
python
>>>from genp import password_generation
>>>password_generation(False,True,False,10)
'pMLFFkemQT'

```

In this case, we also set the function to generate a password without digits and without special characters, i.e. only letters are used.

ERROR HANDLING
--

This function should return an error if not filled out correctly:

```
>>> password_generation(False,False,1)
    raise Exception("Error!")
Exception: Error!
```
Because "False" is set everywhere

RU
==

ОСНОВНОЕ 
--
Это библиотека предназначена для генерации пароля с настройками.

ЦЕЛЬ
--

Библиотеку можно использовать для генерации пароля в своём коде. Функция для библиотеки проста в использовании, пользователь заполняет только основные настройки, остальное - выполняет рандом.

УСТАНОВКА
--

Перейдите в используемую директорию, и напишите:
```
pip install genp

```

ИСПОЛЬЗОВАНИЕ
--

Для того чтобы сгенерировать пароль, достаточно импортировать библиотеку и вызвать функцию `password_generation()`

`УЧТИТЕ, что функция принимает 4 переменные:`
1. Использовать ли цифры (Если да - True, иначе False ).
2. Использовать ли буквы (Если да - True, иначе False  ).
3. Использовать ли специальные символы (Если да - True, иначе False ).
4. Длина генерируемого пароля (указать цифру,неограниченно )
![image](https://user-images.githubusercontent.com/79650307/212470789-c8e2a41e-8fd6-4371-a2fc-ace6be611c01.png)



ПРИМЕР №1
---

```
pip install genp
python
>>from genp import password_generation
>>password_generation(True,True,True,19)
'J+J@<U^]jk5SS~w]}k,'

```

В этом случае функция сгенерировала пароль, включающий все настройки: цифры, буквы, специальные символы.


ПРИМЕР №2
---

```
pip install genp
python
>>>from genp import password_generation
>>>password_generation(False,True,False,10)
'pMLFFkemQT'

```
В этом же случаем мы задали , чтобы функция создала пароль без цифр и без специальных символов, т.е. использовались только буквы.

ОБРАБОТКА ОШИБОК
--

При неправильном заполнение функции должно выдаст ошибку:

```
>>> password_generation(False,False,False,1)
    raise Exception("Error!")
Exception: Error!
```

Потому что везде стоит False.
