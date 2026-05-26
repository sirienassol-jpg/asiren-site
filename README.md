# Asiren — сайт кав’ярні з онлайн-замовленням

## Опис проєкту

Asiren — це навчальний web-застосунок кав’ярні, який дозволяє користувачу переглядати меню, додавати товари в кошик та оформлювати замовлення онлайн.

Користувач може обрати спосіб отримання замовлення: доставка додому або самовивіз із кав’ярні.

## Посилання

Репозиторій GitHub:  
https://github.com/sirienassol-jpg/asiren-site

Опублікований сайт:  
https://sirienassol-jpg.github.io/asiren-site/

## Основні можливості

- перегляд меню кав’ярні;
- фільтрація товарів за категоріями;
- додавання товарів у кошик;
- зміна кількості товарів;
- автоматичний підрахунок суми;
- вибір доставки або самовивозу;
- оформлення замовлення через форму.

## Структура web-застосунку

1. Головна сторінка
2. Меню
3. Кошик
4. Оформлення замовлення
5. Контакти

## Використані технології

- HTML
- CSS
- JavaScript
- GitHub Pages

## Приклад JavaScript-коду

```javascript
function addToCart(productId) {
  const product = products.find(item => item.id === productId);
  const cartItem = cart.find(item => item.id === productId);

  if (cartItem) {
    cartItem.quantity += 1;
  } else {
    cart.push({ ...product, quantity: 1 });
  }

  saveCart();
  renderCart();
}
```

## Автор

Лук’янова Анастасія  
Група ЕК-11
