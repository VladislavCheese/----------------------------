---
marp: false
paginate : true
---
<style>
h1 { 
    font-size: 60px;
    color: Black;
    text-align: center;
    }       
h2 { 
    font-size: 30px;
    color: Black;
    position: relative;
    left: -2.5em;
    top: 8em;
    }

h3 { 
    font-size: 30px;
    color: Black;
    position: relative;
    left: -2.5em;
    top: 7em;
    }

section.titleslide1 h4 {
    font-size: 40px;
    color: Black;
    position: relative;
    left: 0em;
    bottom: 6em;    
}

section.titleslide2 h4 {
    font-size: 40px;
    color: Black;
    position: relative;
    left: 0em;
    bottom: 5.3em;    
}

section.titleslide3 h4 {
    font-size: 40px;
    color: Black;
    position: relative;
    left: 0em;
    bottom: 4.1em;    
}

section.titleslide4 h4 {
    font-size: 40px;
    color: Black;
    position: relative;
    left: 0em;
    bottom: 0em;    
}

section.titleslide5 h4 {
    font-size: 40px;
    color: Black;
    position: relative;
    left: 0em;
    bottom: -1em;    
}

</style>

# Лабораторная работа №2
## Syrov Vladislav 

## НКНбд-01-19

### RUDN University, 2022 Moscow, Russia

---
<!--_class: titleslide1 -->
#### Прагматика выполнения лабораторной работы
* Ознакомление и изучение основ математического моделирования
* Получение навыков визуализации траектории движения
* Озанкомление с новыми инструментами 

---
<!--_class: titleslide2 -->
#### Цель выполнения лабораторной работы
* Научиться решать задачи о погоне с помощью диф. уравнений и графиков
* Визуализация траекторий движения в sciLab
* Научиться выводить уравнения движения через математические формулы

---
<!--_class: titleslide3 -->
#### Задача выполнения лабораторной работы

* Вывести уравнение, которое описывает движение катера

* Построить трактории движения в двух случаях нач. условий

* Найти точки пересечения траекторий в двух случаях

---
<!--_class: titleslide4 -->
#### Уравнение

Решение исходной задачи сводится к решению системы из двух дифференциальных уравнений: 
$$
\begin{equation*} 
  \begin{cases} 
    \frac{\partial r}{\partial t} = v 
    \\
    r \frac{\partial \theta}{\partial t} = \sqrt{21.09} v 
  \end{cases}
\end{equation*}
$$

с начальными условиями 

$$
\begin{equation*}
  \begin{cases}
    \theta_0 = 0 
    \\ 
    r_0 = x_1 
  \end{cases}
\end{equation*}
$$
и
$$
\begin{equation*}
  \begin{cases}
    \theta_0 = -\pi
    \\
    r_0 = x_2
  \end{cases}
\end{equation*}
$$
Исключая из полученной системы производную по t, можно перейти к следующему уравнению:
$$
\frac{\partial r}{\partial \theta} = \frac{r}{\sqrt{21.09}}.
$$
Начальные условия остаются прежними. Решив это уравнение, мы получим траекторию движения катера в полярных координатах.


---
<!--_class: titleslide5 -->
#### Результат

# ![Вывод 1](https://github.com/VladislavCheese/----------------------------/blob/master/lab2/presentation/images/var_1.png "рис.01")

# ![Вывод 2](https://github.com/VladislavCheese/----------------------------/blob/master/lab2/presentation/images/var_2.png "рис.02")

---
# Спасибо за внимание