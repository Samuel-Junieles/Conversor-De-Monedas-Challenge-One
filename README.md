# # Conversor-De-Monedas-Challenge-One

Este proyecto es una aplicación de consola en Java que realiza conversiones de divisas en tiempo real utilizando una API externa.

## 🚀 Funcionalidades
* **Conversión en tiempo real:** Consulta tasas de cambio actualizadas.
* **Catálogo de monedas:** Opción para ver los códigos de las monedas soportadas.
* **Interacción por consola:** Menú dinámico para el usuario.

## 🛠️ Tecnologías
* **Java:** Lenguaje principal.
* **Gson:** Librería para procesar los datos JSON de la API.
* **ExchangeRate-API:** Servicio para obtener los tipos de cambio.

## 📦 Configuración
1. **API Key:** Es necesario obtener una clave en [exchangerate-api.com](https://www.exchangerate-api.com/) y colocarla en la variable `apiKey` de la clase `Main.java`.
2. **Librería Gson:** Se debe descargar el archivo JAR de Gson e incluirlo en las dependencias del proyecto (Project Structure > Modules > Dependencies).

## 📖 Uso
1. Ejecutar la clase `Main.java`.
2. Elegir la opción del menú (1 para catálogo, 2 para convertir, 3 para salir).
3. Ingresar los códigos de moneda (ej: USD, MXN) y el valor a transformar.

---
Proyecto desarrollado para el Challenge ONE de Oracle Next Education y Alura Latam.
