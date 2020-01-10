# Техническое задание интернет-магазина по продажам одежды:
* ## Общие требования:
     * Разработка эскиза Дизайн и верстка макета сайта
     * Программирование и подключение администраторского модуля
* ## Технологические требования:
     * Сайт разрабатывается под максимальное разрешение 1920x1080,вёрстка должна быть валидной
     * Мета-теги и контент сайта на этапе изготовления сайта настроены для поисковых систем, чтобы обеспечить продвижение сайта по ключевым словам в поисковых системах Yandex, Google и др.
     * На любые некорректные действия посетителя, связанные с вводом неверных данных, незаполнением обязательных полей ввода в формах и прочие, которые могут быть обработаны системой, генерируются соответствующие сообщения об ошибках на русском языке, в рамках общего дизайна сайта.
     * Основная валюта сайта Российский рубль
     * Интеграция с платежной системой
* ## ГЛАВНАЯ страница содержит:
     * Корзину (размещение на усмотрение дизайнера или разработчика )
     * ### Шапка сайта:
           * Логотип (при кликле ведёт на главную страницу)
           * Поиск по товарам
           * Профиль с маленкой картинкой пользователя,при клике выпадает список ссылок,которые ведут на соответствующие страницы:
             * Профиль
             * Корзина
             * Выйти/войти/регистрация 
             (возможно добавление ссылок)
           * #### Навигационное меню:
           * Каталог
           * Тех.поддержка
           * О нас
           *
     * ### body страницы:
           * Слайдшоу
           * Рекламный блок,возможно несколько(для размещения такой информацией как – Акция, Распродажа, Новинка, Хит продаж и пр.)
           * Кликая на слайды и блоки посетитель должен переходить на соответствующие разделы и страницы
     * ### footer страницы:
           * Copyright
           * Возможно добавление ссылок на соц.сети,ввиде иконок(уточнить)
* ## Описание контента разделов сайта: 
     * ### Верхнее меню:
           * Каталог  - меню каталога должно выпадать при наведении на кнопку аналогично сайту mytoys.ru, которые можно добавлять/удалять.
           * Акции – состоит из кликабельных блоков с краткой информацией об акциях, подарках и прочее, которые можно добавлять/удалять.
     * ### Поиск товара:
           * Набрать слово/словосочетание/артикул/бренд в форме запроса и нажать на кнопку ввиде иконки. 
           Результаты поиска будут отображены на специальной странице со списком товаров имеющих это слово или словосочетание в    описании, названии и других полях.
    * ### Корзина:
           * Раздел,демонстрирующий корзину пользователя
                 * Название товара (ссылка на страницу с описанием товара)
                 * Цена
                 * Количество (в виде поля ввода, с возможностью изменения)
                 * Сумма
                 * Поле ввода типа checkbox для указания товарных позиций на удаление
                 * Под таблицей – справа общая сумма заказа
                 * Выбор способа доставки
                 * Выбор способа оплаты
                 * Кнопка Оформить заказ 
                   Нажав на кнопку «Оформить заказ», на E-mail адрес, указанный в свойствах раздела, высылается письмо с содержимым заказа и личными данными заказчика, пользователь же попадает на страницу с текстом об успешности операции заказа. Кроме того на адрес пользователя отсылается уведомление о сделанном им заказе, содержащее ссылку на страницу «слежения за состоянием заказа».
    * ### Личный кабинет 
          * Регистрация
          Логин
          Имя
          E-mail
          Пароль
          Я согласен с данными условиями (Условия обслуживания) 
          Нажав на кнопку «Зарегистрироваться», посетитель попадает на страницу приветствия его, как зарегистрированного пользователя. Одновременно с этим в специальном списке зарегистрированных пользователей в администраторском модуле появляется соответствующая запись, а так же высылается уведомление по электронной почте пользователю и администратору)
          * Забыли пароль?
          Сервис по напоминанию пароля
          * Забыли логин? 
          Сервис по напоминанию логина
          * Авторизация
          Ввод Логина и Пароля
          * Управление учетной записью
          Информация об учетной записи 
          Здесь Вы можете изменить Вашу контактную информацию.
    * ## Раздел Каталог
          * Сложный раздел, состоящий из основных категорий. Каждая категория делится на подкатегории. Подкатегории делятся на группы товаров.
    * ### Основная категория
          * На главной странице сайта. Всплывающий список содержащий название категории и иллюстрация. Здесь отображены все основные разделы каталога со ссылками в подкатегории.
    * ### Подкатегории каталога 
