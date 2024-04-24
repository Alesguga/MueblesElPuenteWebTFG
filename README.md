# 🛏️ Web muebles el puente 🛋️

### El proyecto consiste en la parte web de el TFG en la cual mejoro la pagina web de [Muebles el Puente](https://muebleselpuente.com/) 

## ¿Porque elegí Astro 🚀?

Cuando se trata de construir sitios web modernos, hay muchas herramientas para elegir, pero Astro me llamó la atención por estas razones:

- **Rendimiento estelar:** Astro genera sitios estáticos por defecto, lo que significa que las páginas cargan súper rápido. No hay JavaScript innecesario enviado al navegador, por lo que los usuarios obtienen una experiencia más rápida y suave desde el primer clic.
- **Componentes reutilizables:** Es genial que con tailwind CSS y HTML pueda crear componentes al estilo React,Vue o Svelte.
- **Menos JS, por favor:** La mayoría de las paginas cargan y cargan javascript haciendolas mas lentas de funcionar,  Astro va en la dirección opuesta. Solo carga el JavaScript que necesitas, donde lo necesitas.
- **Union de tecnologías:** Porque solo usar una librería frontend pudiendo usar a la vez React,Vue... En el mismo proyecto
- **Cambios al instante:** Como con LiveServer con HTML puro con Astro los cambios se reflejan al instante en la web.
- **SEO facilitado:** Dado que Astro pre-renderiza contenido en HTML, los motores de búsqueda lo adoran, lo que facilita que mis proyectos sean encontrados por la audiencia que los busca.

## ⚡ Inicio rápido con astro 

Puedes usar el aministrador de paquetes que quieras ya sea pnpm, npm...

```sh
bun create astro@latest

npm create astro@latest

pnpm create astro@latest
```

## 🚀 Estructura del proyecto


```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── fonts/
│   │   │   └── ITC Bauhaus
│   │   ├── icons/
│   │   │   └── Todos los SVG
│   │   ├── botonIconico.astro
│   │   ├── Conocenos.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── HeaderAu.astro
│   │   ├── HeaderD.astro
│   │   ├── HeaderJu.astro
│   │   ├── HeaderMi.astro
│   │   ├── HeaderSo.astro
│   │   ├── ImageGallery.astro
│   │   ├── ImgConocenos.astro
│   │   ├── ModalAviso.astro
│   │   ├── ModalP.astro
│   │   └── ... (otros archivos de componentes)
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       ├── 404.astro
│       ├── contacto.astro
│       ├── descanso.astro
│       └── auxdeco/
│       │   └── ... (otros archivos o carpetas relacionadas con auxdeco)
│       ├── dormitorios/
│       │   └── ... (otros archivos o carpetas relacionadas con dormitorios)
│       ├── juveniles/
│       │   └── ... (otros archivos o carpetas relacionadas con juveniles)
│       ├── salones/
│       │   └── ... (otros archivos o carpetas relacionadas con salones)
│       └── tapiceria/
│           └── ... (otros archivos o carpetas relacionadas con tapiceria)
├── package.json
└── ... (otros archivos o directorios en la raíz del proyecto como .gitignore, README.md, etc.)


```



## 💻 Comandos Astro 


| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
|bun install`               | Installs dependencies                            |
| `bun run dev`             | Starts local dev server at `localhost:4321`      |
| `bun run build`           | Build your production site to `./dist/`          |
| `bun run preview`         | Preview your build locally, before deploying     |
| `bun run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun run astro -- --help` | Get help using the Astro CLI                     |
| `bun install @midudev/tailwind-animations` | Get help using the Astro CLI    |


### 💨 Dentro del tailwind config

    import animations from '@midudev/tailwind-animations'

    export default {
    // ...rest of the options
    plugins: [animations],
    }

## 👀 Docu que me ha ayudado

- Documentacion original de [astro](https://docs.astro.build).
- Flowbite [Componentes de tailwind ya creados](https://flowbite.com/)
- Material tailwind [Ideas que he sacado para hacer el form](https://www.material-tailwind.com/)
- Clases de [tailwind](https://tailwindcss.com/)
- Svgs de grandisima calidad [Svgl](https://svgl.vercel.app/)
- Aprendizaje ts,astro [Midudev](https://midu.dev/)