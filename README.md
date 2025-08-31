# WikiChat Documentation

Esta es la documentación oficial de WikiChat, construida con Mintlify.

## Desarrollo Local

### Prerrequisitos

Asegúrate de tener Node.js (versión 18.10.0 o superior) instalado.

### Instalación

1. Clona este repositorio
2. Instala las dependencias:
   ```bash
   npm install
   ```

### Ejecutar en modo desarrollo

Para previsualizar los cambios localmente:

```bash
npm run dev
```

También puedes usar el CLI de Mintlify directamente:

```bash
npm i -g mint
mint dev
```

La documentación estará disponible en `http://localhost:3000`.

## Estructura del Proyecto

```
├── docs.json                # Configuración principal de Mintlify
├── introduction.mdx         # Página de introducción
├── quickstart.mdx          # Guía de inicio rápido
├── development.mdx         # Guía de desarrollo
├── essentials/             # Documentación esencial
│   ├── markdown.mdx
│   ├── code.mdx
│   ├── settings.mdx
│   └── navigation.mdx
├── api-reference/          # Referencia de la API
│   ├── introduction.mdx
│   └── endpoint/
│       ├── get.mdx
│       ├── create.mdx
│       └── delete.mdx
├── images/                 # Imágenes y assets
├── logo/                   # Logos (claro y oscuro)
└── package.json
```

## Personalización

### Colores

Los colores del tema están definidos en `docs.json`:

```json
{
  "colors": {
    "primary": "#0D9373",
    "light": "#07C983",
    "dark": "#0D9373"
  }
}
```

### Logo

Los logos se encuentran en la carpeta `/logo/`:
- `light.svg` - Logo para tema claro
- `dark.svg` - Logo para tema oscuro

### Favicon

El favicon está en la raíz del proyecto como `favicon.svg`.

## Deployment

Para desplegar la documentación:

1. Instala la app de GitHub desde tu [dashboard](https://dashboard.mintlify.com/settings/organization/github-app)
2. Los cambios se desplegarán automáticamente cuando hagas push a main/master

## Contribuir

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-caracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## Recursos

- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify community](https://mintlify.com/community)
