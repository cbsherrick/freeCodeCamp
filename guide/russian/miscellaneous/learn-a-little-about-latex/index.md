---
title: Learn a Little About Latex
localeTitle: Узнайте немного о латексе
---
LaTeX предназначен для производства технической и научной документации. Вы можете создавать матрицы, массивы или некоторые другие математические функции.

`$$ (latex language) $$`

Вы можете вставлять Latex в GitterIM. Примеры:

## массив
```
$$\begin{array} {cc} 
 arr11 & arr12\\ 
 arr21 & arr22\\ 
 \end{array}$$ 
```

## матрица
```
$$\begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$$ 
```

## форматирование
```
$$\huge\textstyle\color{#F00}{BigRed}\small\textstyle\color{#0F0}{SmallGreen}$$ 
```

[Поддержка функций](https://github.com/Khan/KaTeX/wiki/Function-Support-in-KaTeX)

## Детали

[KaTeX Github Repo](https://github.com/Khan/KaTeX) LaTeX - высококачественная система набора; он включает в себя функции, предназначенные для производства технической и научной документации. LaTeX является стандартом де-факто для связи и публикации научных документов. Его преимущества заметны в длинных документах, таких как книги, документы или тезисы.

Gitter использует Katex (пользовательская реализация LaTeX), и его можно использовать, вводя следующий код:
```
$$\begin{array} {cc} 
 item11 & item12\ 
 item21 & item 22\ 
 \end{array} 
 $$ 
```

Текст:

*   `$$\huge\textstyle{some text}$$` -> $$ \\ огромный \\ textstyle {some text} $$
*   `$$\color{#F90}{some text}$$` -> $$ \\ color {# F90} {some text} $$