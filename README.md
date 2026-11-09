# ꫂ᭪ ¡Hola! Soy Estephanie

**Frontend que termina siendo full stack** ✦

Soy una desarrolladora a la que le gusta crear interfaces intuitivas y escalables, y pensar en que cualquier persona pueda usar una aplicación de forma fácil y cómoda.

---

## ♡ Sobre mí

Estudié en un colegio técnico y, entre todas las especialidades, la que más me llamó fue desarrollo de software. Ahora estudio Informática Empresarial en la Universidad de Costa Rica y estoy haciendo mi práctica empresarial.

Sí a un chocolate, caliente o frío ☕︎

---

## Cómo me gusta trabajar ⋆｡‧˚ʚ

↳ **Usabilidad** - Me pongo en el lugar de quien usa la aplicación para que encuentre lo que busca, entienda qué hacer en cada pantalla y, si se equivoca, el sistema se lo explique con claridad  
↳ **Código limpio** - Simple, fácil de leer y sostenible, para que otros y hasta yo misma lo entendamos  
↳ **Probar antes de entregar** - Verifico que todo funcione, pero desde el punto de vista de un usuario  
↳ **Documentación** - Que el proyecto lo entiendan otros y no solo yo, con manuales de usuario y preguntas frecuentes  

---

## ❀ Lo que he construido

### Módulo de reportes de planillas
*Práctica empresarial (proyecto de la empresa, sin repositorio público)*

Módulo web de reportes de planillas para un sistema que se está migrando a la web, hecho con C#, ASP.NET Core MVC, Entity Framework Core y SQL Server. Lo desarrollé a partir de los reportes del sistema anterior y lo dejé como base para migrar otros módulos. Son 16 reportes, entre ellos aguinaldo, vacaciones, liquidación, deducciones, horas trabajadas, incapacidades, aportes patronales y los de CCSS e INS, además del comprobante de pago.

<details open>
<summary>Lo que hice</summary>

↳ Las pantallas de filtros, en tres tipos (simples, de comprobante y detallados), y la regla de empresa: quien administra puede cambiar de empresa y quien es de una empresa solo ve la suya  
↳ Los reportes en PDF, Excel y Word con el mismo contenido en los tres formatos, con encabezado, logo de cada empresa, pie y totales alineados, siempre en hoja carta  
↳ El tiquete de pago en PDF de 80 mm para impresoras térmicas  
↳ Avisos, indicadores de carga, errores de conexión y diálogos como componentes reutilizables para otros módulos  
↳ Validación de entradas en la pantalla y en el servidor, como las fechas posteriores a hoy, el rango de fechas invertido y la empresa permitida  
↳ Programación defensiva y manejo de errores para datos vacíos o mal guardados  
↳ Arquitectura en capas, con la lógica de negocio en servicios y no en los controladores  
↳ QA funcional, pruebas de entradas no válidas, pruebas de exportación y pruebas de experiencia de usuario, con los errores encontrados registrados y corregidos  
↳ El manual de usuario, guías técnicas y los entregables de la práctica  

</details>

### Bitácoras y reportes
*Proyecto en equipo de Análisis y diseño de software, con Angular, .NET y SQL Server (Proyecto para una empresa, sin repositorio público)*

Sistema de bitácoras que registra los accesos, modificaciones y actividades de los usuarios para dar trazabilidad y seguridad, con un módulo de reportes. Está hecho con Angular y Angular Material en el frontend y una API en ASP.NET Core con Entity Framework y SQL Server en el backend.

<details>
<summary>Lo que hice en el módulo de reportes</summary>

↳ Los filtros de cada reporte, con validaciones como las fechas obligatorias, que la fecha final no sea anterior a la inicial y que se elija el usuario que consulta  
↳ El reporte de Seguridad DTIC y el Informe Cuatrimestral, con su consulta en el backend y sus pantallas  
↳ Las tablas dentro de la misma página y el PDF que se abre en otra ventana y se puede descargar  
↳ Los PDF generados en el backend con el formato oficial del informe, con encabezado, logo y secciones  
↳ La lógica para construir los gráficos en el backend (consultas por mes, promedio por día y hora, y oficinas con más consultas) e insertarlos en el informe  
↳ El estilo de los reportes, el menú lateral, las rutas y los mensajes de error con la descripción correcta  

