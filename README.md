# PrestAmigos

---

## 1. Integrantes

| Nombre | Descripción |
|------|-------------|
| Stefania Sarmiento | Soy Stefania, tengo 20 años, vivo en Silvania Cundinamarca. Actualmente trabajo como docente de bachillerato enseñando ingles y frances y tambien soy estudiante universitaria, me apasiona aprender y enseñar. Actualmente no tengo hobbies como deportes o pasatiempos sin embargo me gusta mucho aprender idiomas por lo que me encuentro estudiando Portugues. Ha sido un reto estudiar y trabajar sin embargo no ha sido en vano y se que no lo sera.|
| Yohani Correa | Soy Yohani, tengo 32 años, vivo en La Ceja, Antioquia. Trabajo como auxiliar contable y soy emprendedor de una perfumeria. Vivo con mi esposa y dos hijos, estar en estos momentos estudiando, es un reto para mi, ya que varias veces he empezado y me ha tocado dejar el camino, pero hoy puedo decir que voy en el tercer semestre y con la ilusion de llegar a la meta. Ya saben si desean algun perfume a la orden jeje|
| Karen Johana Hinestroza Mercado | Soy Karen,tengo 18 años, vivo en chigorodo antioquia, por el momento soy estudiante,deportista y hago parte de un voluntariado. El deporte que practico es la lucha olimplica y Judo, el voluntariado al cual pertenezco se llama Raices de Ebano y es enfocado en comunidades negras, sus contumbres y tradiciones. Por medio de este voluntariado y el gobierno, lidero un poyecto enfocado en la industrilizacion avicola en zonas vulnerables de mi municipio, voy en mi tercer semestre de ingenieria industrial y mis pasatiempos preferidos es pasar tiempo con mi familia, salir a cenar con mis amigas, trotar y leer. |
| Mariana Alcaraz Alvarez | Soy mariana, tengo 22 años, vivo en chigorodo antioquia, actualmente trabajo en un centro de lubricacion automotriz, vivo con mis padres, mi hermana y dos mascotas, mi pasatiempo preferido es pasar tiempo con mi familia y hacer actividades con ellos como ir al rio, estoy en mi tercer semestre y mi objetivo es terminar la carrra y poder lograr mis metas propuestas. |
---

## 2. Vínculos académicos y descripción

### Stefania Sarmiento
**Programa:** Ingeniería Industrial  
**Habilidades:** análisis lógico, organización  
**Fortalezas:** Trabajo en equipo, comunicacion efectiva

### Yohani Correa
**Programa:** Ingeniería Industrial  
**Habilidades:** Matematicas, Disciplina       
**Fortalezas:** Responsable, Aprendo rapido 

### Karen Hinestroza
**Programa:** Ingeniería Industrial  
**Habilidades:** pensamiento logico, trabajo en equipo

**Fortalezas:** amor por el aprendizaje continuo  
 
### Mariana Alcaraz

**Programa:** Ingeniería Industrial 

**Habilidades:** Comunicacion Asertiva, Pensamiento Critico

**Fortalezas:** Autodisciplina 

## 3. Nombre del proyecto

**Nombre:** PRESTAMIGOS  

**Descripción:**  
Sistema automatizado de gestion de prestamos e inventario desarrollado en Python. El cual permite registrar articulos,
gestionar el historial de presamos a terceros y automatizar el seguimiento de devoluciones. Incluye funciones criticas
como alertas de vencimiento, generacion de certificado de retorno y emision automatica de facturas de venta para productos
no devueltos.

