# Demon List GD

Clasificación comunitaria de Geometry Dash inspirada en Global Demonlist.

## Publicar con GitHub Pages

1. Abre **Settings → Pages** en este repositorio.
2. En **Build and deployment → Source**, selecciona **GitHub Actions**.
3. Abre **Actions** y comprueba que el workflow **Deploy Demon List to GitHub Pages** termine correctamente.
4. La URL pública aparecerá en **Settings → Pages**.

## Escala de puntos

La lista usa una escala propia donde Grief, en la posición global #1, equivale a **1,000.00 puntos**. La fórmula aplicada es:

`puntos de completion = 1000 / √posición`

Las progresiones parciales reciben la proporción correspondiente al porcentaje conseguido. Por ejemplo, una progresión del 73% recibe el 73% del valor del nivel.

Esta fórmula es una decisión de esta web y **no es la fórmula oficial de Global Demonlist**. Las posiciones de Bloodlust (#293) y Shardscapes (#268) se muestran como referencias de Global Demonlist y pueden cambiar cuando esa lista se actualice.

## Récord inicial de GuitarHeroStyles

- Bloodlust — 100% (completion).
- Shardscapes — 73% (progreso).

Con las posiciones de referencia actuales, la web calcula aproximadamente **103.01 puntos** en total.

## Datos y limitaciones

- La web guarda los cambios en `localStorage`; los récords añadidos desde un dispositivo no se sincronizan automáticamente con otros visitantes.
- Los niveles añadidos por el formulario quedan pendientes de clasificación y no dan puntos hasta que se les asigne una posición.
- Los récords iniciales son datos comunitarios precargados; la web no los verifica automáticamente.
- Para una clasificación pública colaborativa hacen falta una base de datos compartida y un sistema de moderación de pruebas.
