# Задание 2 Перемножение матриц

## Дедлайн: 12 апреля

На вход подаются две матрицы `A` и `B`. Можно считать, что их размерности кратны длине блока. Необходимо посчитать их произведение.

### Особенности реализации

1. Постарайтесь использовать shared память для подсчета произведения внутри блока.
2. Замерьте производительность по сравнению с реализацией [наивной](/CUDA/03.5-matrix-multiplication-example)
3. Попробуйте выяснить, имеются ли при вычислении произведения банк-конфликты и попробуйте их разрешить, если они есть.
Среднее значение должно быть приблизительно равно `a + c`.
