# Lecturer
Timur Bosenko M. (bosenkotm@mgpu.ru)

Здесь Вы можете найти все материалы по лекциям **`Распределенные системы`**.

Эти лекции дадут Вам краткое введение в то, что называется `распределенными системами`. Обновим знания об основах сетевой модели `ISO`, моделях данных, обработки данных и сравним их с распределенным миром больших данных. После этого углубимся в основы распределенных хранилищ данных и обработки данных, а также в связанные концепции и проблемы надежности, масштабируемости и репликации. По завершению лекционномого модуля, рассмотрим наиболее распространенное программное обеспечение и фреймворки (в основном это экосистема `Hadoop`).

## Программное обеспечение 
   
 `УДАЛЕННОЕ РАБОЧЕЕ МЕСТО`:
   
 - OC **`Ubuntu 20.04`** на базе кластера **`МГПУ`**. Номер РМ студента получить у ведущего лектора. Для работы потребуется клиент [anydesk](  https://anydesk.com/en/downloads/windows).
   
 `ВИРТУАЛЬНАЯ ГОСТЕВАЯ ОС`:
 
 - `D_System_22` [vm - VirtualBox](https://disk.yandex.ru/d/RTZvbDhtfXInMg), в его комплект входит:
    - `VirtualBox-6.1.30-148432-Win.exe` - ПО для разворачивания виртуальной ОС; 
    - `St_work_1.ova` - образ настроенной ОС `Ubuntu 18.04`;
    - `St_work_Hadoop.ova` - образ настроенной ОС `Ubuntu 18.04 + Hadoop`;
    - `login.txt`;
    - `ubuntu-18.04.6-desktop-amd64.iso` - исходный образ ОС.
    
## Темы курсовых проектов
   [2022 ТП-191](https://docs.google.com/spreadsheets/d/1vH9CPcBrWd2rGgXVlzg4eaXm8DNor1-3s4Um11_e2hA/edit?usp=sharing)
   
   Распределение студентов КР:
   - [`ТП-191`](/kp/kp_tp_191.pdf)
   
   ### Регламент написания и защиты курсового проекта.

При защите курсового проекта оцениваются:
- соответствие содержания курсового проекта ее теме;

- полнота и глубина разработки согласно поставленным задачам и цели работы;

- актуальность и новизна;

- степень проработанности литературных источников;

- использование вычислительной и экспериментальной техники при проведении исследований;

- степень самостоятельности при выполнении работы;

- содержание доклада и ответы на вопросы.

[Методические рекомендации к выполнению курсового проекта](https://disk.yandex.ru/i/6_ypM5IRQTfpBA)

## Текущая успеваемость

 [ЦТ-211мз РС 2022](https://docs.google.com/spreadsheets/d/1u9Ho3idAo5v0o7mETkpKlkmCPVmGR6D3_15j_dGVWvU/edit?usp=sharing)
 
 [ТП-191](https://docs.google.com/spreadsheets/d/1NOTUaM9YFTO9QEV7WKDY1KJoWyKj5iSkfVdgChCiw_o/edit?usp=sharing)

## Distributed_systems

- `01-ЛЕКЦИЯ` [Введение](Lectures/01-ЛЕКЦИЯ_Введение.pdf)

- `02-ЛЕКЦИЯ` [Взаимодействие в распределенных системах](Lectures/02-ЛЕКЦИЯ_Взаимодействие%20между.pdf)

- `03-ЛЕКЦИЯ` [HTTP и веб-сервисы](Lectures/03-ЛЕКЦИЯ_HTTP%20и%20веб-сервисы.pdf)

- `04-ЛЕКЦИЯ` [Групповые взаимодействия](Lectures/04-ЛЕКЦИЯ_Групповые%20взаимодействия.pdf)

- `05-ЛЕКЦИЯ` [Непрямое взаимодействие](Lectures/05-ЛЕКЦИЯ_Непрямое%20взаимодействие.pdf)
   - `05-01-ЛЕКЦИЯ` [docker-indirect](/Lectures/05-01-docker-indirect-comm.pdf)
   - `05-02-ЛЕКЦИЯ` [Требования к распределенных систем, моделям данных и доступа](/Lectures/05-02-Requirements_for_DS.pdf)
   - `05-03-ЛЕКЦИЯ` [Непрямое взаимодействие](/Lectures/05-0-lecture_Kafka_intro.pdf)
- `06-ЛЕКЦИЯ` [Обнаружение отказов](Lectures/06-ЛЕКЦИЯ_Обнаружение%20отказов.pdf)

- `07-ЛЕКЦИЯ` [Именование и поиск](Lectures/07-ЛЕКЦИЯ_Именование%20и%20поиск.pdf)

- `08-ЛЕКЦИЯ` [Масштабирование](Lectures/08-ЛЕКЦИЯ_Масштабирование.pdf)

- `09-ЛЕКЦИЯ` [Параллельная обработка](Lectures/09-ЛЕКЦИЯ_Параллельная%20обработка.pdf)

- `10-ЛЕКЦИЯ` [Репликация данных](Lectures/10-ЛЕКЦИЯ_Репликация%20данных.pdf)


## self-study

- `Семинар 1`. [Протокол HTTP/HTTPS](practice/S-1-%20HTTP)
 
- `Семинар 2`. [Multicast](d-zadanie/04-multicast) (Выполнить на базе кластера `МГПУ`).

- `Семинар 3`. [Message queue, RabbitMQ.](/d-zadanie/03-mq) (Выполнить на базе кластера `МГПУ`).

- `Семинар 4-5`. [Kafka.](https://github.com/BosenkoTM/kafka),  [Kafka2.](https://github.com/Zabi82/KafkaLab) [Kafka3.](https://github.com/cblanton45/kafka-labs).

- `Семинар 6`. 

            - [Парадигма Map Reduce - Преподаватель](practice/S-2-09-map-reduce)
             
            - [Парадигма Map Reduce - Студент](https://colab.research.google.com/drive/1-_TOZV0MaRLGaFqHaHP45JznxGC5F4hl?usp=sharing)

- `Семинар 7`. [01_HADOOP администрирование](https://github.com/BosenkoTM/ds_practice/tree/main/exercises/winter_semester_2021-2022/05_hadoop)
  - Решение самостоятельного задания `Семинар 7` [тут](https://github.com/BosenkoTM/ds_practice/tree/main/solutions/winter_semester_2021-2022/05_hadoop)
  - [02_HADOOP сам_задание](/practice/S-3-HADOOP/2.%20Hadoop%20Lab-1.pdf)


## ТЕСТ 1. Распределенные системы.  

`07.10.2022`

[ССЫЛКА ДЛЯ ВХОДА](https://docs.google.com/forms/d/e/1FAIpQLScEjZmp_Fsx2qGEp-KWWR5L8UfUrZs0GmGJIM_Nd3I0nzbuwg/viewform?embedded=true)

- Темы тестирования: Понятие распределенных информационных систем, Основные принципы технологии  «клиент-сервер», 
Модели взаимодействия компонентов РС, Распределенная обработка данных. 
`Глава 1` - `Глава 2` Учебник [Бабичев С. Л](https://urait.ru/book/raspredelennye-sistemy-445188)

## ТЕСТ 2. Распределенные системы. 
[ССЫЛКА ДЛЯ ВХОДА](https://docs.google.com/forms/d/e/1FAIpQLScx-U2XsIRvTkMHWHqbu15K9I9lNxc-n2NCgK-PiC22B0BTzA/viewform?embedded=true)

`18.11.2022`

- Темы тестирования:  `Глава 9.` Архитектура распределенных систем. + конспект
Учебник [Бабичев С. Л](https://urait.ru/book/raspredelennye-sistemy-445188)
- [Конспект лекций](Lectures/help_test2.pdf)

## Conferences
1. [`XXI конференция молодых исследователей образования  - МГПУ`](https://www.mgpu.ru/event/xxi-konferentsiya-molodyh-issledovatelej-obrazovaniya/).


## Дополнительные материалы
- [Основные понятия Docker](/Lectures/05-01-docker-indirect-comm.pdf) 
- [Docker help](/Lectures/docker_help.pdf) 

### Основная литература

1.	Бабичев, Сергей Леонидович. Распределенные системы [Электронный ресурс]: учеб. пособие для вузов / С. Л. Бабичев, К. А. Коньков. – М. : Юрайт, 2020. https://urait.ru/book/raspredelennye-sistemy-457005 

2.	Распределенные системы: учебное пособие для студентов, обучающихся по направлению подготовки 38.03.05 Бизнес-информатика / [авт.-сост. А.В. Демина, О.Н. Алексенцева]. 2018. – 108 с. Demina_Aleksenzeva.pdf — Яндекс.Диск (yandex.ru)

3.	Клеппман М.Высоконагруженные приложения. Программирование, масштабирование, поддержка. — СПб.: Питер, 2018 — 640 с.

### Дополнительная литература

4.	Austin Parker Distributed Tracing in Practice Instrumenting, Analyzing, and Debugging Microservices, y O’Reilly Media, Inc., 2020
5.	Sigismondo Boschi RabbitMQ Cookbook Packt Publishing 2013

