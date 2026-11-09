# actividad2.3

# Tarea de Aprendizaje: Contenedor GitClient

Este repositorio contiene los archivos y notas de la tarea práctica orientada al aprendizaje y gestión de entornos virtuales. Todo el entorno está configurado de manera *segura y controlada* para la simulación de entornos de producción.

---

## Configuración del Entorno Remoto

Para esta práctica, utilizamos un **contenedor remoto basado en Ubuntu** que actúa como nuestro cliente de Git principal. Esto nos permite estandarizar las herramientas sin importar el sistema operativo local.

Para conocer más detalles sobre la plataforma de contenedores, puedes consultar la [Documentación Oficial de Ubuntu](https://ubuntu.com).

###  Especificaciones del Contenedor
* **Sistema Operativo:** Ubuntu Server (versión LTS).
* **Acceso:** Conexión remota cifrada a través de protocolo seguro.
* **Herramientas:** Git preinstalado junto a utilidades de red esenciales.

---

## Topología del Laboratorio

En el siguiente esquema puedes ver cómo se conecta tu máquina local con el contenedor Ubuntu remoto y el servidor Git externo:

![Esquema de Conexión Remota](./img/contenedor.jpeg)



---

## Guía de Comandos Básicos

### 1. Acceso al Contenedor e Inicialización
Una vez que accedas a la terminal de tu contenedor remoto Ubuntu, puedes verificar la instalación de Git y configurar tu identidad ejecutando el siguiente bloque de código:

```bash
# Comprobar la versión de Git instalada en Ubuntu
git --version

# Configurar tu nombre de usuario global
git config --global user.name "Tu Nombre"

# Configurar tu correo electrónico
git config --global user.email "tu-correo@ejemplo.com"
```

### 2. Sincronización del Trabajo
Recuerda realizar tus commits de manera frecuente.
