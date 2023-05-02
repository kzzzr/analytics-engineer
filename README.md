# Analytics Engineer

WIP Brief overview

https://docs.google.com/spreadsheets/d/1Bo23j4LG43xE5IBUTP1lQ_RmbJEwLqifP2JVQdO8vf4/edit#gid=1769766247

## Labs

- [Setting up Airbyte Data Pipelines Labs](https://github.com/kzzzr/airbyte_lab)
- [DWH powered by Clickhouse and dbt](https://github.com/kzzzr/dbt_clickhouse_lab)
- [Data Vault powered by dbtVault and Greenplum](https://github.com/kzzzr/dbtvault_greenplum_demo)


## Talks

- (YouTube) 2022-11 [Аналитика продуктивности команд разработки на основе данных Github](https://www.youtube.com/watch?v=Y_xGZzI5sNI)
- (YouTube) 2022-10 [Работа с ГЕО-данными в DWH: координаты, зоны, агрегация](https://www.youtube.com/watch?v=IS5PIOhXLdk)
- (YouTube) 2022-05 [Extract - Load как сервис и как собственное решение. Поиск баланса и дзен. День 1](https://www.youtube.com/watch?v=CR32LFCgtGE)
- (YouTube) 2022-05 [Extract - Load как сервис и как собственное решение. Поиск баланса и дзен. День 2](https://www.youtube.com/watch?v=dSm2kDsRhOI)
- (YouTube) 2022-04 [SQL для аналитики — прикладные задачи и подходы к их решению](https://www.youtube.com/watch?v=UIJjXBVWONo)
- (YouTube) 2022-04 [End-to-end решение для аналитики на примере источника MaestroQA](https://www.youtube.com/watch?v=ImchI3LeHeg)
- (YouTube) 2021-11 [Полуструктурированные данные в Аналитических Хранилищах: Nested JSON + Arrays](https://www.youtube.com/watch?v=lBwmLnMwfl0)
- (YouTube) 2021-07 [Configuring Slim CI: легковесные интеграционные тесты для Хранилища Данных](https://www.youtube.com/watch?v=yfMWiyKpUkQ)
- (YouTube) 2021-06 [Лучшие практики в работе с Качеством Данных (Data Quality)](https://www.youtube.com/watch?v=j5V36kztvEI)

## Data Integration: ELT

Рассмотрим классификацию основных источников данных для аналитики и их отличительные особенности.
Выясним отличие принципов ETL и ELT, структурированных и неструктурированных данных. 
Научимся подключаться и вычитывать исходные данные, запрашивать ответы от внешних провайдеров через REST API, настраивать потоковую репликацию данных в Хранилище. 
Проанализируем основные сервисы и инструменты, используемые для этого класса задач.

* [Источники данных: классификация и особенности](./data_integration_elt/README.md#инструменты-для-выгрузки-данных-–-1)
    Description
* [Инструменты для выгрузки данных – 1](./data_integration_elt/README.md#инструменты-для-выгрузки-данных-–-1)
    Description
* [Developer tools 101: IDE, Terminal, Docker, Codespaces, Terraform]()
    Description

TO BE:
- OSS tools: Airbyte (Meltano, Singer)
- Sync modes: incremental, full-load, deduped history
- How to implement your own ELT into target
- Sources and target types (+ S3 file formats)

## DWH Basics

- Занятие 4. Принципы построения DWH.
- Занятие 5. Аналитические движки (СУБД) для работы с данными.
- Занятие 6. Знакомство с Data Build Tool.
- Занятие 7. DWH powered by Clickhouse and dbt

TO BE:
- basic modeling principles + dbt introduction (jaffle shop)
- analytics engines: key principles
- dbt DAG, refs
- DWH powered by Clickhouse and dbt
- dbt: tests (data quality)
- dbt: project, adapter, resource configs; dbt CLI (commands); materialization types (+ incremental)
- dbt: node selection, 

## DWH Intermediate

- Занятие 8. Оркестрация скриптов и задач – 1.
- Занятие 9. Оркестрация скриптов и задач – 2.
- Занятие 10. Разбор ДЗ – Выгрузка данных веб-счетчика.
- Занятие 11. Data Quality.
- Занятие 12. Вопросы оптимизации производительности.
- Занятие 13. Разбор ДЗ – Конфигурирование и запуск проекта dbt.
- Занятие 14. Data Vault – 1.
- Занятие 15. Разбор ДЗ – Подготовка и установка на расписание DAG выгрузки данных из источников.
- Занятие 16. Data Vault – 2.
- Занятие 17. Data Vault – 3.

TO BE:
- dbt deep dive: jinja (macro showcase), variables, env vars, packages, hooks: https://www.getdbt.com/dbt-learn/lessons/intro-to-jinja/#4
- dbt incremental models: https://www.getdbt.com/dbt-learn/lessons/incremental/#1
- dbt snapshots: https://www.getdbt.com/dbt-learn/lessons/techniques-trade/#18
- dbt: custom schemas, environments (dev, test, prod) target names behaviour (if prod then else)
- Extending with modules: dbt utils showcase
- dbt snapshots
- SQL for analytics
- Advanced modeling with dbtVault
- dbt Cloud vs. dbt Core
- Deployment: Airflow (Prefect, Dagster)

## Business Intelligence foundation

- Занятие 18. BI: Обзор.
- Занятие 19. BI: Deployment.
- Занятие 20. BI: Modeling & Delivering.
- Занятие 21. Разбор ДЗ – Организация детального слоя DWH по методологии Data Vault.
- Занятие 22. Analytics: Базовые аналитические витрины.
- Занятие 23. Analytics: Сквозная аналитика.
- Занятие 24. Разбор ДЗ – Конфигурация и развертывание BI-решения.
- Занятие 25. Analytics: Продвинутые аналитические витрины.

TO BE:
- BI tools overview, purpose, features
- dbt vs. BI (segregation): https://www.getdbt.com/dbt-learn/lessons/dbt-project-design/#74
- BI deployment and configuration (Metbase, Superset)
- Semantic layer: dbt Metrics, Cube.js
- Common analytics patterns: KPI, Retention, Cohorts, GEO
- Marketing analytics showcase

## DWH Advanced toolkit

- Занятие 26. DWH: Advanced topics.
- Занятие 29. DBT: Extending with modules.
- Занятие 28. DWH: Monitoring + Workload management.
- Занятие 27. DWH: External + Semi-structured data.
- Занятие 30. DWH: Reverse-ETL.
- Занятие 31. DWH: Machine Learning capabilities.
- Занятие 32. Разбор ДЗ – Визуализация и дашбординг для аналитических витрин.

TO BE:
- Configuring CI + CD, --state and --defer
- dbt Metadata: logging, dbt Artifacts
- Writing your own dbt module
- External + Semi-structured data
- Reverse ELT, ML capabilities

## Case studies

- Занятие 33. Разбор кейса: end-to-end solution.
- Занятие 34. Разбор ДЗ – Advanced DWH: Configuring CI, dbt modules, External tables.
- Занятие 35. Дальнейшее развитие навыков.

TO BE:
- Recap with showcase (case study)
- Own project (or individual consultation)

## WIP About

About me

Learning course
About platform where course is held
Prerequisites: OS basic knowledge, Docker, ...
