![AMBROSIO — Ingeniería estructural, modelación y automatización](assets/banner.svg)

# Ingeniería estructural · Modelación · Automatización

Este espacio reúne mi trabajo descrito en investigación numérica y automatización, junto con desarrollos en curso y propuestas de estudio. Mi enfoque está en la respuesta sísmica, el concreto armado y la comunicación clara de hipótesis, resultados y límites.

[Portafolio web](https://sergioambrosio714.github.io/) · [Fichas técnicas](https://sergioambrosio714.github.io/#proyectos) · [Laboratorio de estructuras](https://sergioambrosio714.github.io/#laboratorio)

## Proyectos seleccionados

| Proyecto | Enfoque y herramientas | Estado de la evidencia |
| --- | --- | --- |
| [Pilares de concreto armado con CFRP](https://sergioambrosio714.github.io/casos/01-pilares-cfrp.html) | Comparación BASE/CFRP, secciones de fibras y respuesta cíclica en OpenSeesPy. | Estudio reportado; scripts, datos brutos y cita completa del ensayo pendientes. |
| [Flujo de revisión sísmica E.030](https://sergioambrosio714.github.io/casos/02-motor-e030.html) | Arquitectura ETABS → Python → Mathcad Prime → memoria trazable. | En desarrollo; implementación funcional y validación pendientes. |
| [Detalles estructurales con AutoLISP](https://sergioambrosio714.github.io/casos/03-autolisp.html) | Familias de rutinas descritas para vigas, columnas, placas y escaleras en AutoCAD. | Desarrollo técnico descrito; fuentes `.lsp` y capturas auténticas no adjuntas. |
| [Columnas reforzadas en edificaciones](https://sergioambrosio714.github.io/casos/04-columnas.html) | Comparación numérica propuesta de CFRP y encamisado en edificios de hasta 12 pisos. | En formulación; sin resultados definitivos. |

## Un caso, con su alcance explícito

La documentación del estudio de pilares con CFRP reporta **117/117 objetivos cíclicos completados**, **NRMSE = 7,928 %** y un incremento de fuerza lateral de **+12,725 % a +5 % de deriva** en el caso numérico de aplicación.

Estos indicadores no han sido verificados de forma independiente en este repositorio: faltan los archivos fuente, los datos brutos y la referencia completa del ensayo. Corresponden al caso estudiado y no constituyen una garantía de desempeño para otras estructuras. La [ficha CFRP](https://sergioambrosio714.github.io/casos/01-pilares-cfrp.html) detalla metodología, cifras adicionales y documentación pendiente.

## Competencias y tecnologías

| Área | Relación con el trabajo presentado |
| --- | --- |
| **OpenSeesPy · Python** | Modelación no lineal y tratamiento de resultados descritos en el caso CFRP; evidencia ejecutable pendiente. |
| **ETABS · Python · Mathcad Prime** | Herramientas previstas en la arquitectura de revisión E.030, todavía en desarrollo. |
| **AutoCAD · AutoLISP** | Dibujo paramétrico y organización de detalles en las familias de rutinas descritas. |
| **SAP2000 · BIM · coordinación 4D/5D** | Áreas de interés y profundización; este portafolio no aporta todavía un caso específico que demuestre su aplicación. |
| **Documentación técnica** | Estructura de casos con problema, objetivo, procedimiento, resultados y límites de verificabilidad. |

La revisión normativa del flujo E.030 está pendiente. El proyecto no es un verificador terminado ni certificado.

## Laboratorio interactivo

El [laboratorio de viga biapoyada](https://sergioambrosio714.github.io/#laboratorio) permite explorar reacciones, cortante y momento bajo carga uniforme. Es una demostración didáctica de estática; no dimensiona secciones ni acredita cumplimiento normativo.

## Contacto

- [Perfil de GitHub](https://github.com/SergioAmbrosio714).
- Correo profesional y LinkedIn: pendientes de configurar con datos confirmados.

<!-- CONTACTO CONFIGURABLE: sustituir la línea anterior por correo profesional y URL de LinkedIn reales cuando estén confirmados. No publicar identificadores privados ni enlaces de ejemplo. -->

---

Primero las hipótesis y la mecánica. Después el modelo y el código. Cada conclusión, con su evidencia y sus límites.
