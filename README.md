Proyecto: Administracion de Servicios DHCP

Repositorio dedicado a la implementación y gestión del protocolo DHCP en entornos mixtos. Diseñado para el módulo de Servicios de Red e Internet (ASIR).

Datos de la Entrega

Campo

Información

Alumno

Iñigo Durán Sanz

Fecha de entrega

19 de febrero de 2026

Sistemas Operativos

Windows Server 2022 / Ubuntu Server 22.04 LTS

Versión

1.0.0

Contenido del Repositorio

El proyecto se divide en cuatro áreas fundamentales para la comprensión y despliegue del servicio:


1. Presentaciones y Teoria

Recursos destinados a la exposición de conceptos clave como el proceso DORA, parámetros de red y arquitectura cliente-servidor.

presentacion_dhcp.md: Esquema detallado de diapositivas.

index.html: Presentación web autoejecutable.


2. Laboratorios Practicos

Guías de configuración técnica para administradores de sistemas.

practica_windows_linux.md: Pasos para la creación de ámbitos, exclusiones y reservas de IP.

analisis_wireshark.md: Captura y análisis de tráfico real para verificar el intercambio de mensajes UDP.


3. Documentacion Docente

Material de apoyo para la gestión del aula y evaluación del aprendizaje.

guia_profesor_dhcp.md: Objetivos didácticos y criterios de evaluación.

fichas_tecnicas_alumnos.md: Documentación de referencia rápida para el estudiante.


4. Evaluacion

Herramientas para la comprobación de conocimientos adquiridos.

Kahoot_DHCP.csv: Plantilla para importación de preguntas en la plataforma Kahoot.

examen_dhcp.md: Prueba de evaluación teórica y resolución de supuestos prácticos.

Tecnologias y Conceptos Cubiertos

Para la correcta visualización y ejecución de este proyecto se han considerado los siguientes puntos críticos:

Protocolo: Análisis de puertos 67 y 68 UDP.

Seguridad: Prevención de servidores DHCP no autorizados (Rogue DHCP).

Escalabilidad: Implementación de Agentes de Relevo (DHCP Relay) para entornos con múltiples subredes.

Tolerancia a fallos: Configuración básica de alta disponibilidad y tiempos de concesión (Lease Time).

Instrucciones de Visualizacion

Para una lectura óptima en entornos locales, se recomienda utilizar editores compatibles con GitHub Flavored Markdown. Los archivos HTML pueden abrirse directamente en cualquier navegador moderno.
