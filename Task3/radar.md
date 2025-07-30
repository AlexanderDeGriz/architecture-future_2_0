
|**Домен**|**Adopt**|**Trial**|**Assess**|**Hold**|
| :-: | :- | :- | :- | :- |
|Медицинский|MongoDB,FastAPI|FHIR (стандарт обмена мед. данными),MLflow|Kubeflow,S3 Glacier (архивация)|Power Builder UI|
|Финансовый|PostgreSQL,Java|Spring Boot,gRPC|Apache Flink|Legacy SOAP-сервисы|
|Аналитика|Qlik Sense,Kafka|Snowflake,dbt|ClickHouse|Power BI (legacy),Apache Camel|
|Инфраструктура|Docker,AWS/GCP| Kubernetes,Terraform|Service Mesh (Istio)|Физические серверы|


<br><h2>Обоснование ключевых изменений</h2>

1. Переход с SQL Server 2008 → PostgreSQL:
Почему: Устаревшая СУБД не поддерживает современные аналитические нагрузки.
Преимущества: Горизонтальное масштабирование, встроенная поддержка JSON.

2. Замена Power BI → Qlik Sense:
Почему: Qlik Sense лучше подходит для ассоциативной аналитики и самообслуживания.
Преимущества: Скорость работы с большими данными, AI-подсказки.

3. Внедрение Kafka вместо Apache Camel:
Почему: Event-driven архитектура для реального времени.
Преимущества: Масштабируемость, отказоустойчивость.