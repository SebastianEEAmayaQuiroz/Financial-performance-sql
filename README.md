# Financial-performance-sql
Análisis de ROI y Margen Bruto por país con SQL y Excel. 6 mercados internacionales.
[Proyecto 3_ Análisis del desempeño financiero con SQL - Resumen ejecutivo .xlsx](https://github.com/user-attachments/files/26696082/Proyecto.3_.Analisis.del.desempeno.financiero.con.SQL.-.Resumen.ejecutivo.xlsx)
# 💰 Análisis de Desempeño Financiero por País — SQL + Excel

**Herramientas:** SQL · Excel Avanzado · Power Query  
**Tipo de análisis:** Business Intelligence · KPIs Financieros · ROI · Análisis de Rentabilidad  
**Dataset:** Ingresos, costos operativos y costos de campañas por país (6 mercados internacionales)

---

## 🎯 Objetivo de negocio

Evaluar el desempeño financiero de una empresa con presencia en 6 países, analizando la rentabilidad real (Margen Bruto y ROI de campañas) para identificar en qué mercados conviene aumentar la inversión y en cuáles optimizar costos.

---

## 🔧 Técnicas aplicadas

- **SQL:** consultas de agregación para calcular Beneficio Bruto, Margen % y ROI % por territorio
- **KPI 1 — Margen Bruto:** `Beneficio Bruto / Ingresos × 100` → mide eficiencia operativa
- **KPI 2 — ROI de Campañas:** `Beneficio Bruto / Costo de Campañas × 100` → mide retorno sobre inversión publicitaria
- **Análisis de sensibilidad:** simulación del impacto de aumentar 50% el gasto en campañas sobre el ROI por país
- **Dashboard Excel:** tabla comparativa con formato condicional por país y territorio

---

## 📈 Resultados clave

| País | Ingresos | Beneficio Bruto | Margen % | ROI % |
|---|---|---|---|---|
| United States | $3,353,939 | $1,454,468 | 43.37% | **75.75%** ✅ |
| Australia | $2,532,003 | $1,057,045 | 41.75% | 49.16% |
| United Kingdom | $1,189,636 | $508,128 | 42.71% | 22.05% |
| Germany | $1,071,460 | $460,165 | 42.95% | 20.31% |
| France | $924,316 | $396,519 | 42.90% | 17.96% |
| Canada | $710,205 | $317,879 | **44.76%** | 17.43% ⚠️ |

### 💡 Insights accionables

1. **United States** es el mercado más rentable: genera el mayor ingreso con un costo de campaña relativamente moderado, resultando en el ROI más alto (75.75%). Prioridad de inversión.
2. **Canada** tiene el margen bruto más alto (44.76%) pero el ROI más bajo (17.43%): el alto costo de campañas está erosionando la rentabilidad. Oportunidad de optimización publicitaria.
3. **France y Canada:** reducir el costo de campañas podría incrementar el ROI significativamente sin sacrificar volumen de ventas.
4. **Simulación de +50% en campañas:** reduciría el ROI promedio en ~33%; el impacto más severo recaería en France y Canada, haciendo inviable la inversión sin un aumento paralelo en ventas.

---

## ❓ Preguntas analíticas respondidas

**¿Cuál es la diferencia entre Margen Bruto y ROI?**  
El Margen mide qué porcentaje de los ingresos queda como beneficio después de costos operativos directos. El ROI mide la rentabilidad específica sobre la inversión en campañas de marketing.

**¿Por qué Estados Unidos tiene el ROI más alto?**  
Genera el mayor ingreso ($3.35M) con un costo de campaña moderado ($1.92M), convirtiendo su inversión publicitaria en ventas de manera más eficiente que cualquier otro mercado.

---

## 📁 Archivos en este repositorio

```
financial-performance-sql/
├── Proyecto_3_Analisis_Desempeno_Financiero_SQL.xlsx   # Dashboard y análisis completo
└── README.md
```

---

*Proyecto desarrollado durante el Bootcamp de Análisis de Datos (2025) · [@SebastianEEAmayaQuiroz](https://github.com/SebastianEEAmayaQuiroz)*
