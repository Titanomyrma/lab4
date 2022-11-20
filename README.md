# Test cases
---

### Ссылка: [IKIJI](https://ikiji.jp/en/#)

---

### 1. Добавить предмет в корзину

#### Precondition: Наличие интернет-соединения

* В навигационной панели навести курсор на вкладку STORE, нажать ONLINE STORE

* В навигационной панели навести курсор на вкладку ONLINE STORE, нажать на интересующую вкладку

* Кликнуть на изображение продукта

* Пролистать вниз, выбрать цвет, размер, количество и нажать ADD TO CART

#### Expected result: Открыто окно корзины. Выбранный предмет находится в корзине

### 2. Удалить предмет из корзины

#### Precondition: Наличие интернет-соединения, открыта вкладка [магазина](https://store.ikiji.jp/), в корзине добавлены покупки 

* Справа вверху нажать иконку корзины

* Уменьшить количество предметов до 0 или нажать на REMOVE

#### Expected result: Открыто окно корзины. Предмет удален из корзины

### 3. Изменить отображение продуктов

#### Precondition: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://store.ikiji.jp/collections/pants) 

* Слева внизу нажать на тусклую иконку, изображающую вид отображения продуктов

#### Expected result: Изменен вид отображения товаров

### 4. Сортировка

#### Precondition: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://store.ikiji.jp/collections/pants)

* Справа внизу нажать на SORT - SORT

* В списке выбрать сортировку по цене в порядке убывания

#### Expected result: Все предметы сортированы в порядке убыввания цены

### 5. Фильтр

#### Precondition: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://store.ikiji.jp/collections/accessories)

* Справа внизу нажать на FILTER - FILTER

* В списке выбрать кошельки

#### Expected result: Из перечня предметов показаны только кошельки

### 6. Изменение количества на отрицательное значение на странице продукта

#### Precondition: Наличие интернет-соединения, открыта вкладка [товара](https://store.ikiji.jp/products/tps-sweat-shirttps%E7%B8%AB%E8%A3%BD%E8%A3%8F%E8%B5%B7%E6%AF%9B%E3%82%B9%E3%82%A6%E3%82%A7%E3%83%83%E3%83%88%E3%82%B7%E3%83%A3%E3%83%84-br-22aw%E6%96%B0%E8%89%B2?variant=42814778572957) 

* Изменить количество товара на отрицательное значение

#### Expected result: При изменении количества товара на отрицательное значение оно становится единицей

### 7. История просмотра

#### Precondition: Наличие интернет-соединения, открыта вкладка [перечня товаров](https://store.ikiji.jp/collections/accessories)

* Нажать на товар, чтобы перейти на его страницу

* Вернутся на страницу перечня [перечня товаров](https://store.ikiji.jp/collections/accessories)

#### Expected result: В отделе недавние товары находится недавний продукт

### 8. Изменение количества товара в корзине

#### Precondition: Наличие интернет-соединения, открыта вкладка [товара](https://store.ikiji.jp/products/tps-sweat-shirttps%E7%B8%AB%E8%A3%BD%E8%A3%8F%E8%B5%B7%E6%AF%9B%E3%82%B9%E3%82%A6%E3%82%A7%E3%83%83%E3%83%88%E3%82%B7%E3%83%A3%E3%83%84-br-22aw%E6%96%B0%E8%89%B2?variant=42814778572957)

* Добавляем 1 товар в корзину

* Нажимаем на плюс

#### Expected result: Количество продукта изменилось на 1

#### Received result: Количество продукта вернулось к 1

### 9. Добавление существующего товара

#### Precondition: Наличие интернет-соединения, открыта вкладка [товара](https://store.ikiji.jp/products/tps-sweat-shirttps%E7%B8%AB%E8%A3%BD%E8%A3%8F%E8%B5%B7%E6%AF%9B%E3%82%B9%E3%82%A6%E3%82%A7%E3%83%83%E3%83%88%E3%82%B7%E3%83%A3%E3%83%84-br-22aw%E6%96%B0%E8%89%B2?variant=42814778572957), в корзине уже есть данный товар 

* Нажать на кнопку ADD TO CART

#### Expected result: Количество находящегося в корзине товара изменилось на количество добавленного

### 10. Изменение количества на дробное значение на странице продукта

#### Precondition: Наличие интернет-соединения, открыта вкладка [товара](https://store.ikiji.jp/products/tps-sweat-shirttps%E7%B8%AB%E8%A3%BD%E8%A3%8F%E8%B5%B7%E6%AF%9B%E3%82%B9%E3%82%A6%E3%82%A7%E3%83%83%E3%83%88%E3%82%B7%E3%83%A3%E3%83%84-br-22aw%E6%96%B0%E8%89%B2?variant=42814778572957) 

* Изменить количество товара на дробное значение

#### Expected result: При изменении количества на дробное записывается целая часть

