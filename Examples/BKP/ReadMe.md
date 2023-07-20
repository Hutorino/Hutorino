
## РЗР - РеЗеРвный регистр (BKP - BacKuP Register)
### Этот пример работает без использования сторонних библиотек
### (This example works without using third-party libraries)

Для примера работы BKP записываем в память резервных регистров данные. По USART выводится сообщение о записи данных. По прерыванию TAMPER данные из резервных регистров удаляются с целью защиты от взлома, в порт выводятся уже очищенные данные.
(For an example of BKP operation, we write data to the memory of the backup registers. A message about data recording is displayed on USART. When TAMPER is interrupted, data from the backup registers is deleted in order to protect against hacking, already cleared data is output to the port.)
