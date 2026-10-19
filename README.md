# República de los Bloques — Minecraft 26.3

Mods del servidor República de los Bloques. **Se instala una vez y luego se actualiza solo** cada vez que pulsas *Jugar*.

**Versión actual: 0.5.0** (publicada el 19/10/2026 21:39)

Novedad: guia de la cooperativa dentro del juego (tecla G o el libro rojo del inventario) y pestana "Republica de los Bloques" en creativo. Incluye MCA Remastered: los aldeanos del pueblo son personas con nombre y personalidad.

## Descargar

**[⬇ Descargar el instalador](https://github.com/albuki98/mc-republica-26.3/raw/main/descargas/Republica-de-los-Bloques-Instalador.zip)**

## Instalar (solo la primera vez)

1. Ten **Minecraft Java 26.3** abierto al menos una vez desde el launcher oficial.
2. Instala **Fabric** para 26.3: <https://fabricmc.net/use/installer/> → *Download for Windows* → pestaña *Client*, versión 26.3 → *Install*.
3. Cierra el launcher. Descomprime el ZIP (clic derecho → *Extraer todo*) y haz doble clic en **`Instalar.bat`**.
4. Abre el launcher, elige **«Republica de los Bloques 26.3»** junto al botón *Jugar* y juega.
   La primera vez sale una ventanita descargando los mods.
5. La dirección del servidor te la da el administrador por privado (si ya jugabas, ya está en tu lista de Multijugador). Tu nombre tiene que estar en la lista blanca.

A partir de ahí no tienes que hacer nada: cuando haya una versión nueva se descarga sola al darle a *Jugar*.
Si el juego ya estaba abierto cuando se actualizó el servidor, ciérralo y vuelve a abrirlo.

## Qué incluye

- `chisel-fabric-2.2.1+mc26.3.jar`
- `cooperativa-cigarros-0.5.0.jar`
- `cooperativa-cuadros-0.5.0.jar`
- `cooperativa-decoracion-0.5.0.jar`
- `cooperativa-esculpido-0.5.0.jar`
- `cooperativa-estandartes-0.5.0.jar`
- `cooperativa-nucleo-0.5.0.jar`
- `cooperativa-vestimenta-0.5.0.jar`
- `cooperativa-vida-0.5.0.jar`
- `cryonicconfig-fabric-1.0.0+mc26.3.jar`
- `fabric-api-0.162.0+26.3.jar`
- `mcarem-fabric-8.2.0+26.3.jar`

## Cómo funciona

El perfil del launcher carga un pequeño actualizador antes del juego. Lee `manifiesto.txt` de este repositorio,
comprueba su **firma** (solo el administrador del servidor puede publicar versiones) y el **SHA-256** de cada archivo, descarga lo que
falte y aparta los mods viejos en `mods-antiguos`. Sin conexión, el juego arranca con lo que ya tienes.
Registro en `%appdata%\.minecraft\republica-26.3\actualizador\actualizador.log`.

## Licencias y créditos

Los mods `cooperativa-*` son del servidor (MIT). Se redistribuyen sin modificar:

- Fabric API — Apache-2.0 — <https://github.com/FabricMC/fabric>
- Chisel Reborn — GPL-2.0 — <https://github.com/matthewperiut/Chisel-Reborn>
- Cryonic Config — MIT — <https://github.com/matthewperiut/cryonicconfig>
- Minecraft Comes Alive Remastered — GPL-3.0 — <https://github.com/AncientKira21/mcarem>

Secuencia de publicación: 3.
