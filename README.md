#  Caso Seleccionado: Aplicación de Control de Asistencia
## Descripción del Caso
La Aplicación de Control de Asistencia es un sistema diseñado para registrar, gestionar y monitorear la presencia de estudiantes, empleados u otros usuarios dentro de una organización.  
Su objetivo principal es automatizar el seguimiento de asistencia, reducir errores manuales y ofrecer **reportes precisos en tiempo real**.
### Funcionalidades principales
- Registro de entrada y salida mediante credenciales, códigos QR, huella digital o geolocalización.  
- Panel administrativo para estadísticas, reportes y gestión de horarios.  
- Alertas automáticas por ausencias o retardos.  
- Integración con nómina o evaluaciones según el entorno.  
- Acceso multiusuario con roles diferenciados (administrador, supervisor, usuario).
## Objetivos del Proyecto
- Digitalizar el proceso de control de asistencia en instituciones académicas o laborales.  
- Garantizar la seguridad, disponibilidad y confiabilidad de la información.  
- Proveer una interfaz intuitiva y accesible para todos los actores del sistema.  
- Permitir la generación de reportes automáticos y alertas ante patrones de inasistencia.  
- Integrar nuevas tecnologías (como reconocimiento facial) que mejoren la precisión y experiencia del usuario.
## Requerimientos Funcionales
| Código | Funcionalidad | Propósito |
|:-------:|:--------------|:----------|
| **RF01** | Registro de asistencia | Facilitar el control diario de asistencia. |
| **RF02** | Consulta de historial | Permitir transparencia y seguimiento individual. |
| **RF03** | Generación de reportes | Automatizar la creación de informes mensuales. |
| **RF04** | Autenticación de usuarios | Asegurar el acceso controlado y seguro al sistema. |
| **RF05** | Notificaciones por inasistencias | Alertar sobre ausencias reiteradas para intervención temprana. |

##  Tabla de Pruebas (Ejemplo de Plan de Verificación)

 Requerimiento Asociado | Entrada | Resultado Esperado | Estado |
|:----------------|:----------------------|:--------|:-------------------|:-------|
 RF01 | Usuario escanea QR | Registro exitoso de entrada |  Aprobado |
 RF02 | Consulta de estudiante | Muestra historial correcto |  Aprobado |
 RF03 | Solicitud de reporte mensual | Genera documento PDF |  Aprobado |
 RF04 | Login incorrecto | Acceso denegado |  Aprobado |
 RF06 | Rostro reconocido | Registro automático correcto |  En desarrollo |
## Tipo de Mantenimiento Propuesto
| Tipo de Mantenimiento | Descripción | Ejemplo |
|:----------------------|:-------------|:----------|
| **Correctivo** | Corrige errores o fallos detectados en uso. | Arreglar un error al registrar hora de entrada. |
| **Preventivo** | Evita fallos futuros mediante optimización o limpieza de código. | Refactorizar código para mejorar rendimiento. |
| **Perfectivo** | Mejora funcionalidades o experiencia del usuario. | Implementar reportes automáticos y mejorar la interfaz. |
| **Adaptativo** | Ajusta el sistema a cambios externos o nuevos entornos. | Adaptar la app a una nueva versión de Android. |

## 💬 Reflexión sobre el Control de Versiones


El control de versiones no solo facilita la gestión técnica, sino que refuerza la disciplina de trabajo en equipo y documentación profesional dentro del ciclo de vida del software.

