# Тестовое задание на позицию "Стажёр во frontend разработку Дзена"

ссылка на описание вакансии: https://yandex.ru/jobs/vacancies/interns/intern_frontdev_zen/



## Оригинальная постановка задачи

	
Для того, чтобы мы могли лучше познакомиться с вашим уровнем знаний, выполните задание на JavaScript.

Дана доска размером M × N клеток. Клетка может находиться в одном из двух состояний: 1 — живая, 0 — мёртвая. Каждая клетка взаимодействует с восемью соседями. Правила таковы:

- Живая клетка, у которой меньше двух живых соседей, погибает.

- Живая клетка, у которой два или три живых соседа, выживает.

- Живая клетка, у которой больше трёх живых соседей, погибает.

- Мёртвая клетка, у которой три живых соседа, возрождается.

Напишите программу, которая будет:
— случайным образом генерить стартовое состояние;
— уметь получать его из файла (способ выбирается через параметры запуска в консоли);
— каждую секунду выводить в консоль новое состояние доски.

## Запуск

Требуется установленный `node`  

1. Проверьте наличие файла настроек config.json
2. Выполните
    1. Для случайной генерации игрового поля  
    `node script.js random`  
    Также вы можете указать ширину и высоту игрового поля, например:  
    `node script.js random 50 30`
    2. Для получения игрового поля из csv-файла  
    `node script.js config.csv`



