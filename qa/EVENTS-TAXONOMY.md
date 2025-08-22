# Аналітичні події (що відправляємо)

Обов'язково:
- view_home, view_category, search
- filter_apply, sort_apply
- view_item, add_to_cart
- begin_checkout, add_shipping_info, add_payment_info, purchase
- add_to_wishlist

Для кожної події відправляємо: час (event_time), user_id або session_id, screen, props (наприклад {product_id, price}).
