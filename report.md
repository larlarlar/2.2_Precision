# Отчёт о тестировании приложения "Precision"

## Краткое описание

Создано базовое приложение, в котором размещен код:

public class Main {

  public static void main(String[] args) {
  
    double regularBonus = 0.3;
    
        double specialBonus = 0.6;
        
    double totalBonus = regularBonus + specialBonus;
    
    System.out.println(totalBonus);
    
  }
  
}

Была проверена работоспособность кода. При введённых данных сложение происходит некорректно.
## Описание тестов

Было провеедено функциональное тестирование. Тестировалась функция корректного сложения.

## Результаты

1. 100 % неуспешных тестов (1).
2. [Приложение некорректно складывает "бонусы"](https://github.com/larlarlar/2.2_Precision/issues/1#issue-782215558)

## Общие рекомендации

Проверить код, возможно ошибка в типе данных float.
