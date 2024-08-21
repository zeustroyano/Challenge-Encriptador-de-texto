## **Encriptador de Mensajes Secreta: ¡Tu Caja Fuerte Digital!**

### **Solución al Challenge - Encriptador de Texto de Oracle Next Education (ONE)**

Este proyecto representa la resolución del primer reto de la formación Oracle Next Education (ONE) de Oracle + Alura Latam, utilizando las tecnologías HTML5, CSS3 y JavaScript. El objetivo principal era construir una aplicación web funcional que permitiera a los usuarios encriptar y desencriptar texto de manera sencilla.

**¿Qué hace este proyecto?**

* **Encriptación:** Convierte texto plano en un código secreto utilizando las siguientes llaves de sustitución:
  * **e** -> enter
  * **i** -> imes
  * **a** -> ai
  * **o** -> ober
  * **u** -> ufat
* **Desencriptación:** Devuelve el texto a su formato original, descifrando el código generado.

**Tecnologías utilizadas:**

* **HTML5:** Estructura básica de la página web.
* **CSS3:** Estilos y diseño visual de la interfaz.
* **JavaScript:** Lógica de programación para la encriptación, desencriptación y manipulación de la interfaz de usuario.

**¿Por qué este proyecto?**

Este desafío fue una excelente oportunidad para poner en práctica los conocimientos adquiridos en la Formación Principiante en Programación de Oracle Next Education (ONE). Al construir este encriptador, consolidé mis habilidades en:

* **Manipulación del DOM:** Modificar elementos HTML desde JavaScript para crear una interfaz dinámica.
* **Eventos:** Escuchar y responder a acciones del usuario (por ejemplo, al hacer clic en un botón).
* **Funciones:** Crear bloques de código reutilizables para realizar tareas específicas.
* **Algoritmos simples:** Implementar el algoritmo de sustitución para cifrar y descifrar texto.

**¿Cómo funciona?**
# Diagrama de Flujo del Encriptador de Textos

```mermaid
flowchart TD
    A[Inicio] --> B[Entrada de Texto]
    B --> C{Selección de Modo}
    C --> |Encriptar| D[Aplicar Reglas de Encriptación]
    D --> E[Mostrar Texto Encriptado]
    C --> |Desencriptar| F[Aplicar Reglas de Desencriptación]
    F --> G[Mostrar Texto Desencriptado]
    E --> H[Copiar al Portapapeles]
    G --> H[Copiar al Portapapeles]
    H --> I[Reiniciar]
    I --> A
    I --> J[Fin]


**Estructura del proyecto:**
encriptador/
├── index.html
├── style.css
├── script.js
└── README.md
