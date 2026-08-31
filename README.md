# Ancapistánský filozofický týdeník

Zdroj webu [goofyass1231561.github.io](https://goofyass1231561.github.io/).

Obsah je v `content/`. Každý push do větve `v4` spustí `.github/workflows/deploy.yml`,
který nainstaluje závislosti, sestaví lokální Quartz z tohoto repozitáře a nasadí `public/`
na GitHub Pages. Lokální `npx quartz build` ani `npx quartz sync` nejsou pro deploy potřeba.
