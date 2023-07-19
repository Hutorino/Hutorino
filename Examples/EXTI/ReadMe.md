ВНЕП - ВНЕшнеее Прерывание (EXTI - EXTernal Interrupt)
Этот пример работает без использования сторонних библиотек
(This example works without using third-party libraries)
Для примера работы EXTI используем кнопку USR_BTN (PA2). По USART раз в секунду передаётся сообщение "Run at main", а при нажатии кнопки USR_BTN срабатывает внешнее прерывание и в порт отправляется сообщение "Run at EXTI".
(For an example of how EXTI works, we use the USR_BTN button (PA2). The message "Run at main" is transmitted via USART once a second, and when the USR_BTN button is pressed, an external interrupt is triggered and the message "Run at EXTI" is sent to the port.)
