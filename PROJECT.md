<!-- managed-by-telegram-cursor-bot:agent-kit -->
# Contexto del proyecto

## Produccion
- URL: https://github.com/Marcos1995/gasolineras
- Vista: https://marcos1995.github.io/gasolineras/ (repo público; Chrome)
- Vista local: `index.html` (con red; la página pide la API del Ministerio)

## Estado
- Mapa de España por provincia: gasolina 95, 98, diésel y GLP, con el precio oficial en vivo.
- Por distancia: si hay GPS, los km salen de ese punto aunque muevas el mapa; si no, del centro de lo que estás viendo. Por precio no usa un lugar.
- Ruta dibuja el camino en coche desde el GPS con OSRM (OpenStreetMap): minutos y kilómetros, sin tráfico en vivo.
- La propia API dice que los precios se actualizan cada media hora. Recargar antes no aporta.
- La recarga eléctrica no entra: el €/kWh no está en una API pública anónima.

## Stack
- Un `index.html` (CSS y JS dentro). Leaflet 1.9.4 y teselas de OpenStreetMap. Sin build y sin API de pago.

## Comandos utiles
- Instalar: nada
- Test: abrir la página y comprobar que sale el sello de fecha del Ministerio
- Dev: `python -m http.server` en la raíz y abrir la URL local

## Notas para el agente
- Supuesto: España. Fuente `ServiciosRESTCarburantes` (CORS abierto). Provincia por `FiltroProvincia`; el listado nacional pesa 12 MB.
- «Cerca de mí» elige la provincia por un centro aproximado; en el límite el usuario puede cambiar el desplegable.
- No cachear precios. No añadir puntos de recarga sin precio.
- Lean kit (ver AGENTS.md)
