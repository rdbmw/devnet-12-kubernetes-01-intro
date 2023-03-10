
## Задача 1: Установить Minikube

### Вопрос 
Для экспериментов и валидации ваших решений вам нужно подготовить тестовую среду для работы с Kubernetes. Оптимальное решение — развернуть на рабочей машине Minikube.

### Ответ
Установку производил на локальную машину

![Скриншот](src/Task1_1.png)

## Задача 2: Запуск Hello World

### Вопрос 
После установки Minikube требуется его проверить. Для этого подойдет стандартное приложение hello world. А для доступа к нему потребуется ingress.

- развернуть через Minikube тестовое приложение по [туториалу](https://kubernetes.io/ru/docs/tutorials/hello-minikube/#%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BB%D0%B0%D1%81%D1%82%D0%B5%D1%80%D0%B0-minikube)
- установить аддоны ingress и dashboard

### Ответ

Тестовое приложение
![Скриншот](src/Task2_1.png)

![Скриншот](src/Task2_2.png)

Установка аддонов
![Скриншот](src/Task2_3.png)

![Скриншот](src/Task2_4.png)

## Задача 3: Установить kubectl

### Вопрос 

Подготовить рабочую машину для управления корпоративным кластером. Установить клиентское приложение kubectl.
- подключиться к minikube 
- проверить работу приложения из задания 2, запустив port-forward до кластера

### Ответ

port-forward до кластера

![Скриншот](src/Task3_1.png)

![Скриншот](src/Task3_2.png)

![Скриншот](src/Task3_3.png)