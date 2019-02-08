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

!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


!!! info
    Был сильный мороз.
           
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
  ```
  import os

  Pomaceous fruit of plants of the genus Malus in
  the family Rosaceae.
  ```

- Java
  ```
  The fruit of an evergreen tree of the genus Citrus.
  ```

- Just Tab
  - One
  - Two

- Other Tab
  1. Item
  1. Item
  1. Item

a **b** c.

{% endtabs}

<details>
  <summary>Some details</summary>
  <p>More info about the details.</p>
  a **b** c.
</details>


??? optional-class "Summary"
    Here's some content.
    
## List Tables

*   -   Title
    -   Description
    -   Default value
*   -   Foo
    -   Lorem ipsum dolor amet, blah-blah-blah, really long description, just goes on and on
    -   42
*   -   Bar
    -   Short description 
    -   2
*   -   Baz
    -   A very long description again. Notice how the table has already completely fallen apart because you cannot track the table's structure anymore since all lines have different length.
    -   13

## HTML Tables
 <table>
     <tr>
        <th>Поле</th>
        <th>Описание</th>
     </tr>
     <tr>
        <td>`name`</td>
        <td>Имя [источника](../reference/glossary.md#source-dscr), данные которого содержит объект.</td>
     </tr>
 </table>
 
 ## Заголовок
 
 С текстом

## Модификаторы ссылок

Всё это находится в [{#A} области действия](../tasklist.md) наших приборов.

Всё это находится в [{#B} области действия](../tasklist.md) наших приборов.

Всё это находится в [{#N} области действия](../tasklist.md) наших приборов.

Всё это находится в [{#ABN} области действия](../tasklist.md) наших приборов.

Всё это находится в [{#ANB} области действия](../tasklist.md) наших приборов.

Всё это находится в [{#NBA} области действия](../tasklist.md) наших приборов.
