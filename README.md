# 📚 Extracción de Conocimientos en Bases de Datos - IDGS91N

## Entrega de Evidencias mediante GitHub

Bienvenido al repositorio de entregas para la materia **Extracción de Conocimientos en Bases de Datos** del grupo **IDGS91N**.

Debido a que la plataforma Moodle está temporalmente fuera de servicio, utilizaremos este repositorio de GitHub para recibir y revisar tus evidencias de aprendizaje.

---

## 🎯 ¿Qué necesito hacer?

Vas a subir tus evidencias (archivos PDF, código, documentos, etc.) a este repositorio usando **Git** y **GitHub**. No te preocupes si nunca has usado estas herramientas, aquí te explicamos **paso a paso** cómo hacerlo.

---

## 📋 Antes de empezar

### 1. Crear una cuenta en GitHub

Si aún no tienes cuenta:

1. Ve a [github.com](https://github.com)
2. Haz clic en **"Sign up"** (Registrarse)
3. Completa el formulario con:
   - Un correo electrónico válido
   - Una contraseña segura
   - Un nombre de usuario (puede ser tu nombre o apodo)
4. Verifica tu correo electrónico
5. ¡Listo! Ya tienes tu cuenta

### 2. Instalar Git en tu computadora

**Para Windows:**
1. Descarga Git desde: [git-scm.com/download/win](https://git-scm.com/download/win)
2. Ejecuta el instalador descargado
3. Deja todas las opciones por defecto y haz clic en "Next" hasta terminar
4. Abre "Git Bash" (lo encontrarás en el menú inicio)

**Para Mac:**
1. Abre la Terminal (búscala en Spotlight con Cmd + Espacio)
2. Escribe: `git --version` y presiona Enter
3. Si no está instalado, macOS te preguntará si quieres instalarlo automáticamente
4. Haz clic en "Instalar"

**Para Linux:**
1. Abre la terminal
2. Ejecuta: `sudo apt-get install git` (Ubuntu/Debian) o `sudo yum install git` (Fedora/CentOS)

---

## 🚀 Paso a paso: Cómo entregar tus evidencias

### Paso 1: Hacer una copia del repositorio (Fork)

1. Asegúrate de haber iniciado sesión en GitHub
2. Ve a la página principal de este repositorio
3. Haz clic en el botón **"Fork"** (esquina superior derecha)
4. GitHub creará una copia del repositorio en tu cuenta
5. Espera unos segundos y verás el repositorio en tu perfil

### Paso 2: Descargar el repositorio a tu computadora (Clonar)

1. En **tu copia del repositorio** (la que está en tu cuenta), haz clic en el botón verde **"Code"**
2. Copia la URL que aparece (debe verse como: `https://github.com/TU_USUARIO/NOMBRE_REPO.git`)
3. Abre **Git Bash** (Windows) o **Terminal** (Mac/Linux)
4. Navega a la carpeta donde quieres guardar el repositorio. Por ejemplo:
   cd Documents
   # o en Windows:
   cd C:\Users\TU_USUARIO\Documents
5. Escribe este comando (reemplaza la URL con la que copiaste):
   git clone https://github.com/TU_USUARIO/NOMBRE_REPO.git
6. Presiona Enter y espera a que se descargue
7. Entra a la carpeta del repositorio:
   cd NOMBRE_REPO

### Paso 3: Configurar tu identidad en Git (solo la primera vez)

Antes de hacer cambios, Git necesita saber quién eres:

git config --global user.name "Tu Nombre Completo"
git config --global user.email "tu.correo@ejemplo.com"

**Importante:** Usa tu nombre real y el correo con el que te registraste en GitHub.

### Paso 4: Crear tu carpeta personal

Ahora vas a crear tu estructura de carpetas. **Usa tu nombre completo con ambos apellidos** (sin espacios, usa guiones bajos).

**Estructura que debes crear:**
entregas/
└── APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE/
    ├── unidad1/
    │   ├── evidencia1/
    │   └── evidencia2/
    ├── unidad2/
    │   ├── evidencia1/
    │   └── evidencia2/
    └── unidad3/
        └── evidencia1/

**Ejemplo práctico para "Juan Pérez García":**
entregas/
└── PEREZ_GARCIA_JUAN/
    ├── unidad1/
    │   ├── evidencia1/
    │   │   ├── documento.pdf
    │   │   └── codigo.java
    │   └── evidencia2/
    │       └── reporte.pdf
    └── unidad2/
        └── evidencia1/
            └── diagrama.png

**Cómo crear las carpetas:**

Puedes hacerlo de dos formas:

**Opción A: Desde el explorador de archivos (más fácil)**
1. Abre el explorador de archivos de tu sistema operativo
2. Navega hasta la carpeta del repositorio que clonaste
3. Dentro de la carpeta `entregas/`, crea tu carpeta con tu nombre completo (ambos apellidos + nombre)
4. Dentro de tu carpeta, crea las carpetas `unidad1`, `unidad2`, etc.
5. Dentro de cada unidad, crea las carpetas `evidencia1`, `evidencia2`, etc.
6. Coloca tus archivos dentro de cada carpeta de evidencia

**Opción B: Desde la terminal (para usuarios avanzados)**
mkdir -p entregas/APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE/unidad1/evidencia1
mkdir -p entregas/APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE/unidad1/evidencia2
mkdir -p entregas/APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE/unidad2/evidencia1

### Paso 5: Agregar tus archivos

Copia tus archivos de evidencia (PDFs, código, imágenes, etc.) a la carpeta correspondiente que creaste.

**Por ejemplo:**
- Si es la evidencia 1 de la unidad 1, coloca tus archivos en:  
  `entregas/APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE/unidad1/evidencia1/`

### Paso 6: Guardar los cambios en Git (Commit)

Una vez que hayas colocado todos tus archivos:

1. Abre Git Bash o Terminal en la carpeta del repositorio
2. Verifica qué archivos agregaste:
   git status
   (Verás una lista de archivos en rojo)

3. Agrega todos los archivos al "staging":
   git add .
   (El punto significa "todos los archivos")

4. Confirma los cambios con un mensaje descriptivo:
   git commit -m "Entrega Unidad 1 - Evidencias 1 y 2 - APELLIDO_PATERNO APELLIDO_MATERNO NOMBRE"
   **Importante:** Reemplaza el mensaje con tu información real

### Paso 7: Subir los cambios a GitHub (Push)

Ahora vas a enviar tus archivos a tu copia del repositorio en GitHub:

git push origin main

Si es la primera vez que haces push, GitHub te pedirá que inicies sesión. Usa tu usuario y contraseña de GitHub.

**Nota:** Si tu rama se llama `master` en lugar de `main`, usa:
git push origin master

### Paso 8: Crear un Pull Request (Solicitud de revisión)

Este es el paso final donde **oficialmente entregas tu trabajo** al profesor:

1. Ve a tu repositorio en GitHub (en tu navegador)
2. Verás un mensaje amarillo que dice **"This branch is X commits ahead of..."**
3. Haz clic en el botón **"Contribute"** y luego **"Open pull request"**
4. Se abrirá una página para crear el Pull Request
5. En el título escribe:
   Evidencias APELLIDO_PATERNO APELLIDO_MATERNO NOMBRE - Unidad X
6. En la descripción escribe:
   - **Alumno:** Tu Nombre Completo (con ambos apellidos)
   - **Grupo:** IDGS91N
   - **Materia:** Extracción de Conocimientos en Bases de Datos
   - **Unidad:** X
   - **Evidencias incluidas:** Lista breve de lo que entregas
   - **Fecha de entrega:** DD/MM/AAAA
7. Haz clic en **"Create pull request"**

¡Listo! Tu trabajo ha sido entregado y el profesor podrá revisarlo.

---

## 🔄 ¿Cómo agregar más evidencias después?

Si necesitas entregar más evidencias posteriormente:

1. Abre Git Bash o Terminal en la carpeta del repositorio
2. Asegúrate de tener la última versión:
   git pull origin main
3. Crea las nuevas carpetas de evidencia o agrega archivos a las existentes
4. Repite los pasos 6, 7 y 8 (add, commit, push, pull request)

**Puedes hacer varios commits antes de crear el Pull Request final.**

---

## ❓ Preguntas Frecuentes

### ¿Puedo entregar archivos ZIP?
Sí, pero es preferible que subas los archivos individuales para que el profesor pueda verlos directamente en GitHub.

### ¿Qué pasa si me equivoco al subir un archivo?
No te preocupes, puedes hacer otro commit corrigiendo el error y hacer push nuevamente.

### ¿Cuántos Pull Requests debo crear?
Lo ideal es **un Pull Request por unidad**. Si entregas varias evidencias de la misma unidad, inclúyelas todas en el mismo PR.

### ¿Qué formatos de archivo puedo subir?
- Documentos: PDF, DOCX, TXT
- Código: Java, Python, JavaScript, HTML, CSS, etc.
- Imágenes: PNG, JPG, SVG
- Otros: Cualquier archivo relacionado con tu evidencia

**Evita subir archivos muy pesados (mayores a 50 MB).**

### ¿Puedo usar GitHub Desktop en lugar de la terminal?
¡Sí! GitHub Desktop es una herramienta gráfica más amigable:
1. Descárgala desde: [desktop.github.com](https://desktop.github.com)
2. Instálala y conecta tu cuenta de GitHub
3. Clona tu fork del repositorio
4. Haz los cambios en tus archivos
5. En GitHub Desktop verás los cambios, haz commit y push
6. Luego crea el Pull Request desde github.com

---

## 📞 ¿Necesitas ayuda?

Si tienes problemas técnicos:
1. Revisa nuevamente este documento
2. Busca el error en Google (es muy probable que alguien más haya tenido el mismo problema)
3. Contacta al profesor por el canal oficial de comunicación del grupo

---

## ✅ Checklist de entrega

Antes de crear tu Pull Request, verifica que:

- [ ] Tu carpeta está dentro de `entregas/`
- [ ] El nombre de tu carpeta es `APELLIDO_PATERNO_APELLIDO_MATERNO_NOMBRE` (sin espacios, sin acentos)
- [ ] Creaste las carpetas `unidadX/evidenciaY/` correctamente
- [ ] Tus archivos están en la carpeta de evidencia correcta
- [ ] Hiciste `git add .` y `git commit` con un mensaje claro
- [ ] Hiciste `git push` exitosamente
- [ ] Creaste el Pull Request con título y descripción completos
- [ ] El Pull Request apunta al repositorio del profesor (no al tuyo)

---

## 🏆 Buenas prácticas

1. **Nombres de archivos:** Usa nombres descriptivos sin espacios ni caracteres especiales
   - ✅ `diagrama_clases.pdf`, `codigo_patron_factory.java`
   - ❌ `trabajo final (1).pdf`, `código patrón.java`

2. **Mensajes de commit:** Sé claro y conciso
   - ✅ `"Agregar evidencia 1 de unidad 2 - Diagrama de arquitectura"`
   - ❌ `"cambios"`, `"asdasd"`, `"final final ahora sí"`

3. **Organización:** Respeta la estructura de carpetas solicitada

4. **Fechas de entrega:** No esperes al último momento, Git y GitHub pueden tener una curva de aprendizaje al inicio

---

**¡Éxito en tus entregas!** 🎓

---

*Última actualización: Noviembre 2025*
