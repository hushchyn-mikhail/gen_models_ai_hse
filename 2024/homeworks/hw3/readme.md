Задание 3: Диффузия, нормпотоки  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hushchyn-mikhail/gen_models_ai_hse/blob/main/2024/homeworks/hw3/HW3.ipynb)


**Дополнение**: 

ТЗ для реализации функции `other_agent_score`: 

Реализуйте функцию, которая принимала бы на вход набор сгенерированных и настоящих объектов,
разбивала на train и test с учетом баланса классов (real и fake объектов), с соотношением 3 к 1,
обучала модель линейной регрессии и градиентного бустинга, которые учились бы отличать настоящие объекты от фальшивых,
после чего выводила бы accuracy score на отложенной выборке у обоих моделей.
