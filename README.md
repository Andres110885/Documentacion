# Documentación

App local para tener a mano la documentación importante de la familia, organizada por persona y por documento (frente/reverso). No sube nada a internet: se abre desde el propio archivo.

## Cómo usarla
1. Abre `index.html` en el navegador (doble clic).
2. Entra en una persona y verás sus documentos. Cada hueco vacío te dice el nombre que debe tener la foto.
3. Guarda las fotos en la carpeta `img/` con ese nombre exacto (ej. `andres_dni_frente.jpg`).
4. Recarga la app: la foto aparece sola y la barra de progreso sube.

## Personas y documentos
- **Andrés:** DNI, carnet de conducir, pasaporte, Seguridad Social, Adeslas, libro de familia, familia numerosa.
- **Leo, Miah, Alex:** DNI, pasaporte, Seguridad Social, tarjeta sanitaria, Adeslas, familia numerosa, cartilla de vacunación, foto para el cole.

## Nombres de archivo
`persona_documento_lado.jpg` — personas: `andres`, `leo`, `miah`, `alex`.
Ejemplos: `andres_dni_reverso.jpg`, `leo_fotocole_unico.jpg`, `miah_sanitaria_frente.jpg`.

## Añadir fotos y pasarlas al móvil
- Toca un hueco de un documento: en el ordenador se abre el explorador; en el móvil, la cámara o la galería. La foto se guarda sola con el nombre correcto.
- Las fotos se guardan en el navegador **de ese dispositivo**.
- Para pasar todo del ordenador al móvil: pulsa **⬇ Exportar** (crea `documentacion-copia.json` con todas las fotos), pasa ese archivo al móvil (AirDrop, cable, correo, etc.), abre la app en el móvil y pulsa **⬆ Importar**. A partir de ahí trabaja solo desde el móvil.
- Consejo: cuando pases a trabajar solo en el móvil, ese será el dispositivo "oficial". Haz un Exportar de vez en cuando como copia de seguridad.

## PIN opcional
En `index.html`, arriba del bloque del PIN: pon `PIN_ACTIVO = true` y cambia `PIN_CODE`. Es un candado ligero del propio archivo, no cifrado.

## Seguridad / privacidad
- Son documentos sensibles. **No publiques esto en GitHub Pages ni en ningún sitio público.**
- Si lo guardas en GitHub, que el repositorio sea **privado**.
- En el móvil, ábrelo solo desde una carpeta a la que accedas únicamente tú.

## En el móvil
Sincroniza toda esta carpeta (carpeta + `img/`) al teléfono y abre `index.html`. Al añadirlo a la pantalla de inicio usará el icono incluido.
