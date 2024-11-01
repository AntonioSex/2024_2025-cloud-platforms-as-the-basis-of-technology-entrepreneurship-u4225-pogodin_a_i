<div align="center">
University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FTMI](https://ftmi.itmo.ru/)

Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 

Year: 2024/2025

Group: U4225

Author: Pogodin Anton Igorevich

Lab: Lab2

Date of create: 30.10.2024

Date of finished: 01.11.2024
</div>

## Описание
Это третья лабораторная работа Исследование Cloud Storage

## Цель работы
Ознакомиться с основными понятиями и принципами работы облачного хранилища, изучат различные модели хранения данных (блок, файл, объектное хранилище), познакомятся с основными сервисами и функционалом, предоставляемым облачными хранилищами.

## Ход работы

1. Выбрал существующий проект, в котором есть соответствующие разрешения
   
2. Создал Cloud Storage bucket - контейнер в Google Cloud Storage (GCS), служащий для организации и хранения объектов в GCS. 

![image](https://github.com/user-attachments/assets/42d3a36b-401a-4612-90bd-f45bf6fdc6b2)


3. Загрузил 4 изображения в Cloud Storage bucket
   
![image](https://github.com/user-attachments/assets/688d0c6d-8b2c-4572-88b9-bf9dbf75cdad)


4. Создал папку с названием "Random people" и переместил файлы туда в пределах бакета (с помощью Move)

![image](https://github.com/user-attachments/assets/8eed4ed2-dea3-4c58-b0bc-ec3a84344a08)


5. Настроил публичный доступ для файлов в настройках приватности

![image](https://github.com/user-attachments/assets/d9a813c0-e807-409e-b4fe-263bd6c89770)

![image](https://github.com/user-attachments/assets/be36d614-f4c5-42a6-9b95-435ff39d23ce)

![image](https://github.com/user-attachments/assets/23151093-d773-4a6d-8a20-113803ee69bb)



6. Создал ссылки на файлы через контекстное меню файла
![image](https://github.com/user-attachments/assets/26273656-43f1-443d-b149-f7dd6c2dd2a3)


https://storage.googleapis.com/pogodinai-bucket/Random%20people/baiden.jpg

https://storage.googleapis.com/pogodinai-bucket/Random%20people/keidzhnicolas.jpg

https://storage.googleapis.com/pogodinai-bucket/Random%20people/netanyahu.webp

https://storage.googleapis.com/pogodinai-bucket/Random%20people/petr1.jpg

Проверил работоспособность ссылок:
![image](https://github.com/user-attachments/assets/1f1a3782-14b1-4e14-b681-15010d5de479)

![image](https://github.com/user-attachments/assets/1bfe1b5a-1692-46a6-a771-533706826a73)

![image](https://github.com/user-attachments/assets/5072cba0-ec60-4274-ba71-d09868ee01b4)

![image](https://github.com/user-attachments/assets/818e3ba2-5131-45ea-b8ec-1b943e9e47d6)

7. Удалил за собой все созданные сервисы

![image](https://github.com/user-attachments/assets/6706ab92-19f9-439d-b9cc-4248f8d98780)


## Выводы
В процессе работы с Google Cloud Storage были достигнуты следующие результаты:

- Создан бакет для хранения файлов с возможностью задания уровня доступа;
- Загружены и структурированы файлы внутри бакета;
- Настроен публичный доступ к файлам, что позволяет легко делиться ссылками;
- Изучены ключевые операции **Cloud Storage**, такие как создание бакета, загрузка файлов, настройка прав доступа и удаление.

Cloud Storage позволяет гибко управлять файлами в облаке, поддерживая как приватные, так и публичные уровни доступа. Благодаря этим возможностям данный сервис отлично подходит для хранения данных любого типа — от часто запрашиваемых до архивных данных, предлагая широкий выбор классов хранения и удобный интерфейс для управления доступом.
