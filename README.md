# 📝 Plantilla LaTeX para VS Code

Configuración optimizada de VS Code + LaTeX Workshop para proyectos LaTeX con gestión automática de archivos auxiliares, bibliografía y compilación eficiente.

## 📋 Tabla de Contenidos

- [Características](#-características)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Atajos de Teclado](#%EF%B8%8F-atajos-de-teclado)
- [Recursos Adicionales](#-recursos-adicionales)

## ✨ Características

- ✅ **Directorio de salida organizado**: PDF y archivos auxiliares en carpeta `output/`
- ✅ **Compilación automática**: Al guardar el archivo
- ✅ **Gestión de bibliografía**: Configurado para BibTeX
- ✅ **Limpieza automática**: Elimina archivos auxiliares después de compilar
- ✅ **Visor integrado**: PDF dentro de VS Code
- ✅ **SyncTeX**: Navegación bidireccional entre código y PDF
- ✅ **Editor**: Se limita la longitud máxima de linea
- ✅ **LTex**: Se configura el corrector ortografico a Español

## 📁 Estructura del Proyecto

```
tu-proyecto-latex/
├── .vscode/
│   └── settings.json          # Configuración de LaTeX Workshop
├── output/                     # PDF y archivos auxiliares (auto-generado)
│   ├── documento.pdf
│   ├── documento.aux
│   └── ...
├── imagenes/                   # Recursos gráficos
│   └── ejemplo.png
├── referencias/                # Bibliografía
│   └── bibliografia.bib
├── documento.tex               # Tu documento LaTeX principal
└── README.md                   # Este archivo
```

## ⌨️ Atajos de Teclado

| Acción | Windows/Linux | macOS |
|--------|---------------|-------|
| Compilar | `Ctrl+Alt+B` | `Cmd+Option+B` |
| Ver PDF | `Ctrl+Alt+V` | `Cmd+Option+V` |
| Limpiar auxiliares | `Ctrl+Alt+C` | `Cmd+Option+C` |
| SyncTeX (código → PDF) | `Ctrl+Alt+J` | `Cmd+Option+J` |
| SyncTeX (PDF → código) | `Ctrl+Click` en PDF | `Cmd+Click` en PDF |

## 📚 Recursos Adicionales

- [Documentación LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop/wiki)
- [Overleaf - Aprende LaTeX](https://www.overleaf.com/learn)
- [LaTeX Wikibook](https://en.wikibooks.org/wiki/LaTeX)
- [Detexify](http://detexify.kirelabs.org/classify.html) - Encuentra símbolos LaTeX dibujándolos
- [Manualdelatex](https://manualdelatex.com/tutoriales/crear-un-documento)
