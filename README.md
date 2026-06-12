# Configuración de una VPC con subredes y gestión de seguridad

Tu tarea es diseñar y configurar una VPC en un entorno de nube que incluya subredes públicas y privadas, un NAT Gateway, y reglas de routing entre subredes. Además, deberás implementar medidas de seguridad para proteger la red. El objetivo es asegurar que los recursos de la VPC estén correctamente aislados y accesibles según las necesidades del negocio.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Diseño de redes |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 3-4 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Diseño de la VPC

**Objetivo:** Definir la estructura de la VPC incluyendo subredes públicas y privadas.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Identifica las necesidades del negocio para determinar qué recursos deben estar en subredes públicas y cuáles en privadas.
- Diseña la estructura de la VPC con las subredes necesarias.

**Entregable:** Diagrama de la estructura de la VPC con subredes públicas y privadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera la segmentación de la red para mejorar la seguridad y el rendimiento.
- Piensa en cómo las subredes públicas y privadas interactúan entre sí.

</details>

### Fase 2: Configuración de NAT Gateway y routing

**Objetivo:** Implementar un NAT Gateway y configurar las rutas entre subredes.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Configura un NAT Gateway para permitir que las instancias en subredes privadas accedan a Internet.
- Define las rutas necesarias para el tráfico entre subredes públicas y privadas.

**Entregable:** Configuración del NAT Gateway y tablas de rutas entre subredes.

<details>
<summary>Pistas de conocimiento</summary>

- Recuerda que el NAT Gateway es necesario para que las instancias en subredes privadas puedan acceder a Internet.
- Las rutas deben ser definidas para asegurar un flujo de tráfico eficiente y seguro.

</details>

### Fase 3: Gestión de seguridad de red

**Objetivo:** Implementar medidas de seguridad para proteger la red.

**Tiempo estimado:** 1 hora

**Instrucciones:**

- Configura grupos de seguridad para controlar el acceso a los recursos en la VPC.
- Implementa reglas de seguridad para proteger las subredes públicas y privadas.

**Entregable:** Configuración de grupos de seguridad y reglas de seguridad para la VPC.

<details>
<summary>Pistas de conocimiento</summary>

- Los grupos de seguridad actúan como un firewall virtual para los recursos en la VPC.
- Las reglas de seguridad deben ser definidas para permitir solo el tráfico necesario y bloquear el acceso no autorizado.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es una VPC y por qué es importante en un entorno de nube?
- **paraQueSirve**: ¿Para qué sirven las subredes públicas y privadas en una VPC?
- **comoSeUsa**: ¿Cómo se usa un NAT Gateway en una VPC?
- **erroresComunes**: ¿Cuáles son los errores comunes al configurar la seguridad en una VPC?
- **queDecisionesImplica**: ¿Qué decisiones implica la gestión de seguridad en una VPC?

## Criterios de Evaluacion

- Diseño de la estructura de la VPC con subredes públicas y privadas.
- Configuración del NAT Gateway y rutas entre subredes.
- Implementación de medidas de seguridad para proteger la red.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
