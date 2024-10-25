<div align="center">
University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FTMI](https://ftmi.itmo.ru/)

Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/) 

Year: 2024/2025

Group: U4225

Author: Pogodin Anton Igorevich

Lab: Lab2

Date of create: 25.09.2024

Date of finished: 2Х.09.2024


**Ход работы**

Создал Cloud Run из представленного дефолтного сервиса Hello.
![image](https://github.com/user-attachments/assets/b7adb69a-1a76-40fa-8663-724e2e8e6f84)


Перешел по ссылке предоставленной Cloud Run, протестировал сервис.
![image](https://github.com/user-attachments/assets/dcda5f6f-3dd1-4a61-bd84-577c5af047b7)

После этого был успешно развернут образ контейнера на Cloud Run.


Перешел в разделы логи и метрики, проанализировал их.
![image](https://github.com/user-attachments/assets/64974f12-60b0-4a7e-ba16-439574927710)
 Логи показывают входные запросы, а также ответы, информацию о HTTP-методах, статусы ответов и временные метки. Также могут быть показаны ошибки и информация об использовании ресурсов. В данном случае сервис hello-rusakova был успешно создан и обработка запросов выполняется корректно, с положительными ответами на запросы к различным ресурсам.

Метрики
Мы видим такие метрики как: количество запросов, время выполнения, использование памяти, использование CPU, число экземпляров,количество ошибок и исключений, пропускная способность. Так как метрики завязаны на времени, метрики оценивались примерно через 30 минут после развертывания образа контейнера. Как мы видим, метрики демонстрируют действительную ситуацию на настоящий момент.

![image](https://github.com/user-attachments/assets/2ea7402d-0af2-4eba-88b3-4d5736898175)
![image](https://github.com/user-attachments/assets/e5de519f-8e51-4b42-9b48-ac0feebdf61f)
![image](https://github.com/user-attachments/assets/35360685-bb7b-4638-8cd5-e28062cb0b61)
![image](https://github.com/user-attachments/assets/571c15bb-a65c-423b-a996-f57b2d997ba3)
![image](https://github.com/user-attachments/assets/b2b433f2-6b3c-42b9-a1c9-34abb6aae211)


Был изменен Cloud Run - порт изменен на 8090.
Порты 8080 и 8090 являются стандартными портами, которые могут использоваться для обмена данными через протокол HTTP. В большинстве случаев разница между ними связана с тем, какие приложения или службы используют эти порты.
Обычно порт 8080 используется как альтернатива для стандартного порта 80 (обычно используемого для HTTP), когда уже есть другое приложение, занявшее порт 80. Поэтому можно сказать, что порт 8080 является альтернативным HTTP-портом.
На другой стороне, порт 8090 может использоваться для различных целей, и обычно нет стандартного назначения для него. Этот порт может быть выбран для конкретного приложения или службы в зависимости от конфигурации и настроек.
Таким образом, разница между портами 8080 и 8090 в основном заключается в том, как они применяются в конкретных сценариях и конфигурациях сети.



![image](https://github.com/user-attachments/assets/1ce062a4-12bd-41e2-b2f3-91067d7f5ef7)

вот тут трафик меняем

![image](https://github.com/user-attachments/assets/ca6b3dab-638c-4c91-961d-0101653d8337)
![image](https://github.com/user-attachments/assets/5a304289-f51f-4d88-a327-51238836016c)
![image](https://github.com/user-attachments/assets/c5a2bca9-ed14-432a-94bf-fad3c7a15382)

![image](https://github.com/user-attachments/assets/d15b2a94-92d0-46ad-a38a-b3e4a8dbed01)










Измените ваш Cloud Run, поменяв порт на 8090, посмотрите что произойдет. Попробуйте попереключать трафик между версиями, сравните результаты работы.

Удалить за собой все созданные сервисы, написать отчет с использованием скриншотов.

![my-pic1./pic1.jpg](/lab1/pic1.png)
THE END
</div>
