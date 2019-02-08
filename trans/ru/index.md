# MkDocs test

Text and

> Note

{% note %}

> Текст примечания.
> 
> Продолжение изложения.

{% endnote %}

> [!NOTE]
> 
> Удалить можно только пустую корзину.
> 
> XXX

!!! note Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

!!! info Был сильный мороз.

      | First Header  | Second Header |
      | ------------- | ------------- |
      | Content Cell  | Content Cell  |
      | Content Cell  | Content Cell  |
    

[!INCLUDE [auth](../../_includes/authentication.md)]

{% inc '[auth](../../_includes/authentication.md)' %}

{% inc no-title '[auth](../../_includes/authentication.md)' %}

{% inc literal '[auth](../../_includes/authentication.md)' %}

[!LINK-TITLE [switch cloud](cloud/switch-cloud.md)]

{% link-title '[switch cloud](cloud/switch-cloud.md)' %}

[!LINK-META [meta_name](cloud/switch-cloud.md)]

{% link-meta '[meta_name](cloud/switch-cloud.md)' %}

{% tabs %}

- Python
  
      import os
      
      Pomaceous fruit of plants of the genus Malus in
      the family Rosaceae.
      

- Java
  
      The fruit of an evergreen tree of the genus Citrus.
      

- Just Tab
  
  - One
  - Two

- Other Tab
  
  1. Item
  2. Item
  3. Item

a **b** c.

{% endtabs}

<details> <summary>Some details</summary>

More info about the details.

    a **b** c.
    

</details>

??? optional-class "Summary" Here's some content.

## List Tables

- - Title 
    - Description
    - Default value
- - Foo 
    - Lorem ipsum dolor amet, blah-blah-blah, really long description, just goes on and on
    - 42
- - Bar 
    - Short description 
    - 2
- - Baz 
    - A very long description again. Notice how the table has already completely fallen apart because you cannot track the table's structure anymore since all lines have different length.
    - 13

## HTML Tables

| Поле     | Описание                                                                                  |
| -------- | ----------------------------------------------------------------------------------------- |
| `name` | Имя \[источника\](../reference/glossary.md#source-dscr), данные которого содержит объект. |

## Заголовок

С текстом

## Модификаторы ссылок

Всё это находится в [* области действия](../gen-ref/concepts/geo-scope.md) наших приборов.

Всё это находится в [*?* области действия](../gen-ref/concepts/geo-scope.md) наших приборов.

Всё это находится в [*+* области действия](../gen-ref/concepts/geo-scope.md) наших приборов.

Всё это находится в [*@* области действия](../gen-ref/concepts/geo-scope.md) наших приборов.

Всё это находится в [*?+@* области действия](../gen-ref/concepts/geo-scope.md) наших приборов.