# uxn

Наработки, собранные в процессе прохождения [туториала](https://compudanzas.net/uxn_tutorial.html) по языку *uxntal*.

> *uxntal* разработан [Devine Lu Linvega](https://merveilles.town/@neauoire) для виртуального 8-битного процессора *uxn*. На базе виртуального CPU *uxn* создан виртуальный компьютер *varvara*.

Подробнее про *uxn* можно почитать на [wiki](https://wiki.xxiivv.com/site/uxn.html) группы Hundred Rabbits.

## День 3

Одна из задач со звёздочкой (раздел «practice possibilities») предлагает создать контроллер, который бы показывал, какие кнопки нажимает пользователь.  
В *uxn* устройство Controller обрабатывает сигналы, поступающие от клавиатуры, как сигналы, собственно, клавиатуры (порт key), так и сигналы NES-контроллера (порт button).

Реализованная задача: /roms/learn_D3_star.rom

![Демонстрация работы рома, который показывает, какие кнопки нажимает пользователь][demo]

Кнопки контроллера в *uxn* сопоставлены с клавиатурой следующим образом:
|Контроллер|Клавиатура|
|-|-|
|A|LCtrl|
|B|LAlt|
|Start|Home|
|Select|LShift|
|Dpad up|Arrow up|
|Dpad down|Arrow down|
|Dpad left|Arrow left|
|Dpad right|Arrow right|

![Окно графического редактора nasu в процессе создания графики для контроллера Famicom][nasu_famicom]

[demo]: /pics/demo.gif "Famicom"
[nasu_famicom]: /pics/nasu.bmp "nasu и контроллер Famicom"
