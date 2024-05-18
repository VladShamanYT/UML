# Проектирование небольшого приложения по требованиям ТЗ№3 (ВШЭ)

В данной работе описывается онлайн-система заказа еды через мобильное приложение. Предложены некоторые процессы и сценарии, которые являются логичны и реализуемы, с точки зрения пректировщика. В рамках проектирования этой системы подготовлены пять UML-диаграмм. Названия и термины в этих диаграммах приведены на английском языке.

## Диаграмма вариантов использования (Use Case Diagram)
![plot](./UseCasesDiagram.jpg)
- На данной диаграмме внутри границ проектируемой системы можно увидеть различные варианты ее использования такие как "Формироване Заказа", "Обновление Статуса Заказа" и другие. Акторы, обозначенные на диаграмме за пределами системы, показывают сценарии использования этих вариантов. На данной диаграмме указаны самые основные варианты использования и акторы системы.
## Диаграмма последовательности (Sequence Diagram)
![plot](./SequenceDiagram.jpg)
- На данной диаграмме показана последовательность операций при заказе еды через мобильное приложение. Пользователь начинает работать в приложении с поиска еды. Затем следуют шаги подтверждения "корзины", установка своей геолокации, подтверждение заказа и оплата. В этой последовательности, кроме пользователя, участвует само мобильное приложение, онлайн система заказа еды и банк пользователя.
