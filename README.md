# pg1590.github.io

Source for my portfolio site, **[pg1590.github.io](https://pg1590.github.io)**: software and robotics projects, an interactive PID follower playground, and my resume.

Built with [Astro](https://astro.build) and deployed to GitHub Pages by the workflow in `.github/workflows/deploy.yml` on every push to `main`.

## Develop

```sh
npm install
npm run dev       # http://localhost:4321
npm run build     # static site in dist/
```

## Layout

| Path | Contents |
| --- | --- |
| `src/pages/index.astro` | The page, assembled from section components |
| `src/components/` | Hero, Work, Playground, MoreProjects, Experience, About, Contact |
| `src/components/charts/` | Inline SVG charts (flight log, FPGA DSP usage) |
| `src/data/` | Data behind the charts |
| `public/media/` | Videos, posters, and images |
| `resume/resume.tex` | One-page resume; build with `pdflatex` and copy the PDF to `public/` |
