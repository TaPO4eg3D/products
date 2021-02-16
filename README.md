# Products

При помощи сервиса https://fakestoreapi.com/docs реализовано приложение на Angular со следующим функционалом:

## Отображение списка продуктов

**Пагинация.** Реализована при помощи `ng-bootstrap`.

**Настраиваемый размер страницы.** Для выбора установлены значения `5, 10` и `25` элементов на странице.

## Отображение детальной информации о продукте

**Функционал Лупы.** При наведении курсора на изображение продукта оно увеличивается.

## Наличие корзины

**Пользователь имеет возможность:**
1. Добавлять продукты в корзину.
2. Удалять продукты.
3. Изменять количество продуктов.
4. Очищать корзину в один клик.

**Отображение стоимости.** Показывается стоимость продуктов с учетом их количества, а также общая стоимость всех добавленных продуктов.

**Корзина не сбрасывается после перезагрузки страницы.** Реализовано при помощи `localStorage `.

