# Ingeniería de Contexto

## ¿Qué es la ingeniería de contexto?

La **ingeniería de contexto** es la disciplina que se encarga de **diseñar y gestionar la información que rodea a una petición a un modelo de lenguaje** para que pueda generar respuestas más precisas, coherentes y útiles.

No se trata solo de escribir un buen prompt, sino de **preparar el entorno de información adecuado** para que el modelo entienda correctamente la tarea que debe realizar.

En pocas palabras:

> **El prompt es la pregunta.    
> El contexto es todo lo que el modelo necesita saber para responder bien.**  

---

## ¿Por qué es importante?

Los modelos de lenguaje no tienen acceso directo a la realidad ni a bases de datos externas, salvo que se les proporcionen como contexto. 

Una buena ingeniería de contexto permite:

- Reducir respuestas incorrectas o irrelevantes.
- Mantener coherencia en conversaciones largas.
- Adaptar las respuestas a un dominio concreto.
- Construir aplicaciones de IA más fiables y escalables.

Sin un buen contexto, incluso un prompt bien escrito puede producir resultados pobres.

---

## Ingeniería de prompts vs Ingeniería de contexto

| Ingeniería de prompts | Ingeniería de contexto |
|----------------------|------------------------|
| Se centra en la instrucción | Se centra en el entorno completo |
| Actúa a corto plazo | Actúa de forma continua |
| Texto puntual | Datos, memoria, reglas, herramientas |
| Ideal para tareas simples | Clave en sistemas complejos |

Ambas se complementan: **un buen prompt necesita un buen contexto**.

---

## ¿Qué puede formar parte del contexto?

El contexto puede incluir:

- Información previa de la conversación.  
- Documentos relevantes.  
- Datos del dominio (reglas, definiciones, ejemplos).  
- Perfil del usuario o de la tarea.  
- Resultados de herramientas externas (búsquedas, bases de datos).  

No todo debe incluirse siempre: **más contexto no siempre significa mejor contexto**.

---

## Principios básicos de la ingeniería de contexto

1. **Relevancia**  
   Solo debe incluirse información útil para la tarea actual.

2. **Claridad**  
   El contexto debe estar organizado y ser fácil de interpretar.

3. **Actualización**  
   El contexto puede cambiar con el tiempo o con cada interacción.

4. **Economía**  
   Los modelos tienen un límite de contexto; hay que usarlo con cuidado.

---

## Ejemplo sencillo

### Sin ingeniería de contexto

**Prompt:**

> Resume este texto.

El modelo no sabe:  
- Para quién es el resumen.  
- Qué nivel de detalle se espera.  
- Qué aspectos son más importantes.  

### Con ingeniería de contexto

Se añade información como:  
- El público objetivo.  
- El objetivo del resumen.  
- El estilo deseado.  

Resultado: una respuesta más precisa y alineada con la necesidad real.

---

## ¿Dónde se utiliza la ingeniería de contexto?

La ingeniería de contexto es fundamental en: 

- Chatbots avanzados.  
- Asistentes inteligentes.  
- Sistemas de recuperación aumentada (RAG).  
- Agentes autónomos basados en LLMs.  
- Aplicaciones empresariales basadas en IA.  

En estos casos, el modelo necesita **mucho más que una pregunta aislada**.

---

## Resumen

- La ingeniería de contexto prepara el entorno de información del modelo.
- Va más allá de escribir prompts.
- Permite respuestas más coherentes, precisas y útiles.
- Es clave para construir aplicaciones reales con IA generativa.
