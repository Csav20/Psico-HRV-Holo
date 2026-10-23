# Psico-HRV-Holo 🇨🇱

### [▶ Abrir la app](https://csav20.github.io/Psico-HRV-Holo/)

Variabilidad de la frecuencia cardiaca (HRV) y sistema nervioso autónomo **en vivo, para la psicología
deportiva**. Conecta una banda de frecuencia cardiaca por Bluetooth y muestra, en el navegador:

- **Sistema nervioso autónomo y HRV:** acelerador (simpático), freno (parasimpático), RMSSD y FC del último minuto.
- **Gemelo fisiológico 3D:** cuerpo, corazón por cavidades, pulmones por lóbulos, nervio vago, cadena simpática
  y cerebro segmentado. Late con la FC medida, respira y se ilumina según el freno y el acelerador.
  Estilos «Atlas» (colores anatómicos) y «Holograma».
- **Holograma de Poincaré 3D, radar cuerpo–mente** (con autoinforme de confianza y ansiedad) y
  **paisaje autonómico** de la sesión.
- **Calidad de los datos:** corrección de artefactos RR; con más de 5 % de latidos anómalos la HRV no se publica.
- **Informe** imprimible (PDF), descarga en HTML, sesión en CSV e intervalos RR en .txt (compatible con Kubios).

**Unidad de Ciencias Aplicadas al Deporte** · Nació en el **Área de Innovación Deportiva** del
**Departamento de Alto Rendimiento** del **Instituto Nacional de Deportes de Chile**.

Autor: **Claudio Abarca Vargas**, PhD, MSc · [claudio.abarca@ind.cl](mailto:claudio.abarca@ind.cl) ·
Desarrollado con la asistencia de IA: Claude (Anthropic)

## Uso

- **Computador o Android:** abra el enlace en **Chrome o Edge**, pulse «Conectar banda FC» y elija su banda
  (servicio estándar de frecuencia cardiaca; para HRV la banda debe enviar intervalos RR, como las bandas torácicas).
- **Desde WhatsApp:** el enlace se abre en el navegador interno; para conectar la banda use «Abrir en Chrome».
- **iPhone:** se ve todo y funciona el **Modo demostración**, pero Safari y Chrome en iOS no permiten Bluetooth web.
- **Sin banda:** «Modo demostración» genera datos de ejemplo, rotulados como tales.
- **Registro:** «Iniciar registro» guarda la sesión (1 muestra/s) para el paisaje y el informe. Los datos quedan
  solo en ese navegador; no se envían a ningún servidor. Recargar la página borra la sesión en curso.
- Si el navegador tiene la GPU desactivada, el gemelo usa un modo 2D de respaldo y vuelve solo al modo completo
  cuando la GPU está disponible.
- Abrir `docs/index.html` desde github.com muestra el código, no la app: use el enlace de arriba.

## Alcance

Visualización educativa de la HRV y del sistema nervioso autónomo. **No es un dispositivo médico ni entrega
diagnósticos.** La iluminación del gemelo y el ECG son ilustrativos; la FR se estima desde la HRV.

## Contenido

GitHub Pages sirve el sitio desde `main:/docs`: `index.html` (la app) y `holo/` (three.js y modelos anatómicos).
Créditos y licencias de terceros en [CREDITS.md](CREDITS.md).

Versión 1.0.0 · 2026-10-23.

© 2026 Claudio Abarca Vargas. Código y diseño: todos los derechos reservados. Los modelos 3D y bibliotecas de
terceros mantienen sus licencias (ver [CREDITS.md](CREDITS.md)).
