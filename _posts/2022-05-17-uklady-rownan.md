---
title: Układy Równań
author: cheryx
date: 2022-05-17 18:46:00 +0200
categories: [Matematyka]
tags: [matematyka, uklady]
render_with_liquid: false
math: true
---

# Czym jest układ równań?

Układ równań jest to układ składający się z dwóch lub więcej równań.[^uklady] Przykładami równań są:

$$\begin{cases}
    2x+y=6 \\
    3x+7y=9 \\
\end{cases}$$

$$\begin{cases}
    4x-y=2 \\
    -x+y=5 \\
\end{cases}$$

## Równanie pierwszego stopnia

Obecnie obowiązuje nas równanie pierwszego stopnia z dwoma niewiadomymi, można takie równanie zapisać w następujący sposób:

$$ax+by=c$$

## Rozwiązanie równania

Rozwiązanie równania to para liczb, która po podstawieniu do równania spełnia równanie. Na przykład dla równania
$$\begin{cases}
    2x+y=6 \\
    3x+7y=9 \\
\end{cases}$$ będzie to para liczb $x = 3, y = 0$.

# Metody rozwiązywania równań

> W poleceniu może być wskazana metoda rozwiązania równania.
{: .prompt-warning }

## Metoda graficzna

Metoda graficzna polega na narysowaniu układu obu równań, zwykle te równania mają wzór funkcji liniowej więc na układzie współrzędnych powinny być 2 proste.

$$\begin{cases}
    y=x+2 \\
    2y+2x=-8 \\
\end{cases}$$

Najpierw należy przekształcić równanie do postaci $y=ax+b$

$$\begin{cases}
    y=x+2 \\
    y=-x-4 \\
\end{cases}$$

Teraz można narysować układ współrzędnych.

![1](https://user-images.githubusercontent.com/58445363/169099881-5a8cb295-bf28-4b2b-a8ac-46ca9b4ea922.png)

Punkt przecięcia prostych to punkt, który spełnia równanie, w tym przypadku jest to punkt $(3, 0)$. Dlatego rozwiązaniem równania jest $x=3, y=0$.

> Jeśli kreski są równoległe, to jest to `równanie sprzeczne`, a jeśli są w tym samym miejscu, to jest to `równanie tożsamościowe`.
{: .prompt-tip }

## Metoda podstawiania

Metoda postawiania polega na przekształceniu jednego równania do postaci gdzie zmienna $x$ lub $y$ jest tylko po jednej stronie równania.

Przykład przekształcania równania:

$$\begin{cases}
    4x-y=2 \\ 
    -x+y=-5 |*-1\\
\end{cases}$$

$$\begin{cases}
    4x-y=2 \\ 
    x-y=5 |+y \\
\end{cases}$$

$$\begin{cases}
    4x-y=2 \\ 
    x=5+y \\
\end{cases}$$

Jeśli mamy taką forme, to w drugim równaniu można za zmienną (w tym przypadku $x$) podstawić resztę równania.

$$\begin{cases}
    4(5+y)-y=2 \\ 
    x=5+y \\
\end{cases}$$

$$\begin{cases}
    20+4y-y=2 \\ 
    x=5+y \\
\end{cases}$$

$$\begin{cases}
    3y=-18 \\ 
    x=5+y \\
\end{cases}$$

$$\begin{cases}
    y=-6 \\ 
    x=5+y \\
\end{cases}$$

Mamy już obliczoną zmienną $y$, więc możemy z łatwością obliczyć $x$.

$$\begin{cases}
    y=-6 \\ 
    x=5-6 \\
\end{cases}$$

$$\begin{cases}
    y=-6 \\ 
    x=-1 \\
\end{cases}$$

> Kolejność obliczania zmiennych jest dowolna, najpierw można obliczyć $x$, a potem $y$.
{: .prompt-tip }

## Metoda przeciwnych współczynników

Metoda przeciwnych współczynników polega na sprowadzeniu obu równań do postaci, gdzie jeden współczynnik jest przeciwny drugiemu. Na przykład w równaniu pierwszym występuje $-5x$, a w drugim $5x$.

Przykład sprowadzenia równania do odpowiedniej formy:

$$\begin{cases}
    3x-2y=13 | *4 \\ 
    4x+5y=2 |*(-3)\\
\end{cases}$$

$$\begin{cases}
    12x-8y=52\\
    -12x-15y=-6\\
\end{cases}$$

Jeśli mamy taką forme, to dodajemy obie strony równania do siebie, przy czym eliminujemy jedną ze zmiennych

$$-23y=46$$

$$y=-2$$

[^uklady]: [Informacje o układach równań](https://en.wikipedia.org/wiki/System_of_linear_equations)