# 🏫 Panamá Oeste: Más Fuertes, Más Unidos, Más Empáticos
### Mural Pedagógico e Interactivo de Prevención Sísmica y Cuidado Emocional

> **Propósito Educativo:** Recurso web interactivo diseñado para concientizar a estudiantes, padres de familia, docentes y a toda la comunidad de **Panamá Oeste** tras el sismo ocurrido el **09 de octubre**, reforzando qué hacer **mientras** y **después** de un sismo, junto con el cuidado socioemocional y la unión comunitaria.

---

## 🌟 Características Principales

1. **Protocolo Sísmico Oficial (SINAPROC / MEDUCA):**
   - **Fase 1 (Mientras ocurre el sismo):** Los tres pasos fundamentales en 3D: **¡AGÁCHATE!**, **¡CÚBRETE!** y **¡AGÁRRATE!**, reglas de oro y minijuego de decisión.
   - **Fase 2 (Después del sismo):** Evacuación hacia el punto de encuentro, advertencia sobre réplicas, cables caídos, estructuras y comunicación responsable.
2. **Cuento Interactivo con Ilustración:**
   - *"El día que la tierra se movió y nuestros corazones se unieron"* con narración por voz (SpeechSynthesis) y resaltado interactivo de lectura.
   - Ilustración del aula escolar con visor ampliado (*Lightbox modal*).
3. **Mochila de Emergencia Familiar:**
   - 8 artículos clave interactivos con contador dinámico y sonidos.
4. **Cuidado Emocional:**
   - Tarjetas de validación emocional para niños y jóvenes con respuestas reconfortantes.
5. **Árbol de la Esperanza 3D:**
   - Muro interactivo donde los estudiantes cuelgan hojas con mensajes de aliento (guardados localmente con `localStorage`).
6. **En Casa nos Cuidamos con Amor:**
   - *Frasco de los abrazos y la gratitud* familiar con guardado local.
   - Lista de verificación del plan de seguridad familiar y mensaje de agradecimiento.
7. **Directorio Rápido de Emergencias en Panamá Oeste:**
   - Botones de llamada directa a **SINAPROC (911 / 520-4429 / \*335)**, **Bomberos (103)**, **Policía Nacional (104)** y **Cruz Roja (\*455)**.

---

## 🚀 Cómo Publicar en GitHub Pages (Gratis en 3 pasos)

Para que cualquier estudiante, docente o padre de familia pueda abrir este mural desde su celular, tablet o computadora sin descargar nada:

1. **Crear Repositorio en GitHub:**
   - Ingresa a [github.com](https://github.com) e inicia sesión.
   - Haz clic en **"New repository"** (Nuevo repositorio).
   - Nómbralo (por ejemplo: `panama-oeste-segura` o `mural-sismo-panama-oeste`).
   - Elige **Public** (Público) y presiona **Create repository**.

2. **Subir los Archivos:**
   - En la página de tu repositorio, haz clic en **"Add file"** > **"Upload files"** (subir archivos existentes).
   - Arrastra o selecciona los siguientes archivos clave de esta carpeta:
     - `index.html` *(archivo principal del sitio web)*
     - `protocolos-oficiales-meduca.jpg` *(lámina de protocolos MEDUCA)*
     - `ilustracion-sismo-aula.jpg` *(ilustración del cuento)*
     - `Guia_de_Soporte_Emocional_Post-Sismo_Biancheri.pdf` *(Guía docente)*
     - `Somos_Pequenos_Cuento_Sismo.pdf` *(Cuento ilustrado)*
     - `Hojas_de_Colorear_Despues_del_Temblor_Dilsia_Morales.pdf` *(Cuadernillo de actividades)*
     - `README.md`
   - Haz clic en el botón verde **"Commit changes"**.

3. **Activar GitHub Pages (Tu enlace web público):**
   - En tu repositorio de GitHub, ve a **Settings** (Configuración) en la barra superior.
   - En el menú izquierdo, entra en **Pages**.
   - En **Build and deployment > Branch**, selecciona la rama **main** (o `master`) y la carpeta **/(root)**.
   - Haz clic en **Save** (Guardar).
   - ¡Listo! En 1 o 2 minutos, GitHub te dará un enlace público como:
     `https://tu-usuario.github.io/nombre-del-repositorio/`

---

## 💻 Tecnologías Utilizadas
* **HTML5 semántico y accesible**
* **Tailwind CSS (vía CDN)**
* **Font Awesome 6 (iconografía)**
* **Web Speech API & Web Audio API (efectos de sonido y narración sin dependencias externas)**
* **LocalStorage (persistencia en el dispositivo)**
