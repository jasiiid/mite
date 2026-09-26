<div align="center">

# 🇧🇴 Guía de trámites Santa Cruz

### Una skill de IA pensada para la vida real.

**Orientación clara para trámites y servicios en Santa Cruz de la Sierra y el departamento de Santa Cruz.**

<br>

[![Skill](https://img.shields.io/badge/AI%20Skill-Hackathon-ff6b35?style=for-the-badge)](#)
[![Ubicación](https://img.shields.io/badge/🇧🇴-Santa%20Cruz%2C%20Bolivia-2ea44f?style=for-the-badge)](#)
[![Idioma](https://img.shields.io/badge/Idioma-Español%20boliviano-181717?style=for-the-badge)](#)

<br>

**[👤 Jasid Morón](https://github.com/jasiiid)**

</div>

---

## 🧭 ¿Qué es?

**Guía de trámites Santa Cruz** es una skill para asistentes de inteligencia artificial diseñada para ayudar a personas **no técnicas** a resolver dudas sobre trámites y servicios cotidianos en Santa Cruz.

La idea es sencilla:

> **Que una persona pueda preguntar qué necesita hacer y recibir una respuesta que realmente pueda utilizar.**

La skill está diseñada para responder de forma breve, ordenada y comprensible, evitando asumir que la persona conoce portales, aplicaciones, instituciones o términos administrativos. fileciteturn0file0L18-L34

---

## 💡 El problema

Buscar información sobre un trámite puede convertirse rápidamente en una mezcla de:

- páginas diferentes;
- instituciones con nombres parecidos;
- información desactualizada;
- direcciones incorrectas;
- requisitos que cambian;
- portales digitales que no todo el mundo sabe utilizar;
- y respuestas demasiado técnicas.

Una IA puede responder rápido.

**Pero responder rápido no significa necesariamente responder bien.**

Esta skill busca introducir una capa de contexto local y reglas específicas para reducir ese problema.

---

## ⚙️ ¿Cómo responde?

La skill estructura las respuestas alrededor de **7 elementos**:

| | La persona recibe |
|---|---|
| 📌 **01** | Qué es el trámite |
| 📄 **02** | Qué necesita llevar |
| 🔢 **03** | Los pasos, en orden |
| 📍 **04** | Dónde hacerlo y cómo llegar desde su zona |
| 💰 **05** | Costos y plazos, únicamente cuando están verificados |
| ❓ **06** | Una duda frecuente |
| 💬 **07** | Una sola pregunta para continuar |

La intención es evitar respuestas interminables y convertir información administrativa en **instrucciones que una persona pueda seguir**. fileciteturn0file0L20-L30

---

## 🧠 ¿Qué aporta la skill?

### Sin contexto local

> “¿Dónde hago mi pasaporte? Me dijeron que es en Indana.”

Una IA podría repetir información antigua o enviar a una ubicación incorrecta.

### Con la skill

La respuesta puede identificar que **Indana no corresponde actualmente a la atención de migración** y orientar hacia la oficina correspondiente, en lugar de repetir el dato sin verificar. fileciteturn0file0L38-L46

---

## 🗺️ Contexto local

La skill está pensada específicamente para **Santa Cruz de la Sierra y el departamento de Santa Cruz**.

Esto significa que el contexto geográfico importa.

En lugar de inventar una ruta genérica, la skill puede pedir algo tan sencillo como:

> **“¿En qué barrio o anillo estás?”**

A partir de ahí, la respuesta puede orientar utilizando dirección y referencias disponibles, en vez de inventar líneas de micro o tiempos de viaje. fileciteturn0file0L40-L46

---

## 📚 Categorías

Actualmente contempla **13 áreas**:

| # | Área |
|---:|---|
| 01 | 🪪 Identidad |
| 02 | 🏢 Negocios |
| 03 | 🚗 Vehículos |
| 04 | 🎓 Estudios |
| 05 | 🎓 Becas |
| 06 | 🏠 Hogar |
| 07 | 🏥 Salud |
| 08 | 💼 Trabajo, SIN y Gestora |
| 09 | 💰 Impuestos municipales |
| 10 | 👨‍👩‍👧 Familia y registro civil |
| 11 | 🛂 Migración |
| 12 | 👴 Adulto mayor |
| 13 | 🎁 Bonos |

Las instituciones y servicios contemplados incluyen, entre otros, **SEGIP, SEPREC, RUAT, UPSA, UPDS, SUS, SERECI, DIGEMIG, DAT, SIN y Gestora**. fileciteturn0file0L49-L63

---

## 🔎 Verificación antes que certeza falsa

Uno de los principios centrales del proyecto es simple:

### Si un dato no está confirmado, no se presenta como confirmado.

La skill utiliza la marca:

```text
POR CONFIRMAR
```

para información que todavía requiere verificación.

También evita inventar:

- ❌ oficinas
- ❌ líneas de transporte
- ❌ montos
- ❌ plazos

Y cuando corresponde, indica que la información debe volver a verificarse el día de la consulta. fileciteturn0file0L43-L48

---

## 🧪 Ejemplos

Puedes probar la skill con preguntas como:

```text
“Quiero abrir un negocio unipersonal,
vivo en el 2º anillo sur.”

“¿Cómo cobro el Juancito Pinto 2026?”

“¿Dónde hago el pasaporte?
Me dijeron Indana.”

“¿Cómo pago el impuesto de mi casa?”
```

La skill también está diseñada para separar solicitudes cuando una persona necesita realizar **varios trámites**, en lugar de mezclar todas las instrucciones en una sola respuesta. fileciteturn0file0L65-L73

---

## 🛠️ Instalación / uso

La skill se encuentra en:

```text
SKILL.md
```

Para utilizarla:

1. Carga `SKILL.md` como skill del asistente.
2. Realiza una pregunta relacionada con alguno de los trámites cubiertos.
3. Cuando la ubicación sea relevante, proporciona la zona, barrio o anillo.
4. Verifica nuevamente montos y plazos cuando la skill indique que deben confirmarse.

---

## 🧩 Filosofía del proyecto

Este proyecto parte de una idea:

> **La IA no debería limitarse a saber cosas.  
> También debería saber cómo explicarlas a una persona real.**

Especialmente cuando esa persona no sabe qué institución buscar, dónde queda, qué documentos necesita o incluso si puede realizar el trámite de manera presencial.

Por eso la skill prioriza **claridad, contexto local y verificación** antes que respuestas largas o aparentar certeza.

---

## ⚠️ Límites

Esta skill **no reemplaza asesoramiento legal profesional ni realiza trámites en nombre de la persona**.

Además, existen instituciones y sedes que todavía requieren confirmación dentro de la propia skill, entre ellas SERECI central, CNS física, MIN-TEPS y CONALPEDIS en Santa Cruz. fileciteturn0file0L82-L84

---

## 👤 Autor

<div align="center">

### Jasid Morón

**Estudiante de Comunicación Social · IA · Gestión de Crisis**

Me interesa la intersección entre **comunicación, inteligencia artificial y resolución de problemas reales**.

En mis tiempos libres desarrollo y experimento con agentes de IA, buscando convertir ideas en herramientas que puedan ser utilizadas por personas reales.

<br>

[![GitHub](https://img.shields.io/badge/Visita%20mi%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jasiiid)

</div>

---

<div align="center">

### 🇧🇴 Hecho pensando en Santa Cruz.

**Datos oficiales revisados: 26 de septiembre de 2026**

<br>

*Construir tecnología también puede significar hacer que algo cotidiano sea un poco más fácil.*

</div>
