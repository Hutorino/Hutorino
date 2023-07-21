
## ЧРВ - Часы Реального Времени (RTC - Real Time Clock)
### Этот пример работает без использования сторонних библиотек
### (This example works without using third-party libraries)

Для примера работы RTC устанавливаем время и в память резервных регистров записываем значение чтобы при перезагрузке сравнивнить это значение, если сравниваемые значения сходятся, тогда время не переустанавливаем. По USART выводится раз в секунду сообщение о текущем времени.
(For an example of the operation of the RTC, we set the time and write the value to the memory of the backup registers so that this value is compared when rebooting, if the compared values converge, then we do not reset the time. According to USART, a message about the current time is displayed once a second.)
