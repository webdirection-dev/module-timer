# module-timer
Скрипт для таймера.


## Подключение модуля
В данном репозитории точкой входа ___Webpack___ является _./src/js/script.js_.
<br /> Импортируем в него модуль со скриптом слайдера:
```javascript
// Точка вхождения Webpack: "./src/js/script.js'
"use strict";
import timer from './modules/timer';

window.addEventListener('DOMContentLoaded', () => {
    timer('.timer', '2021-07-11');
});
```
