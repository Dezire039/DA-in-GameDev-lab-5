# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev] 5 Интеграция экономической системы в проект Unity и обучение ML-Agent
Отчет по лабораторной работе #5 выполнил(а):
- Буторина Анна Георгиевна
- РИ211002
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨


## Цель работы
Связать экономическую систему, Unity и TensorBoard, поработав с ними.


## Задание 1
### 
Ход работы:
- Запустила обучение агента и запустила проект в Unity:
<img width="825" alt="2022-12-01 (2)" src="https://user-images.githubusercontent.com/114075427/205103706-dd7f8c37-284a-4655-867f-32e2457f65c7.png">

- Увеличила колличество префабов до 12:

<img width="823" alt="2022-12-01 (5)" src="https://user-images.githubusercontent.com/114075427/205104332-358c0e2c-b7a7-4b55-9635-a0586acff35a.png">

- Установила TensorBoard и получила графики:

![2 (1)](https://user-images.githubusercontent.com/114075427/205111480-08f5a7f5-b83b-42c2-8f93-c12eb00a509a.png)

- Изменила параметр strength на 0.5 (1)
Суммарное вознаграждение изменилось
- Изменила gamma на 0.5 и strength на 0.5 (2)
Политика лучше принимает решения, чем в начальных параметрах
- Изменила learning_rate на 2.0e-4, gamma на 0.5 и summary_freq на 10000 (3)
Суммарное вознаграждение не изменилось, а длина эпизода изменилась (мы сменили параметр)
- Полученные графики: 

![3 (1)](https://user-images.githubusercontent.com/114075427/205109578-323a1069-f422-48d6-838f-93a48d6e9043.png)

(оранжевый цыет - начальные параметры, красный - параметры 1, голубой - параметры 2, синий - параметры 3)
 


## Задание 2
### 
Ход работы: 
- 


## Задание 3
### 
Ход работы:




## Выводы
Я поработала с экономической системой в Unity и с TensorBoard. Вывела в TensorBoard результаты обучения ML-агента.



| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
