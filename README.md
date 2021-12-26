# Дели-вери кебаб

## Звонок от заказчика

<details>
<p>
Привет! Я - Боря. Работаю в "Дели-вери Кебаб".  У меня есть гениальная идея. 
Периодически возникают ситуации, когда заказчик не хочет принимать 
доставку еды. По регламенту мы должны выкинуть эту еду в мусорку.

Но что если нам не придётся переводить продукты! Наверняка вокруг много людей, 
которые с удовольствием бы съели недоставленный бургер за половину цены.

Поэтому я хочу, чтобы вы сделали приложение, в котором доставщик мог бы 
разместить непринятый заказ, а люди рядом смогли бы его выкупить со 
скидкой.
</p>
</details>

## Требования

### Главная страница

* Кнопка регистрации
* Кнопка входа
* Список ближайших доступных непринятых заказов
  * Отсортированный по расстоянию
  * Для каждого заказа:
    * Картинка
    * Название
    * Исходная цена
    * Цена со скидкой
    * Кнопка "Выкупить"
      * Доступна только аутентифицированным пользователям
      * При нажатии уходит уведомление курьеру с телефоном и местоположением клиента

### Страница регистрации
  
  * Две роли: курьер и заказчик

### Кабинет курьера

* Форма добавления непринятого заказа
  * Ввод названия
  * Добавление картинки
  * Текущее местоположение
  * Исходная цена
  * Размер скидки в процентах

* Список добавленных заказов
  * Возможность удалить
