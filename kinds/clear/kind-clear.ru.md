---
---

## Клеарфикс

    kind: clear

Этот тип используется в качестве клеарфикса. Используется метод микроклеарфикса _(нужна ссылка)_, поэтому по умолчанию элемент клирится и сверху, и снизу.

### Клеарфикс только с нужной стороны

Если нужно заклирить только с одной стороны, можно использовать параметры `after` или `before`:

    kind: clear after

    kind: clear before

### Элементы для клеарфикса

_(пока не реализовано)_

По умолчанию блок клирится псевдоэлементами, если же необходимо сделать это обычным элементов (или применить на сам блок), можно воспользоваться параметрами-элементами `-before` и `-after`:

    kind: clear (-after '& > .clearfix')
