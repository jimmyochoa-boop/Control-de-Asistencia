## Aplicación de Control de Asistencia

## Descripción del Caso
La Aplicación de Control de Asistencia es un sistema diseñado para registrar, gestionar y monitorear la presencia de estudiantes, empleados u otros usuarios dentro de una organización. Su objetivo principal es automatizar el seguimiento de asistencia, reducir errores manuales y ofrecer reportes precisos en tiempo real.

### Funcionalidades principales
- Registro de entrada y salida mediante credenciales, códigos QR, huella digital o geolocalización.
- Panel administrativo para visualizar estadísticas, generar reportes y gestionar horarios.
- Alertas automáticas por ausencias o retardos.
- Integración con nómina o módulos académicos según el entorno.
- Acceso multiusuario con roles diferenciados.

## Objetivos del Proyecto
- Digitalizar el proceso de control de asistencia.
- Garantizar seguridad, disponibilidad y confiabilidad de la información.
- Ofrecer una interfaz intuitiva y accesible para todos los usuarios.
- Permitir la generación automática de reportes y alertas.
- Incorporar tecnologías modernas como reconocimiento facial para mejorar la precisión.

## Requerimientos Funcionales

| Código | Funcionalidad | Propósito |
|--------|----------------|-----------|
| RF01 | Registro de asistencia | Facilitar el control diario de asistencia. |
| RF02 | Consulta de historial | Permitir transparencia y seguimiento individual. |
| RF03 | Generación de reportes | Automatizar la elaboración de informes periódicos. |
| RF04 | Autenticación de usuarios | Garantizar un acceso seguro y controlado. |
| RF05 | Notificaciones por inasistencias | Alertar sobre ausencias reiteradas. |
| RF06 | Reconocimiento facial | Optimizar el registro automático mediante IA. |

## Tabla de Pruebas

| Caso de Prueba | Requerimiento Asociado | Entrada | Resultado Esperado | Estado |
|----------------|------------------------|---------|--------------------|--------|
 RF01 | Escaneo de código QR | Registro exitoso de entrada | Aprobado |
 RF02 | Consulta de historial | Visualización correcta de datos | Aprobado |
 RF03 | Solicitud de reporte mensual | Generación del documento correspondiente | Aprobado |
 RF04 | Credenciales incorrectas | Acceso denegado | Aprobado |
 RF06 | Reconocimiento del rostro | Registro automático correcto | En desarrollo |

## Tipo de Mantenimiento Propuesto

1. Mantenimiento correctivo  
   Corrige fallos detectados durante el uso del sistema, como errores en el registro de asistencia o fallos en el cálculo de horas trabajadas.

2. Mantenimiento preventivo  
   Previene futuros errores mediante optimización del código, limpieza, actualización de librerías o revisión de rendimiento.

3. Mantenimiento perfectivo  
   Añade mejoras o funcionalidades nuevas para incrementar la utilidad del sistema, como nuevos reportes o mejoras en la interfaz.

4. Mantenimiento adaptativo  
   Ajusta el sistema a cambios externos, como nuevas versiones de sistemas operativos, cambios en infraestructura o nuevas normativas.

## Reflexión sobre el Control de Versiones

El uso de control de versiones permitió mantener un historial claro y ordenado del desarrollo del proyecto. Git y GitHub facilitaron la colaboración entre los integrantes, evitando conflictos y pérdidas de información.  
El versionado permitió mantener trazabilidad entre requerimientos, documentos, pruebas y evidencias, reforzando la organización y la disciplina en el proceso de desarrollo.


