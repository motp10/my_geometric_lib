# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = a * h / 2

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2a + 2b
- Square: P = 4a
- Triangle: P = a + b + c

# общее описнаие решения 
В проекте содержатся 4 файла с функциями нахождения площади и периметра каждой из четырех фигур 
(треугольник, квадрат, прямоугольник, круг). 
# описание каждой из функций
## Circle area:
- входные данные r
- выходные данные pi * r * r - площадь круга
- Пример:
  - area(5) == 25 * pi;
## Circle perimetr:
- входные данные r
- выходные данные pi * 2 * r - площадь круга
- Пример:
  - perimetr(5) == 10 * pi;
## Square area:
- входные данные a
- выходные данные a * a - площадь квадрата
- Пример:
  - area(5) == 25;
## Square perimetr:
- входные данные r
- выходные данные 4 * r - периметр квадрата
- Пример:
  - perimetr(5) == 20;
## Rectangle area:
- входные данные a, b
- выходные данные a * b - площадь прямоугольника
- Пример:
  - area(5, 6) == 30;
## Rectangle perimetr:
- входные данные a, b
- выходные данные 2 * (a + b) - периметр прямоугольника
- Пример:
  - perimetr(5, 6) == 22;
## Triangle area:
- входные данные a, h
- выходные данные a * h / 2 - площадь треугольника
- Пример:
  - area(5, 6) == 15;
## Rectangle perimetr:
- входные данные a, b, c
- выходные данные a + b + c - периметр треугольника
- Пример:
  - perimetr(5, 6, 7) == 18;
# история изменения проекта с хешами комитов
## 8f7c634 (HEAD -> new_feature_465554) files with descriptions
## 5c84ff5 triangle and right rectangle
## 06ae831 rectangle.py was added
## d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
## 8ba9aeb L-03: Circle and square added