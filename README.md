# Java_OOP_Seminar_3

## Задание 1

**1.** Реализовать класс User, с полями firstName, lastName, age, переопределить метод toString()

**2.** Создать класс Personal, реализовать интерфейс Iterable<User>

**3.** В классе Main создать список пользователей, добавить его в класс Personal, при помощи foreach, задействуя класс Personal, 
вывести каждого пользователя



## Задание 2

**1.** В классе User реализовать интерфейс Comparable<User>, сравнивать по возрасту

**2.** В классе Main отсортировать список пользователей по возрасту (применяя Comparable<User>


## Задание 3

**1.** Cоздать поле списка подчиненных в классе User, в качестве списка подчиненных использовать класс Personal

**2.** Создать класс Company, реализовать в нем интерфейс Iterable<User>. Передать в класс Company класс User 
(в конструкторе, или через метод), у которого есть подчиненные.

**3.** Организовать итератор в классе Company, реализуя вывод всех подчиненных пользователей, 
можно использовать поиск в глубину, чтобы найти всех подчиненных у подчиненных В классе Main проверить вывод всех пользователей компании

