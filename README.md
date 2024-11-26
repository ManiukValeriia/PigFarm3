Практична робота №6

Мета роботи: Набути досвіду створення запитів у реляційній моделі баз даних, ознайомитися з основними операціями реляційної алгебри та навчитися застосовувати їх для оптимізації запитів і роботи з даними. 

Постановка задачі: 

Завдання 1. За своїм варіантом (додаток А) виконати завдання по 
реляційній алгебрі з побудовою відповідної структури запиту мовою 
реляційної алгебри. 

Завдання 2. Для одного з запитів Вашого варіанту (основного, по 
якому були виконані практичні роботи 3, 4, 5) виконати побудову запиту до предметної області мовою реляційної алгебри.

Варіант 16 

1.Отримати повну інформацію про постачальників

2. Отримати повну інформацію про всі проекти в Києві
    
3.Отримати всі поєднання "ім'я постачальника-статус"

4.Отримати всі кольори товарів

5.Отримати всі поставки, де кількість товару постачальника S2 більше 200

6.Отримати номери та імена постачальників з Києва

7.Отримати імена товарів синього кольору, які постачаються постачальником S3

8.Отримати імена постачальників та їх статус, які беруть участь у проекті Офіси.

9. Отримати номери постачальників, які постачають або товари з Одеси або для проекту з Харкова. 

Варіант № 16

При побудові функціональної моделі інформаційної системи (ІС) свиноферми були використані дані з попередньої практичної роботи. На етапі створення контекстної діаграми (DFD) було враховано контекстну діаграму з практичної роботи №3, у якій визначені основні сутності: «Свиноферма», «Постачальники кормів», «Ветеринарна служба» та «Покупець продукції». До контекстної діаграми були додані необхідні входи та виходи, такі як постачання кормів, ветеринарний контроль, замовлення продукції та продаж свиней.

Процес декомпозиції контекстної діаграми був заснований на результатах попередніх досліджень. Були визначені основні задачі, які покладаються на інформаційну систему, а саме: управління поголів’ям свиней, моніторинг здоров’я тварин, планування виробництва, управління запасами кормів і продаж готової продукції.

Декомпозиція визначених задач (створення підпроцесів) дозволила більш глибоко зрозуміти внутрішні процеси, що відбуваються у кожній задачі, такі як облік народжуваності, контроль використання кормів і ветеринарного обслуговування. Крім того, створення моделі IDEF3 дало можливість описати та візуалізувати послідовність виконання дій, починаючи з надходження кормів на ферму і закінчуючи реалізацією готової продукції покупцеві. Це забезпечило комплексне розуміння процесів, що відбуваються у свинофермі, та сприяло побудові ефективної моделі управління.

Варіант №16 - Свиноферма

У базі даних повинна міститися інформація про ведення тварин на 
свинофермі. Про кожну дорослу тварину необхідно знати: нік 
(унікальний), стать, вік, який з трьох щеплень зробив і коли, 
призначення (на забій, на продаж, на продовження роду). Якщо у3 
свиней є поросята, слід вказати їх кількість і дату народження. Свині 
їдять материнське молоко, тому корм на них не витрачається 
даремно. По можливості слід вести родовід для кожної дорослої 
тварини - прізвисько батька і матері (або слово «невідомий»). 
Тварини, які діють як мати або батько, повинні мати мету для 
отримання потомства ". За тваринами доглядають свині. Про кожну 
свиню потрібно знати унікальний F.I.O., яких тварин вона 
обслуговує (одна тварина може подавати тільки одну свиню), вага 
кожної тварини в кінці будь-якого місяця і споживання кормів 
кожного виду для кожної тварини в будь-який місяць. 

Запити 
* Вивести прирісток кожної тварини зазначеної свинарки за вказаний період часу та середній їх приріст, де приріст - це зміна ваги тварини, і скласти відомість витрати кормів усіх видів за вказаний період часу для зазначеної свинарки
* Визначити, які щеплення не зроблено яким свиням заданої свинарки;
* Вивести всі дані про тварин, які обслуговуються певною свинаркою, включаючи родовід до третього покоління;
*Для всіх свиней розрахувати і впорядкувати в порядку убування їх виконання за даний місяць, що дорівнює загальному введенню тварини, розділеному на загальне споживання корму всіх видів для всіх тварин кожного свинарника;
* Розрахувати кількість корму, спожитого всією сім'єю тварини (ним самим, матір'ю і батьком) протягом певного періоду часу.
  Транзакція: 
Розробити дизайн нових дорослих тварин і списати старі з 
виробництва; 
* Закрити місяць для плати за тварину і витрати на корм

  ![image](https://github.com/user-attachments/assets/03dc37da-9224-4a43-aa99-ca9a046a151c)

  ![image](https://github.com/user-attachments/assets/d77b00ea-fe54-41bb-a18f-c0a4aae653d8)


