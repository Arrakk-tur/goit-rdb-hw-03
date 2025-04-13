# goit-rdb-hw-03

SQL запити:

### Завдання 1:

- > "Напишіть SQL команду, за допомогою якої можна:
  >
  > - вибрати всі стовпчики (За допомогою wildcard "\*") з таблиці products;
  > - вибрати тільки стовпчики name, phone з таблиці shippers"

- ```sql
  SELECT * FROM lection_them3.products;
  ```
- ```sql
  SELECT name, phone FROM lection_them3.shippers;
  ```

- **Screenshot:**
  - p1_all_data_products.png
  - p1_query_to_shippers.png

### Завдання 2:

- > Напишіть SQL команду, за допомогою якої можна знайти середнє, максимальне та мінімальне значення стовпчика price таблички products

- ```sql
  -- AVG
  SELECT AVG(price) AS average_price FROM lection_them3.products;
  ```
- ```sql
  -- MAX
  SELECT MAX(price) AS max_price FROM lection_them3.products;
  ```
- ```sql
  -- MIN
  SELECT MIN(price) AS min_price FROM lection_them3.products;
  ```

- **Screenshot:**
  - p2_average_price.png
  - p2_max_price.png
  - p2_min_price.png

### Завдання 3:

- > Напишіть SQL команду, за допомогою якої можна обрати унікальні значення колонок category_id та price таблиці products. Оберіть порядок виведення на екран за спаданням значення price та виберіть тільки 10 рядків.

- ```sql
  SELECT DISTINCT
      category_id, price
  FROM
      lection_them3.products
  ORDER BY price
  LIMIT 10;
  ```

- **Screenshot:**
  - p3_distinct_price.png

### Завдання 4:

- > Напишіть SQL команду, за допомогою якої можна знайти кількість продуктів (рядків), які знаходиться в цінових межах від 20 до 100.

- ```sql

  ```

- **Screenshot:** p4\_

### Завдання 5:

- > Напишіть SQL команду, за допомогою якої можна знайти кількість продуктів (рядків) та середню ціну (price) у кожного постачальника (supplier_id).

- ```sql

  ```

- **Screenshot:** p5\_
