# Infraestructura Tecnológica (FCEN · UBA) — Guías de Estudio

Repositorio con las guías de estudio visuales e interactivas y el material de las clases de Infraestructura Tecnológica (Exactas · UBA).

## Sitio publicado (GitHub Pages)

Las guías se publican directamente desde la carpeta `guias/` en:

https://lisandrocordoba.github.io/Infra-4B/

Funciona en computadora, iPad y celular. En Safari (iOS/iPadOS) podés usar **Compartir → Agregar a pantalla de inicio** para abrirlas como app.

> **Nota:** el progreso de conceptos estudiados y el tema claro/oscuro se guardan localmente en cada dispositivo y navegador mediante `localStorage`.

## Guías incluidas (`guias/`)

- `guias/index.html` — Hub de estudio con progreso global
- `guias/00-pareto-20-80.html` — Guía 0 · Núcleo Pareto 20/80
- `guias/01-fundamentos-y-redes.html` — Guía 1 · Datacenter, Servidores y Redes Linux (Clase 1)
- `guias/02-kvm-y-preseed.html` — Guía 2 · Virtualización KVM/QEMU/libvirt y Preseed (Clase 2)
- `guias/03-bridges-y-pfsense.html` — Guía 3 · Bridges Linux, NetworkManager y pfSense (Clases 2–3)
- `guias/04-seguridad.html` — Guía 4 · Seguridad de la Información (Clase 4)

## Material de las clases

Los archivos `Clase 1.zip` a `Clase 4.zip` contienen el material original de la cursada.

## Vista previa local

Para abrir las guías localmente con todas sus funciones interactivas (widgets, navegación entre guías y guardado en `localStorage`), levantá un servidor HTTP dentro de `guias/`:

```bash
cd guias
python -m http.server 8000
```

Luego abrí `http://localhost:8000` en tu navegador.
