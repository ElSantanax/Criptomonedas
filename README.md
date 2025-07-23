# Cotizador de Criptomonedas

Este proyecto es una aplicación web sencilla que permite consultar el precio actualizado de las principales criptomonedas en diferentes monedas fiat (USD, MXN, GBP, EUR).

## Características
- Consulta en tiempo real de precios de criptomonedas usando la API de [CryptoCompare](https://min-api.cryptocompare.com/).
- Selección de moneda fiat y criptomoneda.
- Interfaz responsiva y moderna basada en el framework [Skeleton](http://getskeleton.com/).
- Indicador visual de carga (spinner) y manejo de errores.

## Estructura del proyecto

```
├── index.html           # Página principal
├── js/
│   └── app.js           # Lógica principal de la aplicación
├── css/
│   ├── app.css          # Estilos personalizados
│   ├── skeleton.css     # Framework CSS Skeleton
│   └── normalize.css    # Normalización de estilos entre navegadores
├── img/
│   └── cryptomonedas.png # Imagen ilustrativa
```

## Instalación y uso
1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en tu navegador web favorito.
3. Selecciona una moneda y una criptomoneda, luego haz clic en "Cotizar" para ver el precio actualizado.

No se requiere instalación de dependencias ni servidor backend: todo funciona en el navegador.

## Créditos y licencias
- **Skeleton CSS**: [MIT License](http://www.opensource.org/licenses/mit-license.php) — © Dave Gamache
- **normalize.css**: [MIT License](https://github.com/necolas/normalize.css/blob/master/LICENSE.md)
- **CryptoCompare API**: [Términos de uso](https://min-api.cryptocompare.com/)

## Notas
- Este proyecto es solo para fines educativos y demostrativos.
- Los precios y datos mostrados dependen de la disponibilidad de la API pública de CryptoCompare. 