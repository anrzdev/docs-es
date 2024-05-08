# vuejs.org

## Contribucion

Este sitio esta construido con [VitePress](https://github.com/vuejs/vitepress) y depende de [@vue/theme](https://github.com/vuejs/vue-theme). El contenido del sitio esta escrito en formato Markdown localizado en `src`. Para simples ediciones, tu puedes directamente editar el archivo en GitHub y generar una Pull Request.

Para desarrollo local, [pnpm](https://pnpm.io) es preferible como manejador de paquetes.

```bash
pnpm i
pnpm run dev
```

Este proyecto requiere que Node.js sea `v14.0.0` o superior, porque nosotros usamos las nuevas caracteristicas de JavaScript en nuestro codigo, como el optional chaining.

## Trabajando en el contenido

- Consulta la documentación de VitePress sobre las [extensiones de Markdown admitidas](https://vitepress.dev/guide/markdown) y la capacidad de [usar sintaxis de Vue dentro de Markdown](https://vitepress.dev/guide/using-vue).

- Mira la [guia de escritura](https://github.com/vuejs/docs/blob/main/.github/contributing/writing-guide.md) para nuestras reglas y recomendaciones en la escritura y mantenimiento del contenido de la documentación.

## Trabajando en el tema

Si necesitas hacer cambios en el tema, mira las [instrucciones para el desarrollo del tema junto a la documentación](https://github.com/vuejs/vue-theme#developing-with-real-content).