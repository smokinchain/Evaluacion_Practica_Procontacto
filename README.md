# Evaluación Práctica <img src="LOGO.png" align="right"/>

<p align="left">
  <img src="https://img.shields.io/badge/Interview-Challenge-blueviolet" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
  <img src="https://img.shields.io/badge/Salesforce-00A1E0?logo=salesforce&logoColor=white" />
  <img src="https://img.shields.io/badge/REST-API-green" />
  <img src="https://img.shields.io/badge/SOAP-API-lightgrey" />
</p>

Repositorio correspondiente a la resolución de una serie de ejercicios teóricos y prácticos solicitados como parte de un proceso de evaluación técnica.

---

## Índice

- [Ejercicio 1 – Instalación del ambiente](#instalación-del-ambiente)
- [Ejercicio 2 – Protocolo HTTP](#http)
- [Ejercicio 3 – Ejercicio práctico](#pruebas-de-comunicación-http-y-manejo-de-json)
- [Ejercicio 4 – Ejercicio práctico](#configuración-de-trailhead-y-resolución-de-módulos)
- [Ejercicio 5 – Conceptos de Salesforce](#conceptos-de-salesforce)
- [Ejercicio 6 – Salesforce: soluciones, funcionalidades y conceptos generales](#salesforce-soluciones-funcionalidades-y-conceptos-generales)
- [Ejercicio 7 – Ejercicio práctico](#integración-salesforce-con-servicio-rest-externo)

---

## Instalación del ambiente

Este ejercicio estuvo orientado a la instalación y configuración del entorno de trabajo necesario para el desarrollo del resto de los ejercicios.

Se realizó la instalación y configuración de:
- Visual Studio Code
- Git
- Git Bash
- Postman

_Adicionalmente, se trabajó con la plataforma Salesforce, trailhead y Draw.io._

---

## HTTP

### Servidor HTTP

HTTP es un protocolo de transferencia de hipertexto que permite la comunicación entre un cliente y un servidor a través de un esquema de petición–respuesta. En este modelo, el cliente realiza una solicitud de transmisión de datos y el servidor responde devolviendo el recurso solicitado o el resultado de la operación.

El protocolo HTTP es de tipo stateless, lo que significa que cada solicitud es independiente y no mantiene información sobre solicitudes anteriores. Además, funciona sobre el conjunto de protocolos TCP/IP, lo que permite una comunicación confiable entre sistemas.

Un servidor HTTP es un tipo específico de servidor que almacena, procesa y responde solicitudes realizadas por clientes, como navegadores web o aplicaciones. Su función principal es entregar contenido web y datos a los usuarios, permitiendo acciones como acceder a una página, enviar un formulario o consumir información a través de una API.

Además, un servidor HTTP es capaz de gestionar múltiples solicitudes de manera concurrente y devolver respuestas utilizando códigos de estado HTTP que indican el resultado de cada petición. Puede servir contenido estático directamente o comunicarse con aplicaciones backend para generar respuestas dinámicas, según el tipo de recurso solicitado.

---

### Verbos HTTP

Los verbos HTTP o métodos HTTP, son las acciones que se indican en una solicitud HTTP y que definen qué operación desea realizar el cliente sobre un recurso del servidor.

Cada verbo representa una intención específica, como obtener información, enviar datos, actualizar un recurso o eliminarlo. El servidor interpreta el verbo incluido en la solicitud y ejecuta la acción correspondiente sobre el recurso solicitado. Resumidamente, como instrucciones que le damos al servidor sobre qué queremos que haga con los datos o recursos que estamos solicitando.

Los verbos HTTP más conocidos son:
  
| Verbo HTTP | Qué hace | Ejemplo |
|------------|----------|---------|
| GET        | Se utiliza para solicitar y obtener información de un recurso. No modifica datos en el servidor. | Obtener una página web o consultar datos desde una API |
| POST       | Se utiliza para enviar información al servidor, generalmente para crear un nuevo recurso. | Enviar los datos de un formulario o crear un nuevo registro |
| PUT        | Se utiliza para actualizar completamente un recurso existente. | Modificar todos los datos de un usuario |
| PATCH      | Se utiliza para realizar una actualización parcial de un recurso. | Modificar solo un campo específico |
| DELETE     | Se utiliza para eliminar un recurso del servidor. | Borrar un registro existente |
| HEAD       | Solicita los headers de un recurso sin devolver el cuerpo de la respuesta. | Verificar si un recurso existe o consultar metadatos |
| OPTIONS    | Se utiliza para consultar qué métodos HTTP están permitidos para un recurso. | Verificar operaciones disponibles en una API |

---

### Request y Response

En una comunicación HTTP, un request (solicitud) y un response (respuesta) son los dos mensajes fundamentales que permiten que un cliente y un servidor se comuniquen.

| Tipo       | Qué es / Función                                                                 | Elementos principales                                                                 | Ejemplo                                                                                 |
|------------|---------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| Request    | Mensaje que envía el cliente al servidor para pedir un recurso o realizar una acción | - Verbo HTTP (GET, POST, PUT, etc.)<br>- URL del recurso<br>- Headers (información adicional como tipo de contenido, idioma o autenticación)<br>- Body (opcional, datos enviados al servidor) | Al ingresar una página web en el navegador, se envía un request GET solicitando el HTML de la página |
| Response   | Mensaje que envía el servidor al cliente después de procesar la solicitud       | - Código de estado (response code)<br>- Headers (información adicional, tipo de contenido, longitud)<br>- Body (contenido solicitado: HTML, JSON, mensaje de error) | El servidor responde con el HTML de la página, imágenes, CSS y un código 200 indicando éxito |

---

### Headers
Los headers son información adicional que se envía junto a una solicitud (request) o una respuesta (response) HTTP. No forman parte del contenido principal, pero le dicen al cliente o al servidor cómo procesar la información. Pueden incluir datos como:

- Tipo de contenido (Content-Type) que indica si se envía HTML, JSON, imágenes, etc.

- Tamaño del contenido (Content-Length).
- Información sobre autenticación o tokens de seguridad (Authorization).
- Cookies o datos de sesión.
- Idioma preferido del cliente (Accept-Language).

Ejemplo:
```http
GET /user/333 HTTP/1.1
Host: ejemplo.com
Accept: application/json
Accept-Language: es-ES
Authorization: Bearer abc333

```
---

### QueryString



---

### Response Code

__

---

### Envío de datos en GET y POST

__

---

### Verbo HTTP utilizado por el navegador

__

---

### JSON y XML

__

---

### SOAP

__

---

### RESTful

__

---

### Header Content-Type

__

---

## Pruebas de comunicación HTTP y manejo de JSON

### Descripción

__

### Enfoque y resolución

__

---

## Configuración de trailhead y resolución de módulos

### Descripción

__

### Enfoque y resolución

__

---

## Conceptos de Salesforce

conceptos a explicar, breve descripcin

1. 
2. 
3.
4. 
5. 
6. 
7. 
8.
9. 
10.

### Relaciones entre conceptos (Diagrama UML)

_ diagrama UML en draw.io con los conceptos q se relacionan_

<!-- pegar link al diagrama o foto como sea mejor -->
<!-- Ejemplo: https://app.diagrams.net/... -->

<!-- ![Diagrama UML](ruta/imagen.png) -->

---

## Salesforce: soluciones, funcionalidades y conceptos generales

### Soluciones de Salesforce

1. 
2. 
3. 
4. 
5. 

---

### Funcionalidades de Salesforce

 <ol type="a">
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li> 
  <li></li> 
</ol>
---

### Conceptos generales de Salesforce

 <ol type="a">
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ol> 

---

## Integración Salesforce con servicio REST externo

### Descripción

_explicacion._

### Enfoque y resolución

__

---

## Autor

Candela Paredes
