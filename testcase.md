## Title

## Перевод денег на счёт

### Summary

Проверим программу перевода денег на счёт

### Priority

High

### Steps to reproduce

1. Открыть IntelliJ IDEA
2. Создать проект
3. Создать Main.java class
4. Вставить код 
```java
   public class Main {
   public static void main(String[] args) {
   int balance = 2_000_000_000;
   int sum = 500_000_000;
   int total = balance + sum;
   System.out.println(total);
   }
}
```
5. Запустить программу


### Expected result

1. IntelliJ IDEA запущена
2. Проект создан
3. Main.java class создан
4. Код вставлен
5. Программа запущена, в терминале видим ответ 2_500_000_000


### Дополнительно

1. Код для вставки (4 шаг)

```java
   public class Main {
   public static void main(String[] args) {
   int balance = 2_000_000_000;
   int sum = 500_000_000;
   int total = balance + sum;
   System.out.println(total);
   }
}
```








