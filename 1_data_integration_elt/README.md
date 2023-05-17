# Data Integration: ELT

<!-- 
Рассмотрим классификацию основных источников данных для аналитики и их отличительные особенности.
Выясним отличие принципов ETL и ELT, структурированных и неструктурированных данных. 
Научимся подключаться и вычитывать исходные данные, запрашивать ответы от внешних провайдеров через REST API, настраивать потоковую репликацию данных в Хранилище. 
Проанализируем основные сервисы и инструменты, используемые для этого класса задач.
 -->

## Databases for Analytics: key principles
<!-- (Teaser) Key slide -->
  
- Massively Parallel Processing
- Columnar storage and compression
- Data layout: clustering, partitioning, sorting

<!-- 
Цели занятия:
- Изучить принципы работы аналитических СУБД
- Привести примеры конкретных СУБД, проанализировать сходства и различия

Краткое содержание:
- MPP-базы данных и shared-nothing архитектура
- Колоночное хранение данных и компрессия
- Сегментация и партицирование
- Особенности нагрузки на аналитические СУБД

Результаты:
- Использование сильных сторон аналитических СУБД в проектах
- Выбор оптимального движка под конкретные потребности и задачи бизнеса
- Изучение основных и дополнительных материалов занятия
 -->

## Handling Data Sources
<!-- (Teaser) Key slide -->

- Overview of a company's data sources
- Addressing the key properties of data: volume, frequency, schema evolution
- Data formats: CSV, JSON, AVRO, PARQUET, ORC

<!-- 
Цели занятия:
- Изучить особенности различных источников данных: подключение, формат, типы данных, ограничения
- Классифицировать источники на примерах: PostgreSQL, S3, Yandex.Metrika, REST API (Exchange rates)

Краткое содержание:
- Структурированные и неструктурированные данные
- Рассмотрение ключевых свойств данных: объем, частота, эволюция схемы
- Форматы данных: CSV, JSON, AVRO, PARQUET, ORC
- Чтение из базы напрямую / лога WAL / REST

Результаты:
- Изучение основных и дополнительных материалов занятия
- Анализ источников данных на текущем месте работы
 -->


## Developer tools 101: IDE, Terminal, Docker, Codespaces, Terraform
<!-- (Teaser) Key slide -->

- Organizing a convenient modern Dev Env
- Version control, Shell, Containers basics
- Interacting with Cloud providers and deploying Infrastructure

<!-- 
Цели занятия:
- Организовать удобную современную среду разработки
- Иметь навыки работы с облачными провайдерами и инфраструктурой
- Продемонстрировать полученные знания на практическом примере

Краткое содержание:
- IDE: VS Code, Command palette, keyboard shortcut extensions
- Terminal: Z-shell, shell commands basics
- Version control basics (git), Docker essentials
- Yandex.Cloud CLI, Terraform, Github Actions, Github Codespaces

Результаты:
- Имеются базовые представления о разнообразных инструментах в курсе и их назначении
- Получены все необходимые знания для быстрого старта в выполнении практических заданий
- Все последующие практические работы курса выполняются в удобной среде
 -->

## 🚀 Lab: [Setting up Airbyte Data Pipelines](https://github.com/kzzzr/airbyte_lab)
<!-- (Teaser) Key slide -->

- Understanding ETL to ELT transition
- SaaS (Fivetran, Stitch, Hevo) vs. Self-managed (Airbyte, Meltano, Singer, Nifi)
- Setting up Integration pipelines with Airbyte
- Sync modes: Incremental, Full-load, Deduped history


<!-- 
Цели занятия:
- Понять различия в подходах ETL и ELT
- Оценить выбор решения с точки зрения критериев: стоимость, сопровождение, развитие, масштабируемость
- Научиться делать выгрузки своими силами: RDBMS, S3/HDFS, REST API, Webhooks

Краткое содержание:
- Трансформация из ETL в ELT
- SaaS (Fivetran, Stitch, Hevo) vs. Self-managed (Airbyte, Nifi, Singer)
- Организация регулярных выгрузок с Airbyte

Результаты:
- Принятие решения об использовании инструментов для выгрузки данных
- Изучение основных и дополнительных материалов занятия

Домашнее задание:
- 🚀 Lab: [Setting up Airbyte Data Pipelines](https://github.com/kzzzr/airbyte_lab)

 -->
