# FisioLáser Madrid (Retiro) · Mockup landing 2026

Mockup de evolución visual para la web de FisioLáser Madrid, centrado en hernia/protusión y edema óseo, con enfoque de marca moderno y orientado a conversión.

## Qué incluye

- Hero principal con mensaje de valor claro y CTAs visibles.
- Navegación por secciones clínicas clave.
- Bloques de servicios, proceso, beneficios, precios y casos.
- FAQ y bloque de contacto completo.
- Diseño responsive (desktop/tablet/móvil).

## Stack

- HTML5
- CSS3

## Archivos principales

- `index.html`
- `styles.css`

## Ver el mockup en local

Opción rápida en VS Code:

1. Instala la extensión **Live Server**.
2. Clic derecho en `index.html`.
3. Selecciona **Open with Live Server**.

## Preparar y subir a GitHub

Desde la carpeta del proyecto:

```bash
git init
git add .
git commit -m "feat: mockup landing moderna fisiolaser"
```

### Crear repositorio remoto

#### Opción A (web GitHub)

1. Crea un nuevo repo vacío en GitHub (por ejemplo `fisiolaser-mockup`).
2. Copia la URL del repo.
3. Ejecuta:

```bash
git remote add origin <URL_DEL_REPO>
git branch -M main
git push -u origin main
```

#### Opción B (GitHub CLI)

```bash
gh repo create fisiolaser-mockup --public --source=. --remote=origin --push
```

## Nota

Este proyecto es una maqueta de presentación. Antes de producción, conviene integrar:

- Política de privacidad y aviso legal definitivo.
- Formulario conectado a backend/CRM real.
- Medición (Google Analytics/Meta Pixel) y eventos de conversión.
