| Fase CRISP-DM              | Cómo se adapta                                               |
| -------------------------- | ------------------------------------------------------------ |
| **Business Understanding** | El churn es un KPI real y crítico en Telco.                  |
| **Data Understanding**     | Las variables permiten análisis exploratorio completo.       |
| **Data Preparation**       | Requiere limpieza básica + codificación + balance de clases. |
| **Modeling**               | Puedes usar regresión, árboles, random forest, XGBoost, etc. |
| **Evaluation**             | Permite medir precisión, recall, matriz de confusión o ROC.  |
# ciencia-de-datos-proyecto-3

📌 1. Relevancia del dataset para un problema real de negocio

El churn (abandono de clientes) es uno de los problemas más importantes en telecomunicaciones, porque:

Adquirir un nuevo cliente cuesta entre 5 y 10 veces más que retener uno existente.

La industria telco tiene altas tasas de competencia, variedad de planes y facilidad de migración.

Pequeñas mejoras en retención generan un gran impacto financiero.

Este dataset representa clientes reales de un proveedor de telecomunicaciones, con la pregunta central:

¿Qué clientes tienen mayor probabilidad de abandonar la compañía y por qué?

Esto lo convierte en un caso fuerte para machine learning aplicado a negocio:

Permite identificar perfiles de riesgo.

Justifica campañas de fidelización.

Ayuda a optimizar ofertas, precios y servicios.

Permite medir impacto financiero (retención vs pérdida).

Conclusión:
✔️ Es totalmente relevante para el análisis predictivo en una empresa real de telecomunicaciones, con impacto directo en ingresos y estrategias comerciales.

📌 2. Calidad y documentación del origen de datos

El dataset proviene de una de las fuentes abiertas más reconocidas: Kaggle.

Calidad del dataset

Puntos que hacen de este dataset una excelente elección:

✔️ a) Buena estructura

Incluye 7043 registros y 21 columnas, suficientes para análisis completo sin ser demasiado grande.

✔️ b) Variables ricas y diversas

Tiene variables categóricas y numéricas que representan:

Datos del cliente

Género

Pareja

Dependientes

Servicios contratados

Internet

Seguridad

Backup online

Telefonía

Televisión

Tenencia de fibra óptica

Información de contrato

Mes a mes

1 año

2 años

Facturación y pagos

Tipo de pago (automático, cheque, tarjeta)

Factura electrónica

Cargos mensuales

Cargos totales

Etiqueta objetivo (churn)

Yes / No

✔️ c) Alta limpieza

No tiene valores faltantes críticos.

Las variables son relativamente consistentes.

El único detalle es que algunas están como texto cuando deberían ser numéricas (por ejemplo, TotalCharges), lo cual se puede corregir fácilmente.

✔️ d) Buena disponibilidad y trazabilidad

El dataset está publicado en múltiples plataformas:

Kaggle (principal)

IBM Sample Data Sets

Repositorios educativos

Esto facilita comprobar su consistencia y origen.

✔️ e) Documentación clara

La descripción oficial incluye:

Definición de cada variable

Contexto: “Customer churn of a telco company”

Explicación del signficado de los servicios contratados

Es un beneficio enorme para un proyecto académico porque no tendrás que inventar definiciones ni suposiciones.
