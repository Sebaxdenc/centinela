# Centinela: detección de fraude en tiempo real para una fintech colombiana

ST1630 Sistemas Intensivos en Datos · Universidad EAFIT · Proyecto final

**Autor:** Sebastian Andres Medina Cabezas (1000317163) · [github.com/Sebaxdenc/centinela](https://github.com/Sebaxdenc/centinela)

**Problema:** los analistas de fraude de *Chiva Pay* (SEDPE ficticia) necesitan una alerta priorizada en menos de 10 s (p95) desde que ocurre una transacción sospechosa (P2P, Bre-B, QR), para retener la cuenta antes de la segunda transferencia del ataque. Además, Riesgo y Cumplimiento (SARLAFT) necesitan un Gold dimensional con datos de máximo 30 min.

**Stack:** Kafka 3.9 (KRaft) · Spark 3.5 Structured Streaming · Delta Lake 3.3 sobre MinIO (Bronze/Silver/Gold) · Cassandra 5.0 (serving) · Airflow 3 · Trino + Superset · Docker Compose.

## Entregable 1

| Artefacto | Ruta |
|---|---|
| Documento (5 secciones + anexos) | `docs/entregable1/e1_centinela.pdf` |
| Diagrama de arquitectura | `docs/entregable1/arquitectura.png` |
| Diagrama editable (draw.io) | `docs/entregable1/arquitectura.drawio` |
