# CHALLENGE-REPOSITORIO-TelecomX
Challenge Telecom X
 # 📊 Análisis de Cancelaciones de Servicio

Este proyecto tiene como objetivo analizar el comportamiento de cancelación de clientes en un servicio de telecomunicaciones, identificando patrones clave y proponiendo estrategias para mejorar la retención y reducir la evasión.

---

## 📌 Objetivos

- Identificar las principales variables que influyen en la cancelación de clientes.
- Visualizar el comportamiento de cancelación por género, tipo de contrato, método de pago, y más.
- Proponer estrategias basadas en datos reales para reducir la tasa de cancelación.
- Documentar hallazgos clave y facilitar la toma de decisiones estratégicas.

---

## 📁 Estructura del proyecto

```plaintext
📦 cancelaciones-clientes/
├── data/                     # Datos originales y procesados (CSV, Excel)
├── notebooks/                # Análisis exploratorio en Jupyter o Colab
├── graphs/                   # Gráficas generadas en PNG
├── src/                      # Funciones auxiliares o scripts Python
├── README.md                 # Este archivo
└── report/                   # Conclusiones y estrategias en PDF o Markdown
---
##📦 Dependencias
pandas

matplotlib

seaborn

jupyter

scikit-learn (opcional, si se usa modelado)

numpy

---

##🧠 Hallazgos clave
Los contratos mensuales tienen mayor tasa de cancelación.

Los clientes con fibra óptica cancelan más que los que usan otros tipos de conexión.

Los pagos automáticos reducen la evasión.

Mayor tiempo de contrato y gasto total están asociados a menor probabilidad de cancelación.

Clientes con cónyuge o dependientes tienden a mantenerse más tiempo.

---

##💡 Recomendaciones estratégicas
Incentivar contratos de fidelización.

Mejorar la calidad del servicio de fibra óptica.

Promover métodos de pago automáticos.

Crear campañas específicas para clientes con mayor riesgo de cancelación.

Implementar programas de lealtad basados en antigüedad y gasto.

---

##❗ Posibles problemas
Algunos registros tienen valores “Desconocido”; se recomienda limpieza y mejora en la recolección de datos.

Es recomendable actualizar el análisis periódicamente si los datos cambian.
