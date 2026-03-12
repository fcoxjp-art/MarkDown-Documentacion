# ¿Por qué usar una wiki de GitHub para tu proyecto?
![img](https://integrio.net/static/d75d11762c6f6b496fa1c179af76ca66/technical-documentation-in-software-development.png)

## 1. Pensada para perfiles técnicos
Una **wiki de GitHub** está orientada principalmente a **desarrolladores, arquitectos, analistas y otras personas con conocimientos técnicos**.  

Por ello una wiki dentro de esta plataforma resulta ideal para **documentación técnica **.  

## 2. No está pensada para el cliente o consumidor
**Una wiki de GitHub está diseñada para el equipo técnico detras de la magia.  
En proyectos **open source**, esto suele ser menos problemático, ya que el público objetivo generalmente es **experto en tecnología**.

---

## 💡 Consejo

Puede ser útil **visualizar las páginas de la wiki localmente mientras las editas**, especialmente si prefieres editores locales en lugar del editor web de GitHub.

- **VS Code**  
  - Buenas herramientas de edición  
  - Con extensiones, permite visualizar diagramas de la wiki  

- **Línea de comandos**  
  - Una buena herramienta de visualización es **mdv**  
  - No es compatible con diagramas de la wiki  
  - Depende de **Pandoc** y de un navegador de línea de comandos (por defecto **Lynx**)

---

# ¿Para qué sirve una wiki de GitHub?

Una wiki de GitHub es útil para:

- Documentar **proyectos de código abierto alojados en GitHub**
- Mantener **documentación separada del código fuente**, como por ejemplo:
  - Documentación de **API**
- Compartir **diagramas** con:
  - desarrolladores
  - arquitectos
  - áreas de negocio
- Registrar discusiones técnicas, como por ejemplo:
  - **ADR (Architecture Decision Records)** o *registros de decisiones de arquitectura*
- Mantener la **documentación bajo control de versiones**, igual que el código del proyecto
- Permitir que **cualquier persona (desarrolladores o terceros)** pueda **editar la documentación fácilmente y en lenguaje sencillo**

---

# Activar la Wiki en un repositorio

Antes de comenzar a usar la wiki, es necesario verificar que esté habilitada.

### Paso 1: Acceder al repositorio
1. Inicia sesión en GitHub.
2. Abre el repositorio donde deseas crear la documentación.

### Paso 2: Verificar la pestaña Wiki
En la barra superior del repositorio aparecerán varias opciones:

- Code  
- Issues  
- Pull Requests  
- Actions  
- Projects  
- **Wiki**

Si la opción **Wiki** aparece, significa que está habilitada.

### Paso 3: Activarla (si está deshabilitada)

1. Ir a **Settings** del repositorio.
2. Buscar la sección **Features**.
3. Activar la opción **Wikis**.

---

# 3. Crear la primera página de la Wiki

### Paso 1: Abrir la sección Wiki
1. Dentro del repositorio, hacer clic en **Wiki**.

### Paso 2: Crear la página inicial
1. Seleccionar **Create the first page**.

### Paso 3: Escribir el contenido
Se abrirá un editor donde podrás escribir usando **Markdown**.

---
### Paso 4: Guardar la página
1. Escribir un mensaje de cambio (commit message).
2. Hacer clic en **Save Page**.

---

# 4. Crear nuevas páginas

Las wikis permiten tener múltiples páginas para organizar la documentación.

### Paso 1
Dentro de la wiki, hacer clic en **New Page**.

### Paso 2
Asignar un nombre a la página.

---

# 5. Editar páginas existentes

Para modificar una página:

1. Abrir la página en la wiki.
2. Hacer clic en **Edit**.
3. Realizar los cambios necesarios.
4. Guardar los cambios.

GitHub almacenará el historial de modificaciones.

---

# 6. Clonar la Wiki localmente

Las wikis son repositorios Git independientes, por lo que pueden clonarse.

### Paso 1
Copiar la URL del repositorio de la wiki.

Generalmente tiene este formato:

https://github.com/usuario/repositorio.wiki.git


### Paso 2
Clonar la wiki:

git clone https://github.com/usuario/repositorio.wiki.git

### Paso 3
Editar los archivos Markdown localmente.

### Paso 4
Enviar cambios al repositorio:

git add .
git commit -m "Actualización de documentación"
git push

---
