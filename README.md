# bench_context

# Winograd Schema Challenge

## Суть
Winograd Schema Challenge — классический тест для языковых моделей, состоящий из вопросов со следующей структурой:
    1. Предложение (или короткий текст), в котором есть: (а) два референциальных выражения (NP), разделяющих семантический класс; (б) неоднозначное местоимение (анафор/прономинал), которое может относиться к любому из РЕ из пункта (а); составляющая с альтернативой (обычно 1 слово), такая, что в зависимости от того, какую из альтернатив выбрать, меняется референт для местоимения из пункта (б).
    2. Вопрос (к какому из РЕ относится неоднозначное местоимение) с вариантами ответа.

Например: *[The city councilmen] refused [the demonstrators] a permit because [they] [feared/advocated] violence.*

Ссылка: Levesque, H. J., Davis, E.,  Morgenstern, J. (2012). The Winograd Schema Challenge. In *Proceedings of the Thirteenth International Conference on the Principles of Knowledge Representation and Reasoning* (KR 2012).

## Плюсы и минусы нашей альтернативы

Минусы: совпадение сем. класса референтов придётся проверять руками (ну или забить); нет пар с противоположными правильными ответами