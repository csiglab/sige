> Sistema Integral de  Gestion  Empresarial **(SIGE)**.

**Partes**:
- **Elaboración / Comunicación**: Listado de comunicaciones.
- **Plan / Ejecución**: Articulos, Análisis, 
- **Módelo / Gestión**: Listado de articulos / notebooks acerca del funcionamiento de la empresa.
- ...

## Building & Running

```bash
docker run --rm -v "$PWD:/srv/jekyll" -it jekyll/jekyll:latest jekyll new . --force
```

```bash
docker run --rm -v "$PWD:/srv/jekyll" -it jekyll/jekyll:latest jekyll build
```

```bash
docker run --rm -v "$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:latest jekyll serve
```