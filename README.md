# Отчёт о тестировании Money Transfer
## Краткое описание
Анализ ситуации, где при пополнении счета, в результате выводится отрицательный баланс.
04.05.2021- 05.04.2021 был проведен анализ ситуации с отрицательным балансом приложения Money Transfer
На тестирование затрачено: <время в часах>
3 ч
В результате тестирования выявлены следующие дефекты:
* <ссылка на описание дефекта>https://github.com/Alina1103master/cartoteka/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Сумма остатка, после пополнения ушла в минус
1. Скопировать кусок кода
public class Main {
public static void main(String[] args) {
int price = 2_000_000_000;
int count = 500_000_000;
int total = price + count;

 System.out.println("Total:" +total);
}
}
2. Вставить код в папку src.
3. Запустить код кнопкой Run.
4. В нижнем окне Main, где отображается результат запуска кода, отобразится сообщение с пополненным балансом на ту, сумму которая указана в коде.
Имя устройства LAPTOP-ALAIPIFN Процессор Intel(R) Core(TM) i3-5005U CPU @ 2.00GHz 2.00 GHz Оперативная память 4,00 ГБ Код устройства B3C5DD95-3EBD-455A-BE72-BA302E1DB015 Код продукта 00327-30000-00000-AAOEM Тип системы 64-разрядная операционная система, процессор x64
Выпуск Windows 10 Домашняя для одного языка Версия 20H2 Дата установки ‎23.‎03.‎2021 Сборка ОС 19042.867 Взаимодействие Windows Feature Experience Pack 120.2212.551.0
Java 11.01
