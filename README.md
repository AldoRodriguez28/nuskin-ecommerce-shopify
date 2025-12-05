# Nuskin Ecommerce Shopify

Estructura base para conectar este repo con el theme Dawn de Shopify usando Shopify CLI.

## Pasos rapidos

1. Instala Shopify CLI 3.x y autenticate: `shopify login --store <tu-tienda.myshopify.com>`.
2. Duplica el theme Dawn en tu tienda y copia el `theme_id` (Admin > Online Store > Themes > ... > Edit code).
3. Completa los valores en `shopify.theme.toml` o exporta variables usando `.env.example`.
4. Descarga el theme al repo: `shopify theme pull --environment dawn`.
5. Para subir cambios de vuelta: `shopify theme push --environment dawn`.

La estructura de carpetas (`assets/`, `config/`, `layout/`, `locales/`, `sections/`, `snippets/`, `templates/`) ya esta creada con `.gitkeep` para poder versionar desde cero.
