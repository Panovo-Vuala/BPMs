# 📊 Dashboard Buenas Practicas Manufactura - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a Sharepoint, orientado al análisis de los resultados de las evaluaciones de Buenas Prácticas de Manufactura en planta.

---

## 📌 Objetivo

Diseñar un tablero en Power BI para medir y visualizar los resultados de las evaluaciones de BPMs en planta

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- Power Apps (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
Buenas-Practicas-Manufactura/
├── README.md                               → Descripción general del repositorio
├── pbix/                                   → Archivo PBIX del tablero
├── docs/
│   ├── Medidas_DAX.md                      → Medidas DAX documentadas
│   ├── Columnas_Calculadas.md              → DAX documentadas
│   └── video_tutorial.md                   → Guía de uso del dashboard
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   ├── ModeloDatos.png                     → Captura de las relaciones entre tablas
│   └── preview_app.png                     → Captura de la aplicación
└── ─── modelo_datos.png                    → Relación entre tablas
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/Tablero BPMs.pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

