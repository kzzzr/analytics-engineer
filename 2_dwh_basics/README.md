# DWH Basics

<!-- 
Рассмотрим современные СУБД, используемые для анализа больших данных и ключевые принципы их функционирования. 
Изучим концепцию Хранилища Данных и вопросы, на которое оно призвано отвечать.
Познакомимся с dbt – широко популярный мультитул для работы с DWH, позволяющий выстраивать работу в соответствии с лучшими практиками.
 -->

## DWH modeling basics
<!-- (Teaser) Key slide -->
  

<!-- - historical approaches overview
- normalization / denormalization
- basic modeling principles -->


<!-- 
Цели занятия:

Краткое содержание:

Результаты:

 -->


## Getting familiar with dbt (data build tool)

<!-- - dbt introduction (jaffle shop)
- key features
- Modular data modeling: Transform raw data into human-usable metrics
- Dependency management: Layer your models with the ref() function
- Clear project structure: express your data warehouse design in terms of sources, staging models and marts -->

## 🚀 Lab: [DWH powered by Clickhouse and dbt](https://github.com/kzzzr/dbt_clickhouse_lab)

<!-- - Lab: DWH powered by Clickhouse and dbt
- dbt: project, adapter, resource configs; dbt CLI (commands)
- materialization types (+ incremental)
- dbt DAG, refs -->

## Data Testing and Documenting

<!--
- dbt: tests (data quality)
- dbt: node selection syntax
- dbt docs: Define key fields. Dig into the field + table descriptions annotated by your collaborators
- Examine data lineage
- Explore source freshness
- Track downstream applications (exposures)
 -->
