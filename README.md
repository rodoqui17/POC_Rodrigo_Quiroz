# POC_Rodrigo_Quiroz

Como primer paso se realizó un relevamiento de la información respecto a los requerimientos y a la estructura del POC:

Requerimientos:
1)	La billetera móvil debe entregarse para IOS y Android
2)	La usabilidad y el diseño son muy importantes
3)	El rendimiento la trazabilidad y la seguridad son claves, ya que se utiliza dinero real, y está sujeto a regulaciones.
4)	Cada evento del sistema debe ser auditado
5)	Todos los componentes serán reutilizables.
6)	Es un POC, necesitamos encontrar victorias rápidas y carriles rápidos.

Riesgos Tecnológicos identificados:
1)	Exposición de datos sensibles
2)	Configuraciones incorrectas del control de accesos
3)	Falta de cifrado entre aplicaciones Backend / FrontEnd
4)	Errores en el desarrollo de Smart Contracts

Propuesta:
R1: Requiere de una aplicación multiplataforma 
R2: Hacer uso de estándares ISO 9241-11, ISO/IEC 9126-1 FDIS
R3: Uso de API Gateway para el enrutamiento y control de accesos, las funciones de cada Smart Contract deberan estar vinculados a cada microservicio.
R4: Uso de events en la blockchain integrados con un sistema de gestión de mensaje  y una base de datos para la recopilación de información en los procesos de auditoría.
R5: Uso de Microservicios, Arquitectura Hexagonal que permita integrar distintos puertos.
R6: Uso de contenedores para un despliegue más consistente permitiendo la modularidad de la solución.

1.- ARQUITECTURA Y TECNOLOGIA
FrontEnd : React Native
Desarrollo rentable
Entrega más rápida
Aprovecha Javascript
Requiere Equipos más Pequeños
Comunidad de desarrolladores activa

Backend : Spring Boot
	Altamente escalable
	Gran documentación
	Creado para aplicaciones a gran escala que utilizan un enfoque en la nube
	Ecosistema extenso
	Madurez y estabilidad	

Base de datos: MySQL
	Tareas multiproceso
	Cuenta con API’s disponibles para los principales lenguajes de programación
	Portabilidad
	Nivel de seguridad que permite gestionar varios usuarios y contraseñas individuales

Smart Contract Entorno de desarrollo: Hardhat

Canales CI/CD Integración continua: Jenkins

ApiGatway: Kong

Gestor de Colas: RabittMQ / Eventum /Apache Kafka
	Facilita el desacoplamiento de servicios 
	Gran comunidad	

Contenedores: Docker

Orquestación de los contenedores : Kubernets

Control de versiones: Git 


2.- EQUIPO
Cargo	Roles 	cantidad	Habilidades
Producto Owner	Liderar el equipo atender los requerimiento del sistema, conocimiento sobre marcos de trabajo, herramientas de trabajo en equipo y gestión de proyectos	1	Liderazgo, experiencia trabajando con clientes y desarrolladores
UX/UI Developer	Diseño de la usabilidad, y experiencia para el usuario, conociemientos de estandare ISO, herramientas de trabajo en equipo	1	Empatía 
Backend Developer	Conocimientos en JAVA springboot,	2	Experiencia en el cargo patrones de diseño y arquitecturas
Front end Developer	Conocimientos en React	2	Experiencia en desarrollo de app mobiles multiplataforma y web patrones de diseño y arquitecturas
Blockchain Developer	Desarrollo de Smart contracts, librerías como openzepelling, truffle, Remix	1	Experiencia en el desarrollo manejo de patrones de diseño y arquitecturas 
Especialista en Ciberseguridad o seguridad informática

(Empresa externa)	Validación de los procesos de implementación en cada fase del proyecto	1	Conocimiento sobre herramientas de ciberseguridad a nivel de red, aplicaciones y programación en blockchain 


3.- CULTURA
SCRUM
TRELLO
SLACK
