# ООП


# Декораторы @@classmethod и @staticmethod

Существуют следующие типы методов:

1. Методы экземпляра
2. Методы класса
3. Статические методы

**MyClass.my_classmethod()** - вызов метода класса. Метод класса имеет обязательный параметр cls, который ссылается на сам класс:

class MyClass:
    @classmethod
    def my_classmethod(cls):
        print('Это метод класса')
        print(cls)


MyClass.my_classmethod()
