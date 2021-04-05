# Отчёт о тестировании 
Precision

# Краткое описание
03.04.2021 - 03.04.2021 было проведено smoke test Precision.

На тестирование затрачено: 1 (один) час

# В результате тестирования выявлены следующие дефекты:
*   [Неверный подсчёт бонусов клиента #1](https://github.com/Maksim-Pat/2DZ-2zadanie/issues/1)

# В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком»](https://github.com/netology-code/javaqa-homeworks/tree/master/programming) 
* IntelliJ IDEA Community Edition 2020.3.3


# В качестве тестовых данных использовались данные:
```public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }}
```

# Тестирование производилось в следующем окружении:

* Windows 7
* IntelliJ IDEA Community Edition 2020.3.3