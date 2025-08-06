# Лабораторне заняття №1: Ознайомлення з TypeScript

## Мета роботи
Ознайомитися з основами мови TypeScript шляхом виконання практичних завдань, що демонструють базові можливості мови: типізацію, інтерфейси, класи, композитні типи та дженерики.

---
## Завдання 1: Типізація змінних

**Опис:**  
Оголошено змінні типів `string`, `number`, `boolean`, `array`, `object`.  
Створено функцію, яка приймає об'єкт `{ name: string, age: number }` і повертає форматований рядок.

**Скріншоти: Завдання 1: Типізація змінних**

![](screenshots/task1/task1_1.png)

**Результат .JS:**

![](screenshots/task1/task1_JS.png)

**Результат .D.TS:**

![](screenshots/task1/task1_DTS.png)

**Результат Errors:**

![](screenshots/task1/task1_Error.png)

**Результат Logs:**

![](screenshots/task1/task1_Logs.png)

## Завдання 2: Інтерфейси

**Опис:** 
Створено інтерфейс Person з опціональним полем address.
Реалізовано функцію printPerson, яка виводить дані об'єкта у консоль.

**Скріншоти: Завдання 2: Інтерфейси**

![](screenshots/task2/task2_1.png)

**Результат .JS:**

![](screenshots/task2/task2_JS.png)

**Результат .D.TS:**

![](screenshots/task2/task2_DTS.png)

**Результат Errors:**

![](screenshots/task2/task2_Error.png)

**Результат Logs:**

![](screenshots/task2/task2_Logs.png)

## Завдання 3: Композитні типи (Union type)

**Опис:** 
Оголошено тип Status = 'success' | 'error' | 'loading'.
Функція showStatus виводить повідомлення залежно від значення статусу.

**Скріншоти: Завдання 3: Композитні типи (Union type)**

![](screenshots/task3/task3_1.png)

**Результат .JS:**

![](screenshots/task3/task3_JS.png)

**Результат .D.TS:**

![](screenshots/task3/task3_DTS.png)

**Результат Errors:**

![](screenshots/task3/task3_Error.png)

**Результат Logs:**

![](screenshots/task3/task3_Logs.png)

## Завдання 4: Дженерики

**Опис:** 
Створено універсальну функцію identity<T>, яка повертає значення типу T.
Продемонстровано використання з типами number, string, boolean.

**Скріншоти: Завдання 4: Дженерики**

![](screenshots/task4/task4_1.png)

**Результат .JS:**

![](screenshots/task4/task4_JS.png)

**Результат .D.TS:**

![](screenshots/task4/task4_DTS.png)

**Результат Errors:**

![](screenshots/task4/task4_Error.png)

**Результат Logs:**

![](screenshots/task4/task4_Logs.png)

## Завдання 5: Класи

**Опис:** 
Оголошено клас Car з полями model та year, а також методом getCarInfo().

**Скріншоти: Завдання 5: Класи**

![](screenshots/task5/task5_1.png)

**Результат .JS:**

![](screenshots/task5/task5_JS.png)

**Результат .D.TS:**

![](screenshots/task5/task5_DTS.png)

**Результат Errors:**

![](screenshots/task5/task5_Error.png)

**Результат Logs:**

![](screenshots/task5/task5_Logs.png)

## Дослідження помилок
У кожному завданні тестувалась типова помилка: передача неправильного типу даних.
TypeScript Playground правильно виявляє помилки та відображає їх у вкладці Errors.

**Приклад помилки:**

printPerson({ name: "Bob", age: "25" }); // age очікується як number, а передано string



