---
---

## Модальность

### Позиционирование

    kind: modal-wrap

Тип для создания модального элемента (поверх всех элементов на странице), отвечает за позиционирование.

Расширяет типы [`guide`](../guide/kind-guide.ru.md) и [`centering`](../guide/kind-centering.ru.md)

#### Параметр клеарфикса

Если указан параметр `no-elements`, то клеарфиксы не будут сгенерированы

    kind: modal-wrap no-elements


### Содержимое

    kind: modal

Тип для создания содержимого модального элемента. Заполняет весь размер обертки `kind: modal-wrap`.

Расширяет типы `guide-item` и `centering-item`

### Паранжа

    kind: modal-overlay

Тип для создания на странице панаржи, закрывающие все элементы.

Расширяет типы `guide-item` и [`fill`](../guide/kind-fill.ru.md)