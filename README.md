# Prueba Técnica QA Automation - GreenSQA

## Autor

Mayra Alejandra Calderón Cortés

## Descripción

Este repositorio contiene la propuesta de solución para la prueba técnica de QA Automation solicitada por GreenSQA.

La solución plantea el diseño de un generador de datos de prueba, la aplicación de principios de Programación Orientada a Objetos (POO), principios SOLID, patrones de diseño y la propuesta de automatización de pruebas para la búsqueda de vuelos en LATAM utilizando Serenity BDD, Selenium y Cucumber.

---

## Objetivos

* Generar datos ficticios para pruebas automatizadas.
* Aplicar los pilares de Programación Orientada a Objetos.
* Aplicar principios SOLID.
* Aplicar patrones de diseño.
* Diseñar una estrategia de persistencia de datos.
* Generar archivos CSV para consumo de pruebas.
* Diseñar escenarios de automatización para LATAM.
* Proponer una arquitectura basada en Serenity BDD y Cucumber.

---

## Contenido del Repositorio

### 01-Arquitectura-Solucion.pdf

Documento que describe la arquitectura propuesta para el generador de datos y la automatización.

### 02-Evidencia-Tecnica.pdf

Documento que explica las tecnologías, principios de diseño y estrategia de automatización.

### 03-Casos-Prueba-LATAM.xlsx

Casos de prueba diseñados para la funcionalidad de búsqueda de vuelos en LATAM.

### 04-Requerimientos-y-Reglas-Negocio.pdf

Documento con las reglas de negocio identificadas a partir del enunciado de la prueba.

---

## Tecnologías Propuestas

* Java
* Maven
* Selenium WebDriver
* Serenity BDD
* Cucumber
* SQLite
* GitHub

---

## Automatización Propuesta

La automatización se plantea utilizando:

* Selenium para la interacción con el navegador.
* Cucumber para la definición de escenarios en lenguaje Gherkin.
* Serenity BDD para la gestión de ejecución y generación de reportes.

Ejemplo de escenario:

Feature: Búsqueda de vuelos LATAM

Scenario: Búsqueda exitosa de vuelo

Given el usuario ingresa a la página de LATAM

When busca un vuelo desde Bogotá hacia Medellín con una fecha válida

Then el sistema debe mostrar los vuelos disponibles para la ruta seleccionada

---

## Conclusión

La propuesta presentada busca demostrar el análisis técnico de la solución, el entendimiento de conceptos de automatización de pruebas, diseño orientado a objetos y buenas prácticas de desarrollo, alineándose con los requerimientos planteados para la prueba técnica.
