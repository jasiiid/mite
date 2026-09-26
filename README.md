**Autor**

Skill construida y verificada para contexto Santa Cruz, Bolivia.  
Datos oficiales revisados el 26 de septiembre de 2026.

# Guía de trámites Santa Cruz

Skill de hackathon para asistentes de IA que orientan a personas **no técnicas** en Santa Cruz de la Sierra y el departamento (Bolivia). El archivo que carga el asistente es `SKILL.md`.

| Campo | Valor |
|---|---|
| Nombre | Guía de trámites Santa Cruz |
| Skill id | `gu-a-de-tr-mites-santa-cruz` |
| Archivo | `SKILL.md` |
| Idioma | Español boliviano claro |
| Verificación de datos | 26 sep 2026 |

## En qué ayuda

Ayuda cuando alguien pregunta **cómo hacer un trámite o un servicio de todos los días** y no maneja apps ni portales. Puede no tener Ciudadanía Digital.

El asistente, con esta skill, responde en frases cortas:

1. Qué es el trámite.
2. Qué hay que llevar.
3. Los pasos (pocos y en orden).
4. Dónde queda y cómo llegar **desde la zona** de la persona.
5. Costos y plazos solo si están verificados.
6. Una duda típica (por ejemplo, no tener Ciudadanía Digital).
7. Una sola pregunta para seguir.

Cubre identidad, negocio (SEPREC), vehículos, estudio y becas, hogar, salud, trabajo e impuestos nacionales, impuestos municipales (DAT), familia (SERECI), migración (DIGEMIG), adulto mayor y cobro de bonos.

No da consejo legal profundo y no hace el trámite por la persona.

## Qué cambia entre usarla y no usarla

| Situación | Sin la skill | Con la skill |
|---|---|---|
| “El pasaporte me dijeron en Indana” | Puede mandar a Indana, Ventura Mall o al 4º anillo | Oficina de la ciudad: Edificio Guapay. Indana está cerrado para migración |
| “Pago el impuesto de la casa en IDEAZA” | Puede tratar IDEAZA como una oficina real | IDEAZA no existe en fuentes oficiales: deriva a DAT / Quinta Municipal |
| Cómo llegar | Puede inventar línea de micro y tiempo de viaje | Pide el anillo o el barrio, da la dirección y un punto de referencia |
| No tiene Ciudadanía Digital | Asume que va a entrar a un portal o una app | Explica el trámite presencial o con ayuda de otra persona |
| Pide varios trámites a la vez | Los mezcla en una sola respuesta | Los separa, los ordena por dependencia y arma un plan del día |
| Montos y plazos | Puede dar cifras genéricas | Solo usa cifras verificadas; si duda, pide confirmar ese día en el sitio oficial |
| Forma de hablar | Texto largo y siglas sin explicar | Una idea por frase y, al cierre, una sola pregunta |
| Un dato que no está confirmado | Lo dice como si fuera seguro | Lo marca **POR CONFIRMAR** |

## Categorías cubiertas

1. Identidad (Ciudadanía Digital, SEGIP)
2. Negocio (SEPREC, empresa unipersonal)
3. Vehículos (RUAT / Quinta DAT)
4. Estudio (UPSA, UPDS, título, traspasos)
5. Becas (portales a re-verificar el día)
6. Hogar (anticrético, alquiler, luz, agua, gas, DD.RR.)
7. Salud (SUS, Hospital San Juan de Dios, CNS, discapacidad)
8. Trabajo, SIN y Gestora
9. Impuestos municipales DAT (IMPBI, IMPVA, patentes, IMTO)
10. Familia y registro civil (SERECI)
11. Migración DIGEMIG (solo Guapay en la ciudad)
12. Adulto mayor (Ley 1886 y Renta Dignidad)
13. Bonos (Renta Dignidad, Juancito Pinto, Juana Azurduy, discapacidad)

## Cómo usarla

1. Cargar `SKILL.md` como skill del asistente.
2. Probar con preguntas como estas:
   - “Quiero abrir un negocio unipersonal, vivo en el 2º anillo sur.”
   - “Cómo cobro el Juancito Pinto 2026.”
   - “Dónde hago el pasaporte. Me dijeron Indana.”
   - “Cómo pago el impuesto de mi casa (IDEAZA).”
3. El asistente debe pedir la **zona**, no inventar micros y re-verificar montos el día de la consulta.

## Fuentes (muestra)

- migracion.gob.bo/oficinas (Guapay; ficha de Indana en 404)
- gestora.bo · seprec.gob.bo · gmsantacruz.gob.bo
- ABI (Juancito Pinto 2026)
- gob.bo (Moto Méndez, Renta Dignidad) · impuestos.gob.bo · citas SERECI

## Límites

No inventa oficinas, micros, montos ni plazos. Sedes aún sin confirmar en la skill: SERECI central de Santa Cruz, CNS física, MIN-TEPS Santa Cruz y CONALPEDIS Santa Cruz.
