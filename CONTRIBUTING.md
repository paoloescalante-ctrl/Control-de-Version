# Guía de contribución

Gracias por tu interés en mejorar **Control-de-Version**. Este es un proyecto educativo pequeño, así que las reglas son simples. Léelas antes de enviar cambios.

## Tabla de contenidos

- [Guía de contribución](#guía-de-contribución)
  - [Tabla de contenidos](#tabla-de-contenidos)
  - [Cómo reportar un problema](#cómo-reportar-un-problema)
  - [Flujo de trabajo](#flujo-de-trabajo)
  - [Reglas para los commits](#reglas-para-los-commits)
  - [Estilo del código](#estilo-del-código)
  - [Antes de abrir el pull request](#antes-de-abrir-el-pull-request)

## Cómo reportar un problema

Abre un *issue* en el repositorio e incluye:

- Qué esperabas que pasara y qué pasó en realidad.
- Los pasos para reproducirlo.
- El navegador y el sistema operativo que usas.

## Flujo de trabajo

1. Haz un *fork* del repositorio y clónalo:

   ```bash
   git clone https://github.com/TU-USUARIO/Control-de-Version.git
   cd Control-de-Version
   ```

2. Crea una rama a partir de `main`. No trabajes directamente sobre `main`:

   ```bash
   git checkout -b nombre-de-tu-rama
   ```

3. Haz tus cambios y registra cada uno con `git add` y `git commit`.
4. Sube tu rama a tu fork:

   ```bash
   git push -u origin nombre-de-tu-rama
   ```

5. Abre un *pull request* hacia la rama `main` de este repositorio.

## Reglas para los commits

- Escribe el mensaje en español y en presente, empezando con un verbo: `Agrega`, `Corrige`, `Actualiza`, `Elimina`.
- El mensaje debe decir qué cambió. Evita mensajes como `cambios` o `arreglo`.
- Haz un commit por cada cambio lógico. No mezcles estilos y contenido en el mismo commit.

| Mensaje poco claro | Mensaje descriptivo |
|:--|:--|
| `cambios` | `Centra el título y agrega línea inferior` |
| `arreglo` | `Corrige el enlace a styles.css en index.html` |
| `update` | `Actualiza la hoja de ruta del README` |

## Estilo del código

- Usa dos espacios de sangría en HTML y CSS.
- Escribe las etiquetas y propiedades en minúsculas.
- Mantén el atributo `lang="es"` y la codificación `UTF-8` en `index.html`.
- No subas archivos con contraseñas o claves. El archivo `.gitignore` ya excluye `.env`.

## Antes de abrir el pull request

- [ ] Abriste `index.html` en el navegador y la página se ve bien.
- [ ] Tu rama parte de la versión más reciente de `main`.
- [ ] Los mensajes de tus commits son claros.
- [ ] Describiste en el pull request qué cambiaste y por qué.

Si tienes dudas, abre un *issue* y lo conversamos antes de que inviertas tiempo en el cambio.