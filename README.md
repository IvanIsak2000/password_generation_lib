</div>
<div id="header" align="center">

<img src ="https://media.giphy.com/media/J5B00esp0BoiCrqdCe/giphy.gif" />
  <hr/>
  <img src="https://img.shields.io/badge/python-v3.7-green" />



</div>

EN
==

BASIC 
--

This library is designed to generate a password with settings.

PURPOSE
--

The library can be used to generate a password in your code. The function for the library is easy to use, the user only fills in the basic settings, the rest is done by random.

INSTALLATION
--

Navigate to the directory you are using, and write:

```
pip install pasw-gen

```

USAGE HOWTO
--

To generate a password, simply import the library and call the `password_generation()` function

NOTE that the function accepts 4 variables:`
1 Whether to use numbers (If yes, 1, otherwise 2 ).
2 Whether to use letters (If yes, 1, otherwise 2 ).
Use special characters (If yes - 1, otherwise 2 ).
4. Length of password to be generated (Enter a number between 6 and 30 )

`IMPORTANT: the first three digits of the setting must be 1 or 2, but they cannot all be 2 as a blank password will be generated!`

EXAMPLE #1
```

pip install pasw-gen
python
>>from pasw-gen import password_generation
>>password_generation(1,1,1,25)
g&#.ykuxZQf@7vg?fj?KyfZ6@

```
In this case, the function has generated a password that includes all the settings: numbers, letters, and special characters.


EXAMPLE #2
---


```
pip install pasw-gen
python
>>from pasw-gen import password_generation
>>password_generation(2,1,2,25)
eGzeNPFEz
```
In this case, we also set the function to generate a password without any digits or special characters, i.e. just using letters.

ERROR PROCESSING
--

This function should return an error if it is not filled out correctly:

```
>>password_generation(0,1,1,10)
>>None
```



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
pip install pasw-gen

```

ИСПОЛЬЗОВАНИЕ
--
Для того чтобы сгенерировать пароль, достаточно импортировать библиотеку и вызвать функцию `password_generation()`

`УЧТИТЕ, что функция принимает 4 переменные:`
1. Использовать ли цифры (Если да - 1, иначе 2 ).
2. Использовать ли буквы (Если да - 1, иначе 2 ).
3. Использовать ли специальные символы (Если да - 1, иначе 2 ).
4. Длина генерируемого пароля (Указать цифру в пределах от 6 до 30 )

`НЕДОПУСТИМО: задавать в первые три настройки цифры, отличные от 1 или 2 , а также все первые три настройки НЕ могут быть заполнены цифрой 2`

ПРИМЕР №1
```
pip install pasw-gen
python
>>from pasw-gen import password_generation
>>password_generation(1,1,1,25)
g&#.ykuxZQf@7vg?fj?KyfZ6@

```
В этом случае функция сгенерировала пароль, включающий все настройки: цифры, буквы, специальные символы.


ПРИМЕР №2
---

```
pip install pasw-gen
python
>>from pasw-gen import password_generation
>>password_generation(2,1,2,25)
eGzeNPFEz
```
В этом же случаем мы задали , чтобы функция создала пароль без цифр и без специальных символов, т.е. использовались только буквы.

ОБРАБОТКА ОШИБОК
==
При неправильном заполнение функции должно выдаст ошибку:
```
>>password_generation(0,1,1,10)
>>None
```
