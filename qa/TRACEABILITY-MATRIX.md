# Таблиця відповідності

| Фіча                         | Екран(и)   | API                              | Події аналітики                | Тести              |
|-----------------------------|------------|----------------------------------|--------------------------------|-------------------|
| Нижня навігація             | Всі        | —                                | nav_click                      | UI чеклисти       |
| Каталог: фільтри/сортування | Каталог    | GET /v1/products?filter&sort     | filter_apply, sort_apply       | E2E "фільтр→PDP"  |
| Додати в кошик              | PDP, Кошик | POST /v1/cart/items              | add_to_cart                    | E2E "PDP→кошик"   |
| Редагування кошика          | Кошик      | PATCH /v1/cart/items/{id}        | update_cart_qty                | UI + API          |
| Гостьове замовлення         | Оформлення | POST /v1/orders                  | begin_checkout, purchase       | E2E "чекаут гість"|
| Обране                       | Обране,PDP | POST /v1/wishlist/items          | add_to_wishlist                | UI + API          |
