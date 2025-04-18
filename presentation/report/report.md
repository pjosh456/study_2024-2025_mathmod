---
## Front matter
title: "Доклад"
subtitle: "Зависимость от пути (Path Dependence)"
author: "Алади Принц Чисом"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

## Введение

**Цель работы**

Изучить механизм зависимости от пути как вероятностной модели, проанализировать её особенности, математическое описание и практические примеры проявления в различных областях знаний.

**🎯 Задачи работы:**

1. **Дать определение**  
2. **Рассмотреть математическую модель**
3. **Проанализировать особенности** 
4. **Привести практические примеры**  
5. **Представить наглядные схемы и иллюстрации**
6. **Сформулировать выводы** 

## Определение
Зависимость от пути — это концепция, которая играет важную роль в теории вероятностей и математической статистике. Она описывает процессы, в которых текущее состояние или будущее развитие системы зависит от её прошлого — от того, какой путь она уже прошла. Эта идея широко применяется в различных областях: от экономики до физики и биологии.

## Основная идея

Зависимость от пути — это разновидность **модели с урнами**, где:

- В урне находятся шары разного цвета.
- При каждом шаге вытягивается шар, и его цвет запоминается.
- Выбор цвета в будущем **зависит от того, какие цвета вытягивались раньше**.

Таким образом, процесс не является полностью случайным: **предыдущие события влияют на вероятность будущих событий**.

Пример:
Если на начальных шагах чаще вытягивались синие шары, в дальнейшем они могут вытягиваться с ещё большей вероятностью — система "закрепляется" на этом пути.

## Особенности

- **Историческая зависимость**: выборы, сделанные ранее, определяют будущее развитие системы.
- **Долгосрочное равновесие** зависит от начальных условий и ранних событий.
- Система может прийти к совершенно разным результатам в зависимости от начальных случайных флуктуаций.

## Примеры в реальной жизни

1. **Технологии**: стандарт QWERTY-клавиатуры стал доминирующим, хотя изначально он не был самым эффективным.
2. **Экономика**: фирмы продолжают использовать "устаревшие" решения из-за вложенных ранее инвестиций (эффект блокировки).
3. **Научные теории**: одни направления получают развитие, другие — теряются, из-за ранних случайных успехов.

## Математическая модель

Один из классических примеров — **модель Поля с урнами**:

- В начале есть, скажем, 1 красный и 1 синий шар.
- Каждый раз вытягивается шар, затем **возвращается обратно вместе с ещё одним шаром того же цвета**.
- Вероятность вытянуть определённый цвет накапливается: чем больше раз вытягивался этот цвет, тем выше вероятность, что он будет вытянут снова.

Эта модель иллюстрирует эффект "самоусиливающейся вероятности".


## Долгосрочное поведение

- Система может стабилизироваться в определённом состоянии.
- Но **какое именно это будет состояние — зависит от начальной траектории**.
- Это означает, что **равновесие не обязательно является оптимальным** — оно может быть "случайным" результатом ранних выборов.

## Выводы

Зависимость от пути — мощная концепция, объясняющая, почему одни системы стабилизируются на определённых траекториях, несмотря на наличие более выгодных альтернатив. Это явление встречается повсеместно: от случайных процессов до исторических и социальных решений.

Понимание этой зависимости позволяет лучше анализировать поведение сложных систем и предсказывать их возможные сценарии развития.


## Список литературы{.unnumbered}

1. [Wikipedia: Path Dependence](http://en.wikipedia.org/wiki/Path_dependence)

2. **Arthur, W. Brian** (1989). *Competing Technologies, Increasing Returns, and Lock-In by Historical Events.*  
   → Журнал: *The Economic Journal*, Vol. 99, No. 394, pp. 116–131.  
   🔗 [JSTOR link](https://www.jstor.org/stable/2234208)  
   *Классическая статья, объясняющая, как исторические события могут закреплять неэффективные технологии.*

3. **David, Paul A.** (1985). *Clio and the Economics of QWERTY.*  
   → Журнал: *The American Economic Review*, Vol. 75, No. 2, pp. 332–337.  
   🔗 [JSTOR link](https://www.jstor.org/stable/1805621)  
   *Исследование того, как клавиатура QWERTY стала стандартом из-за исторических случайностей.*

4. **Pierson, Paul** (2000). *Increasing Returns, Path Dependence, and the Study of Politics.*  
   → Журнал: *American Political Science Review*, Vol. 94, No. 2, pp. 251–267.  
   🔗 [Cambridge link](https://doi.org/10.2307/2586011)  
   *Переосмысление зависимости от пути в социальных и политических системах.*

5. **Mahoney, James** (2000). *Path Dependence in Historical Sociology.*  
   → Журнал: *Theory and Society*, Vol. 29, pp. 507–548.  
   🔗 [Springer link](https://doi.org/10.1023/A:1007113830879)  
   *Анализ зависимости от пути в исторической и социологической перспективах.*

::: 
:::
