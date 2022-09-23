# Async `async`

Секція `async` використовується як заповнювач для секцій, які ще не представлені. Ця секція відображається лише тоді, коли ще залишаються спкції, які повинні відобразитись згодом.

За замовчуванням Spaceship працює асинхронно. Він відображає командний рядок відразу, і оновлює його в міру надходження нової інформації.

За бажанням ви можете увімкнути показ кількості секцій, які ще обробляються за допомогою опції `SPACESHIP_ASYNC_SHOW_COUNT`:

```sh title=".zshrc"
SPACESHIP_ASYNC_SHOW_COUNT=true
```

## Опції

| Змінна                       | За замовчуванням | Пояснення                               |
|:---------------------------- |:----------------:| --------------------------------------- |
| `SPACESHIP_ASYNC_SHOW`       |      `true`      | Показати секцію                         |
| `SPACESHIP_ASYNC_SHOW_COUNT` |     `false`      | Показувати кількість задач              |
| `SPACESHIP_ASYNC_PREFIX`     |        -         | Префікс секції                          |
| `SPACESHIP_ASYNC_SUFFIX`     |        -         | Суфікс секції                           |
| `SPACESHIP_ASYNC_SYMBOL`     |       `…`        | Символ, що відображається перед секцією |
| `SPACESHIP_ASYNC_COLOR`      |      `gray`      | Колір секції                            |
