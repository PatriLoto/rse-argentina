# RSE Argentina - Sitio Web

Este es el repositorio del sitio web de RSE Argentina (Research Software Engineering Argentina), construido con [Quarto](https://quarto.org/).

## 🚀 Inicio rápido

### Prerrequisitos

- [Quarto](https://quarto.org/docs/get-started/) (versión 1.3 o superior)
- [Git](https://git-scm.com/)
- Rstudio 

### Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/rse-argentina/website.git
cd website
```

2. Renderiza el sitio localmente:
```bash
quarto preview
```

El sitio estará disponible en `http://localhost:4000`

## 📁 Estructura del proyecto

```
rse-argentina/
├── _quarto.yml          # Configuración principal del sitio
├── index.qmd            # Página principal
├── quienes-somos.qmd    # Página del equipo
├── recursos.qmd         # Página de recursos
├── contacto.qmd         # Página de contacto
├── styles.css           # Estilos personalizados
├── docs/                # Sitio renderizado (no editar)
└── README.md            # Este archivo
```

### Agregar un recurso

Edita el archivo `recursos.qmd` y agrega el recurso en la sección correspondiente:

```markdown
- 📚 **[Nombre del recurso](https://link.com)** - Descripción breve
```

## 🚀 Despliegue

### GitHub Pages (Recomendado)

1. En GitHub, ve a Settings → Pages
2. Selecciona "Deploy from a branch"
3. Elige la rama `main` y carpeta `/docs`
4. Guarda y espera unos minutos

El sitio estará en: `https://rse-argentina.github.io/`

## 📄 Licencia

Este sitio está bajo licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Eres libre de compartir y adaptar el material, dando crédito apropiado.

## 🙏 Agradecimientos

- [RSE Chile](https://rse-chile.github.io/) por la inspiración

---

**Última actualización**: Noviembre 2025
