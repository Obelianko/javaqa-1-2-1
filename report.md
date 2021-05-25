# Отчёт о тестировании Money Transfer

## произведено тестирование правильности расчета остатка счета после его пополнения при помощи кода с использованием указанных переменных

25 мая 2021 было проведено тестрование денежного перевода с использованием кода приложения Money transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/Obelianko/javaqa-1-2-1/issues/1

Причина: Использован некорректный тип переменной

## Описание процесса тестирования

В процессе тестирования артефакты не использовались

В качестве тестовых данных использовались данные кода из https://github.com/netology-code/javaqa-code/blob/master/1.2_programming/variables/src/Main.java
и числовые данные из задания  https://github.com/netology-code/javaqa-homeworks/tree/master/programming:
* public class Main {

  public static void main(String[] args) {

    int price = 2_000_000_000;

    int count = 500_000_000;

    int total = price + count;

    System.out.println(total);

  }

}

Expecting result = 2500000000


Тестирование производилось в следующем окружении:
* OC X El Capitan 10.11.6 (15G22010)
* openjdk 11.0.10 2021-01-19
* IntellijIDEA 2021.1.1
