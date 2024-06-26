# Input Lock (блокування введення) #

* Автор: Jose Manuel Delicado
* NVDA compatibility: 2023.3.4 and beyond
* Завантажити [стабільну версію][1]

## Вступ

У вас є вдома діти або домашні тварини? У вас є кішка, і вона дуже любить
вилазити на ваш стіл і ходити по клавіатурі? Ви випадково переміщаєте мишку
до випадкових частин на екрані під час користування ноутбуком? Тоді Input
Lock для вас! Ви зможете залишити свій комп'ютер без нагляду та без ризику.

Once installed, you will be able to lock your keyboard, touch screen (if
your laptop has one), touchpad, mouse and Braille display.

## Як користуватись

This addon adds three extra gestures to NVDA. By default they are
unassigned, so you will have to configure them from Input gestures
dialog. Read the NVDA User Guide for more information.

Коли ви натиснете команду, яка вмикає блокування введення, NVDA промовить
"Input locked" ("Введення заблоковано"). Ваші пристрої введення будуть
заблоковані, доки ви не натиснете команду ще раз. У той момент NVDA
промовить "Input unlocked" ("Введення розблоковано") і все працюватиме як
завжди.

Locking the touchpad can prevent us from accidentally touching it,
especially those who are used to using the laptop keyboard directly. When
you press the toggle touchpad lock gesture, NVDA will say "Touchpad
locked". Your touchpad will be blocked until you press the same gesture
again. In that moment, NVDA will say "Touchpad unlocked" and everything will
work as usual.

Якщо натиснути команду блокування мишки, мишку буде заблоковано. Натисніть
цю команду ще раз, щоб розблокувати її. Поки мишку заблоковано, ви можете
використовувати жести NVDA для її переміщення та клацати лівою та правою
кнопками, але не можете перемістити саму мишку. Клацання мишкою також можна
вимкнути у категорії «Блокування введення» в діалозі налаштувань NVDA (NVDA
2018.2 та новіших версій) або з діалогу налаштувань додатка для старих
версій, яке доступне в меню налаштувань. Крім того, у цих налаштуваннях ви
можете вибрати, чи блокувати клацання мишки після запуску NVDA.

Примітка: коли клацання мишки заблоковані, ви не можете використовувати
будь-які жести NVDA для роботи з мишкою.

## Обмеження та відомі проблеми

Input Lock має такі відомі проблеми:

* Комбінації control+alt+del і windows+l можна використовувати навіть при
  заблокованій клавіатурі.
* For gestures used to lock the touchpad, please try to assign a small
  number of key combination gestures. It is recommended to use NVDA+letters
  or numbers, Ctrl+F keys etc.

## Журнал змін

### Version 1.13

* Now, minimum supported version is 2023.3.4.
* Updated translations. Starting from version 1.13, changelog won't be
  modified when a new release only includes localization updates.
* Added a gesture (unassigned by default) to lock/unlock the touchpad.

### Version 1.12

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.

### Версія 1.11

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.
* Зараз мінімальна підтримувана версія — 2022.4.

### Версія 1.10

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.
* Оновлено документацію.
* Зараз мінімальна підтримувана версія — 2021.3.
* Після виходу з режиму очікування введення залишатиметься
  заблокованим. Дякую Javi Dominguez.

### Версія 1.9

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.
* Оновлено документацію.

### Версія 1.8

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.

### Версія 1.7

* Оновлено прапори сумісності для останніх версій NVDA.
* Оновлено переклади.

### Версія 1.6

* Тепер налаштування видаляються разом з видаленням додатка. Конфігурація
  більше не скидається при оновленні.
* Нові й оновлені переклади.

### Версія 1.5

* Додано сумісність з останніми версіями NVDA.
* Нові переклади.

### Версія 1.4

* Жести додатка початково не призначені.

### Версія 1.3

* Додано панель налаштувань у діалог налаштувань NVDA. Для старіших версій
  NVDA додано відповідний пункт меню.
* Додано опцію, яка дозволяє блокувати мишку після запуску NVDA.
* Додано опцію, яка дозволяє блокувати клацання мишки, коли мишку
  заблоковано.
* Виправлені невеликі помилки, оптимізовано код та зменшено кількість
  дубльованих рядків для перекладачів

### Версія 1.2

* Тепер мишку також можна блокувати
* Нова команда, призначена лише для блокування мишки

### Версія 1.1

* Якщо інший додаток раніше додав функцію перехоплення для inputManager,
  вона відновлюється, коли вхід розблоковано.

### Версія 1.0

* Перший реліз

[[!tag dev stable]]

[1]: https://www.nvaccess.org/addonStore/legacy?file=inputLock
