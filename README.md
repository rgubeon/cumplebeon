# Cumple de Rafa y Karen 🎂

Invitación fea y absurda (a propósito) para el cumple de Rafa (26) y Karen (27).

- **Día:** martes 3 de noviembre de 2026
- **Hora:** 15:00, almuerzo todos juntos

## Uso

Web estática, sin build. Abre `index.html` o publícala con GitHub Pages:

1. Sube el repo a GitHub.
2. *Settings → Pages → Deploy from a branch → `main` / root*.
3. La web queda en `https://<usuario>.github.io/cumple-rafa-karen/`.

La música arranca al pulsar «Aceptar» en la ventana inicial (los navegadores bloquean el audio automático).

## Lista VIP

Al pulsar «SÍ» se pide el nombre y se añade a la lista. Se puede cambiar el nombre, desapuntarse,
apuntar a más gente y quitar a cualquiera con la ✕.

Los nombres se guardan en el `localStorage` del navegador: sobreviven a recargas,
pero cada navegador tiene su propia lista. Para una lista compartida entre todos haría falta un backend
(Supabase, Firebase…); la única pieza a cambiar es el bloque `<script>` que define `window.claude`.

## Estructura

```
index.html         # todo el HTML, CSS y JS
assets/rafa.png
assets/karen.png
assets/fiesta.mp3  # música de fondo
```