![LOGOPRESTAMIGOS](https://github.com/user-attachments/assets/1ee226a3-bcbc-443a-80c9-7f0e10c369c3)


---

## 4. Licencia del software

​Este proyecto está bajo una licencia **CC BY-NC 4.0**. Para ver una copia de esta licencia, visite http://creativecommons.org/licenses/by-nc/4.0/ 

---

## 5. Reporte de visión

Convertirse en la solución tecnológica líder para la gestión de activos personales en entornos colaborativos, 
transformando la informalidad de los préstamos entre amigos en un proceso transparente, organizado y justo. 
Buscamos que para el año 2026, Prestamigos sea el estándar de confianza, garantizando que ninguna herramienta 
se pierda y que la buena voluntad nunca signifique una pérdida económica.
### Pilares Estratégicos de la Visión

Para alcanzar el estado ideal del proyecto y resolver la problemática de control de inventario, el desarrollo de **PRESTAMIGOS** se fundamenta en tres pilares esenciales:

#### 1. Eficiencia en la Trazabilidad Logística
El núcleo del sistema no consiste únicamente en almacenar registros aislados, sino en garantizar un control total y en tiempo real sobre el estado de cada artículo. El software permite conocer instantáneamente quién posee un objeto, la fecha exacta de salida y cuántos días restan para su devolución esperada. Con esto, se erradican de forma definitiva las anotaciones informales en papel y las pérdidas materiales por olvido o confusión.

#### 2. Cultura de Responsabilidad mediante Coactividad Financiera
A través de la automatización de la regla de los 30 días, el programa implementa un mecanismo de control de morosidad. Al aplicar de forma exacta el **impuesto por conchudez del 23%** sobre el valor base de adquisición, el sistema deja de ser un simple bloc de notas pasivo y se transforma en una herramienta activa orientada a la toma de decisiones financieras y a la recuperación forzosa del valor de los activos.

#### 3. Escalabilidad Analítica con Pandas
Gracias a la migración de las colecciones de datos tradicionales hacia estructuras de la librería **Pandas** (`pd.DataFrame`), el sistema está diseñado para proyectar un crecimiento modular. Esto le permite al administrador ir más allá de las consultas básicas, procesando de forma automatizada métricas complejas (como la sumatoria de recaudos vectoriales y la identificación de extremos de actividad con métodos como `.idxmax()` e `.idxmin()`) para predecir comportamientos de préstamo en el futuro.


## 6. Requisitos funcionales 
| ID        | Requisito |Descripcion|
|-----------|-----------|-----------|
| R-01  | Registrar Usuario | El sistema debe permitir registrar un amigo con nombre, apellido, documento y tiempo de préstamo (5, 10, 15 o 30 días)|
| R-02  | Registrar prestamos | Solo se pueden crear préstamos a usuarios previamente registrados en el sistema |
| R-03  | Retornos | El sistema permite registrar la devolución de un ítem prestado verificando que el préstamo esté activo |
| R-04  | Notificaciones de recuperacion | El sistema genera una alerta cuando un préstamo supera los 20 días sin devolución    |
| R-05  | Solicitud de devolucion | El sistema emite una solicitud formal de devolución al cumplirse el tiempo de préstamo acordado    |
| R-06  | Recibo de venta  | Se genera una factura con subtotal e impuesto del 23% para ítems con más de 30 días prestados    |
| R-07  | Certificados de devolucion| Al registrar una devolución a tiempo se genera un certificado con los datos del préstamo en archivo de texto    |   
| R-08  | Recordatorio despues de 30 dias  | El sistema notifica a MJ que un ítem superó el mes de préstamo y debe proceder con la facturación    |

## Requisitos No Funcionales

| ID | Requisito | Descripción |
|----|-----------|-------------|
| RNF-01 | Usabilidad | El menú de consola debe ser claro y fácil de navegar para cualquier usuario |
| RNF-02 | Validación de entradas | El sistema debe validar cada dato ingresado y mostrar mensajes de error comprensibles |
| RNF-03 | Rendimiento | El sistema debe responder a cada operación en menos de 3 segundos |
| RNF-04 | Seguridad | El módulo administrador requiere usuario y contraseña para acceder |
| RNF-05 | Compatibilidad | El programa debe ejecutarse en Python |
| RNF-06 | Fiabilidad | La información debe persistir entre sesiones mediante archivos planos sin pérdida de datos |
| RNF-07 | Mantenibilidad | El código debe estar organizado en carpetas `src/` y `doc/` con nomenclatura clara |

## 7. Presupuesto Y Diagrama Gantt

Para su calculo hemos definifo que cada integrante va invertir 50 Horas cada uno en el proyecto.
 - SMLV = 1'750.905 Pesos
 - Valor Hora Promedio = 7.959 Pesos
 - Inversion por Estudiante = 50 H * 7.959 = 397.950 Pesos
 - Costo Total Proyecto = 4 * 397.950 = 1'591.800 Pesos

   ### Diagrama de Gantt primera entrega

   <img width="1024" height="768" alt="diagrama de gantt primera entrega" src="https://github.com/user-attachments/assets/f63d0e23-8835-44b3-8c69-9a0919a9c460" />

   ### Diagrama de Gantt segunda entrega

<img width="1203" height="741" alt="Diagrama PrestAmigos" src="https://github.com/user-attachments/assets/b03da3d0-a4ef-4937-a35f-37f042e6ebf3" />

# 8. Plan de Versionado (Historial de Desarrollo)

A continuación se detalla de forma cronológica el proceso de construcción y evolución de **PRESTAMIGOS**, reflejando las etapas de desarrollo y la integración de las herramientas vistas en el curso.

### 📌 Versión 0.1 (Semana 4) - Maquetación de la Interfaz Base
* **¿Qué se hizo?:** Creación de la estructura del menú principal (`menu_principal()`) con las 8 opciones de navegación del sistema.
* **Estado del avance:** En esta fase inicial, el programa no procesaba datos reales ni persistía información. El objetivo principal fue diseñar un entorno visual amigable en consola y validar el correcto enrutamiento del flujo lógico mediante sentencias condicionales (`if / elif / else`).

### 📌 Versión 0.5 (Semana 7) - Registro
* **¿Qué se hizo?:** Implementación de las funciones de captura de datos `registrar_usuario()` y `registrar_item()`.
* **Estado del avance:** Se incorporaron las primeras reglas. Se programaron validaciones para restringir que los nombres contengan números, asegurar que los documentos de identidad posean entre 3 y 15 dígitos y verificar la estructura básica de los correos electrónicos. La información comenzó a ser estructurada de forma temporal en colecciones de datos tradicionales (diccionarios).

### 📌 Versión 1.0 (Semana 10) - Módulo de Préstamos y Control de Acceso
* **¿Qué se hizo?:** Desarrollo de la lógica de asignación en `registrar_prestamo()` y la capa de seguridad en `submenu_administrador()`.
* **Estado del avance:** El sistema empezó a cruzar datos de transacciones, validando obligatoriamente que un artículo del inventario solo pueda ser prestado si el usuario solicitante ya se encuentra previamente registrado en la plataforma. Paralelamente, se añadieron las credenciales maestras (`ADMIN_USER` y `ADMIN_PASS`) para restringir el acceso al panel de administración mediante retornos preventivos en caso de datos erróneos.

### 📌 Versión 1.5 (Semana 12) - Retornos, Alertas Cronológicas y Archivos Planos
* **¿Qué se hizo?:** Integración de la función `registrar_devolucion()` y el control de alertas automáticas por tiempo de préstamo.
* **Estado del avance:** Se programó la rutina para evaluar las fechas de préstamo, activando la generación automática de los certificados de devolución en archivos de texto plano (`.txt`) independientes. El sistema adquirió la capacidad de discriminar los estados de los artículos (Activo/Devuelto) y de realizar alertas preventivas.

### 📌 Versión 2.0 - Versión Final (Semana 14) - Reestructuracion con Pandas
* **¿Qué se hizo?:** Reestructuración integral del almacenamiento interno y optimización de reportes mediante la biblioteca **Pandas**.
* **Estado del avance:** Aprovechando los conceptos avanzados de manipulación de datos adquiridos en las últimas sesiones del curso, se transformaron las bases de datos transaccionales de diccionarios hacia estructuras `pd.DataFrame`. Esta actualización permitió:
  * Tabular y presentar de manera limpia las listas de usuarios y reportes financieros en consola.
  * Utilizar el método vectorial `.sum()` para computar de forma exacta el recaudo total y calcular con precisión el **impuesto por conchudez del 23%** para artículos con mora superior a 30 días.
  * Implementar las funciones estadísticas `.idxmax()` e `.idxmin()` sobre la cantidad de préstamos para calcular automáticamente los usuarios con mayor y menor actividad en el sistema.
  * Flexibilizar el software mediante la función `.lower()` para admitir correos electrónicos indistintamente en mayúsculas o minúsculas y corregir el comportamiento restrictivo de los días permitidos (5, 10, 15 y 30).





 