</details>

### Sitio web de un hotel de turismo (Purrujas)
*Proyecto en equipo de 5 en Ingeniería de Software, con Angular, .NET y SQL Server* · [Ver repositorio](https://github.com/JIgnacio24/Proyecto_Ingenieria_Hotelera_Purrujas)

Sistema para un hotel y resort con dos aplicaciones Angular y un backend en ASP.NET Core organizado en capas, con SQL Server de base de datos y todo levantado con Docker. El sitio de los clientes tiene inicio, sobre nosotros, instalaciones, cómo llegar, promociones, contacto, cotización y reservación en línea. El lado administrador permite cambiar el contenido del sitio sin ser desarrollador, y también gestionar habitaciones, tipos de habitación, temporadas, promociones, publicidad y reservaciones, con métricas, pronóstico de ocupación y bitácora de auditoría.

<details>
<summary>Lo que hice</summary>

↳ Las páginas de Inicio y Contacto del sitio, con su navbar y su footer  
↳ El contenido editable de Sobre nosotros, Inicio y la galería de imágenes, con su API, su base de datos y su pantalla de edición en el administrador  
↳ El estado y la disponibilidad de las habitaciones, y el CRUD de tipos de habitación  
↳ El dashboard con métricas y gráficos del hotel  
↳ Mejoras en la cotización, en su lentitud y en el refresco de la vista  
↳ La investigación de Docker y las guías para levantar todo el proyecto  

</details>

### Raíces con Sabor (landing page de recetas de Turrialba)
*Proyecto individual de Multimedios, con React (Vite), ASP.NET Core y SQL*

Landing page para un proyecto gastronómico que da a conocer recetas de Turrialba y capta suscripciones de personas interesadas. Hice el proceso completo, desde el brief y las personas hasta el prototipo en Figma, la evaluación heurística y el desarrollo.

<details>
<summary>Lo que hice</summary>

↳ El brief, los objetivos, los requerimientos y las fichas de personas con sus escenarios de uso  
↳ El mapa del sitio, los wireframes y el guion técnico y de interacción  
↳ El moodboard, el sistema de diseño y el prototipo en Figma, con versiones para escritorio y móvil  
↳ La evaluación heurística y el informe final del proceso  
↳ Una API en ASP.NET Core en capas (Api, Domain e Infrastructure) que entrega las recetas con sus ingredientes, pasos, creadores y productores, y guarda las suscripciones  
↳ El frontend en React con Vite que consume la API  

</details>

### AeroStar (plataforma de compra de tiquetes de vuelo)
*Proyecto de Lenguajes, con React, TypeScript, Express y MongoDB* · [Ver repositorio](https://github.com/Estephaniec/ProyectoII_Lenguajes)

Aplicación web para buscar y comprar vuelos, con inicio de sesión protegido con código OTP, horarios en la hora local de cada aeropuerto, historial de compras e interfaz en español e inglés.

<details>
<summary>Lo que hice</summary>

↳ El registro e inicio de sesión con verificación en dos pasos (código OTP con Google Authenticator) y la sesión con tokens JWT de acceso y de renovación  
↳ La búsqueda de vuelos por origen, destino, fechas y pasajeros, con la salida y la llegada en hora local y la duración calculada  
↳ La compra de vuelos, con la regla de que cada usuario compra un vuelo una sola vez, y el historial de compras  
↳ Una tarea programada (cron) que genera los vuelos desde el backend  
↳ La interfaz en español e inglés con i18next y estilos con Tailwind CSS  

</details>

### Solución de inteligencia de negocios
*Proyecto académico, con SSIS, SSAS y Tableau* · [Ver repositorio](https://github.com/Estephaniec/BI-AdventureWorks)

Solución sobre AdventureWorks: un ETL que carga las ventas por internet a un data warehouse, un cubo OLAP con sus medidas, dimensiones y perspectivas, y dashboards de KPIs organizados con el Balanced Scorecard.

<details>
<summary>Lo que hice</summary>

↳ El ETL en SSIS, con columnas derivadas, búsquedas de llaves de las dimensiones y manejo de las filas con error  
↳ El cubo en SSAS con 8 medidas, medidas calculadas como el margen de ganancia y las ventas acumuladas del año, y perspectivas por producto, cliente, territorio y promoción  
↳ Los dashboards en Tableau con KPIs de ventas por producto, año, promoción, cliente y ubicación  

</details>

### Investigación sobre Angular
Investigación sobre Angular, con un proyecto que consume una API y tiene pruebas unitarias, de integración y E2E. [Ver repositorio](https://github.com/Estephaniec/Investigacion_EstephanieCerdasMolina)

---

## ✦ Stack tecnológico ⋆.˚

### Lenguajes
![C#](https://img.shields.io/badge/C%23-F472B6?style=for-the-badge&logo=c-sharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-A78BFA?style=for-the-badge&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-F472B6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-A78BFA?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-F472B6?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### Frontend y diseño
![Angular](https://img.shields.io/badge/Angular-F472B6?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-A78BFA?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-F472B6?style=for-the-badge&logo=vite&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-A78BFA?style=for-the-badge&logo=figma&logoColor=white)

### Backend, datos y BI
![.NET](https://img.shields.io/badge/.NET-F472B6?style=for-the-badge&logo=.net&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core%20MVC-A78BFA?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework Core](https://img.shields.io/badge/Entity%20Framework%20Core-F472B6?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-A78BFA?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-F472B6?style=for-the-badge&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-A78BFA?style=for-the-badge)
![SQL Server](https://img.shields.io/badge/SQL%20Server-F472B6?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-A78BFA?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-F472B6?style=for-the-badge&logo=sqlite&logoColor=white)
![QuestPDF](https://img.shields.io/badge/QuestPDF-A78BFA?style=for-the-badge)
![ClosedXML](https://img.shields.io/badge/ClosedXML-F472B6?style=for-the-badge)
![SSIS](https://img.shields.io/badge/SSIS-A78BFA?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![OLAP](https://img.shields.io/badge/OLAP-F472B6?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-A78BFA?style=for-the-badge&logo=power-bi&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-F472B6?style=for-the-badge&logo=tableau&logoColor=white)

### Calidad y herramientas
![Cypress](https://img.shields.io/badge/Cypress-F472B6?style=for-the-badge&logo=cypress&logoColor=white)
![Karma](https://img.shields.io/badge/Karma-A78BFA?style=for-the-badge)
![Jasmine](https://img.shields.io/badge/Jasmine-F472B6?style=for-the-badge&logo=jasmine&logoColor=white)
![Git](https://img.shields.io/badge/Git-A78BFA?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-F472B6?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-A78BFA?style=for-the-badge&logo=docker&logoColor=white)
![Redes](https://img.shields.io/badge/Redes-F472B6?style=for-the-badge)
![Routers y switches](https://img.shields.io/badge/Routers%20y%20switches-A78BFA?style=for-the-badge)

---

## ✧ Actualmente ⋆.˚

- ♡ Terminando mi práctica empresarial con el módulo de reportes
- ♡ Profundizando en arquitectura de software y patrones de diseño
- ♡ Mejorando en rendimiento y en experiencia de usuario
- ♡ Abierta a conversar sobre proyectos y oportunidades como full stack

---

## ♡ Conecta conmigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-A78BFA?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/estephanie-cerdas-3b8649223)
[![Email](https://img.shields.io/badge/Email-F472B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:estephaniecerdas@gmail.com)

✦ Estephanie Cerdas | estephaniecerdas@gmail.com
