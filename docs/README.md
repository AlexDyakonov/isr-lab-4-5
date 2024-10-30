# Проект: Геометрические расчеты

## Описание
Этот проект содержит функции для вычисления:
- Площади и периметра круга
- Площади и периметра квадрата
- Площади прямоугольника
- Площади треугольника

## Структура проекта

- `circle.py` — функции для работы с кругом.
- `square.py` — функции для работы с квадратом.
- `rectangle.py` — функции для работы с прямоугольником.
- `triangle.py` — функции для работы с треугольником.
- `docs/README.md` — документация проекта.

## Детальное описание функций

<details>
  <summary><strong>Модуль `circle.py`</strong></summary>

  - **`area(r)`**
    - **Описание**: Вычисляет площадь круга.
    - **Параметры**: `r` (float) — радиус.
    - **Пример**:
      ```python
      from circle import area
      print(area(5))
      ```

  - **`perimeter(r)`**
    - **Описание**: Вычисляет периметр круга.
    - **Параметры**: `r` (float) — радиус.
    - **Пример**:
      ```python
      from circle import perimeter
      print(perimeter(5))
      ```

</details>

<details>
  <summary><strong>Модуль `square.py`</strong></summary>

  - **`area(a)`**
    - **Описание**: Вычисляет площадь квадрата.
    - **Параметры**: `a` (float) — длина стороны.
    - **Пример**:
      ```python
      from square import area
      print(area(4))
      ```

  - **`perimeter(a)`**
    - **Описание**: Вычисляет периметр квадрата.
    - **Параметры**: `a` (float) — длина стороны.
    - **Пример**:
      ```python
      from square import perimeter
      print(perimeter(4))
      ```

</details>

<details>
  <summary><strong>Модуль `rectangle.py`</strong></summary>

  - **`area(length, width)`**
    - **Описание**: Вычисляет площадь прямоугольника.
    - **Параметры**: `length` и `width` — длина и ширина прямоугольника.
    - **Пример**:
      ```python
      from rectangle import area
      print(area(5, 3))
      ```

</details>

<details>
  <summary><strong>Модуль `triangle.py`</strong></summary>

  - **`area(base, height)`**
    - **Описание**: Вычисляет площадь треугольника.
    - **Параметры**: `base` и `height` — основание и высота треугольника.
    - **Пример**:
      ```python
      from triangle import area
      print(area(6, 4))
      ```

</details>

## История изменений

- `3e53f8d`: Добавлен `triangle.py`, исправлен `rectangle.py`
- `d9cf71c`: Добавлен `rectangle.py`
- `d078c8d`: Добавлена документация
- `8ba9aeb`: Добавлены функции для круга и квадрата