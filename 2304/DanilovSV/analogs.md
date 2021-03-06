## Сравнение аналогов
### LiveTex
Платформа, позволяющая интегрировать сервис для общения с оператором поддержки на веб-страницу, в Android и iOS приложение. Все операторы являются живыми людьми, что одновременно является и плюсом и минусом: услуги операторов стоят денег, в отличие от бота, однако оператор может предоставить более квалифицированную поддержку.

### Наносемантика
На этой платформе используются боты, а не живые операторы. Боты не обучаются (не применяются технологии машинного обучения), а ведут себя согласно предзаданным шаблонам. Шаблоны позволяют чётко прописывать определённые сценарии (в отличии от машинного обучения, которое в целом представляет скорее неинтерпретируемый "чёрный ящик"), однако обладают рядом минусов, таких как невозможность сохранения контекста диалога и необходимость вручную добавлять новые шаблоны (тогда как используя machine learning этот процесс можно автоматизировать).

### Разработки ЦРТ (центра речевых технологий)
Используется машинное обучение для распознавания речи (voice2text), в остальном сохраняются те же проблемы, что и у LiveTex.


## Критерии сравнения аналогов
### Интеграция с внешними системами
Важным критерием является интеграция платформы поддержки с системами заказчика. Интеграция включает в себя возможность авторизации пользователя-клиента, получение данных из CRM, выгрузку статистики и т.д.

### Простота использования и гибкость конфигурации
Решение должно быть простым в использовании для операторов и администраторов заказчика, а также обладать гибкой конфигурацией (например, выбор алгоритмов переобучение модели и выбор алгоритмов обучения на веб-интерфейсе).

### Поддержка
Важным критерием при выборе используемого инструмента является наличие качественной и подробной документации, а также хорошей поддержки.

## Таблица сравнения по критериям

Аналог\Критерий|Интеграция с внешними системами|Простота и гибкость конфигурации|Поддержка
-|-|-|-
LiveTex|-|-|+
Наносемантика|-|+|+
ЦРТ|-|-|+

## Выводы по итогам сравнения
Ни одна из систем не поддерживает необходимый минимальный уровень интеграции с внешними системами, что можно использовать как одну из killer feature разрабатываемой платформы. Так же killer feature будет являться использование машинного обучения, что сделает диалог клиента с роботом более реалистичным и в следствии клиент с меньшей вероятностью переключится на оператора-человека.
