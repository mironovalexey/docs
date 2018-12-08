# MkDocs test

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

{% item 'Python' %}
```
import os

Pomaceous fruit of plants of the genus Malus in
the family Rosaceae.
```

{% item 'Java' %}
```
The fruit of an evergreen tree of the genus Citrus.
```

{% item 'Just Tab' %}
- One
- Two

{% tab 'Other Tab' %}
1. Item
1. Item
1. Item

{% endtabs}


<details>
      <summary>XXX<summary>
      <p>More info about the details.</p>
</details>
