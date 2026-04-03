# Clase 3
Recordemos los pilares de la ingeniería de software: 
>**Persona, Proyecto, Producto, Proceso. **

También tengamos en mente que con estos pilares buscamos: 
>**Calidad, costo, tiempo. **

Algo importante a tener en cuenta con el parámetro de calidad.
>Calidad total significa nunca terminar el proyecto. 

Otro punto más a recordar:
El ciclo de vida del desarrollo de un proyecto.
1. Planificación y análisis (requerimientos).
2. Modelado y diseño.
3. Programación.
4. Pruebas.
5. Lanzamiento y mantenimiento.

## **Desafíos como ing. software: **

- Complejidad creciente, cada vez más capas, más componentes. 
- Retos técnicos y organizacionales. Equipos, versiones diferentes. 
- Presupuestos y plazos ajustados. 
- Demandas de calidad y seguridad. 
- Evolución rápida del mercado. 
- Interconexión de sistemas. Maneras de conectar el sistema con diferentes entornos. 
- Errores y fallos crecientes. más personas, más errores. 
- Gestión de la complejidad. Patrones de diseños y de arquitectura, herramientas para analizar y visualizar el sistema eficazmente. 
- Impacto en proyectos. Complejidad no controlada. 
- Problemas comunes en proyectos, problemas de compatibilidad. 
- Causa de fallas, experiencia y planificación deficiente.  
- Mitigación de riesgos, metodologías ágiles e híbridas, gestionan riesgos efectivamente. 
- Importancia de la comunicación, con el equipo y el cliente. 

## Demanda de calidad del software 

La demanda de calidad del software se centra en:
- confiabilidad
- usabilidad
- seguridad

**Para garantizar calidad:**
- se requieren procesos rigurosos
- pruebas exhaustivas
- cumplimiento de estándares

**Beneficios**
- evita pérdidas
- reduce riesgos de seguridad

>Enfoque clave:
El aseguramiento de calidad debe iniciarse desde las primeras etapas del desarrollo

## Problemas de escalabilidad 
¿Qué es escalabilidad?
>capacidad de un sistema para soportar más carga (usuarios, datos, tráfico) sin perder rendimiento.  

Existen 2 tipos de escalabilidad:
>**Escalabilidad horizontal:** compro más máquinas, más batata. 
>**Escalabilidad vertical:** aumento la capacidad del servidor. 

Empresas pequeñas enfrentan dificultades cuando crecen rápidamente.

**La falta de escalabilidad**
- Limita el crecimiento
- Empeora la experiencia del usuario (lentitud, caídas)

**Solución**
- Aplicar buenas estrategias de diseño
- Usar arquitecturas distribuidas
- Implementar balanceo de carga
- Apoyarse en la nube como Amazon Web Services o Google Cloud

## Términos mencionados por el profesor:
🔧 1. NCP

Puede significar varias cosas según el contexto, pero en redes:

Network Control Protocol
Se usa para configurar y gestionar conexiones de red (ej: en PPP)

👉 Básicamente:

ayuda a que dos dispositivos se entiendan en una red

🤖 2. n8n
Herramienta de automatización (tipo “Zapier pero más técnica”)
Permite conectar apps y crear flujos automáticos

Ejemplo:

Cuando recibes un email → guardar en base de datos automáticamente

👉 Muy útil para backend y productividad

🔐 3. OAuth (protocolo de autenticación)
Permite iniciar sesión sin compartir tu contraseña

Ejemplo:

“Iniciar sesión con Google”

👉 Funciona así:

la app recibe un token, no tu contraseña
🧩 4. Modelo Vista Controlador (MVC)
Patrón de diseño muy usado

Se divide en:

Modelo → datos y lógica
Vista → lo que ve el usuario
Controlador → conecta ambos

👉 Idea:

separar responsabilidades para organizar mejor el código

📊 5. MMMR

Este es menos estándar, puede variar según contexto.
Uno de los usos comunes:

Man-Month Rate (o Man-Month Resource)
Relacionado con estimación de esfuerzo en proyectos

👉 Ejemplo:

“Este proyecto toma 3 personas durante 2 meses”

⚠️ Puede significar otra cosa según tu clase → vale la pena confirmar contexto

☎️ 6. On-call
Persona del equipo disponible para emergencias

Ejemplo:

Si el sistema se cae a las 2 AM → el on-call responde

👉 Muy común en empresas tech
