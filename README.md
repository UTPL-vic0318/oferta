# Portal de Oferta Académica Institucional

Este proyecto es un portal web estático construido para mostrar la oferta académica de la institución, cumpliendo un conjunto de restricciones y requerimientos técnicos específicos.

## 🎯 Objetivos del Proyecto
La solución implementada satisface los siguientes requerimientos:
- Informar estrictamente sobre: **Facultades**, **Carreras** y el **Título** que otorgan.
- Exclusión total de mallas curriculares o texto descriptivo excesivo, manteniendo la página como un panel de datos tabular.
- Navegación precisa desde un índice en la parte superior.
- Control de versiones mediante el flujo de **Git** (historial de modificaciones ordenado).
- Integración Continua (CI/CD) mediante **GitHub Actions** para publicar actualizaciones automáticamente.

## ⚙️ Tecnologías Utilizadas
- **[MkDocs](https://www.mkdocs.org/):** Framework para la generación del sitio web en páginas HTML estáticas a través de código Markdown. Ofrece compatibilidad con cualquier navegador moderno sin requerir servidores de base de datos.
- **[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/):** El entorno gráfico y tema utilizado para dar un aspecto responsivo, visualmente avanzado y profesional.

## 🚀 Cómo ejecutar en modo local
Si deseas hacer cambios de manera local y verlos en tiempo real antes de subir a Internet:

1. Asegúrate de tener Python y MkDocs instalado (`pip install mkdocs mkdocs-material`).
2. Abre tu terminal en la raíz de este proyecto.
3. Ejecuta el comando:
   ```bash
   python -m mkdocs serve
   ```
4. Ingresa desde cualquier navegador a `http://127.0.0.1:8000/`.
