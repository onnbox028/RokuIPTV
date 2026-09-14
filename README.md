# RokuIPTV

Lista principal de canales de la app **MM-IPTV** para Roku.

- `lista-principal.json`: la que baja la app.
- `lista-principal.m3u`: la misma lista en M3U, para cualquier otro reproductor.
- `lista-principal-informe.txt`: qué entró de cada fuente y por qué no entró el resto.

La arma `tools/armar-lista-principal.py` del proyecto MM-IPTV. Prueba cada
canal de las listas fuente con la misma lógica de la app, y deja solo los canales
en vivo que funcionan al momento de armarla.
