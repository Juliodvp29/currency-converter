# Conversor de Divisas

Una aplicación web moderna para convertir divisas en tiempo real, construida con Astro y Tailwind CSS. Permite realizar conversiones instantáneas entre múltiples monedas y visualizar el histórico de tasas de cambio en un gráfico interactivo.

## 🚀 Características

- **Conversión en tiempo real**: Convierte cantidades entre diferentes monedas usando APIs externas actualizadas.
- **Múltiples monedas**: Soporta USD, EUR, GBP, JPY, COP, MXN y ARS.
- **Histórico de tasas**: Visualiza las fluctuaciones de las tasas de cambio en los últimos 30 días con un gráfico interactivo.
- **Interfaz moderna**: Diseño responsivo con gradientes y efectos de vidrio usando Tailwind CSS.

## 🛠️ Tecnologías Utilizadas

- **Astro**: Framework para construir sitios web rápidos y optimizados.
- **Tailwind CSS**: Framework de CSS para estilos modernos y responsivos.
- **Chart.js**: Librería para crear gráficos interactivos.
- **Axios**: Cliente HTTP para realizar peticiones a las APIs.
- **TypeScript**: Para tipado estático en el código JavaScript.

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/currency-converter.git
   cd currency-converter
   ```

2. Instala las dependencias:
   ```bash
   pnpm install
   ```

3. Configura las variables de entorno:
   Crea un archivo `.env` en la raíz del proyecto y agrega tu clave API:
   ```
   PUBLIC_EXCHANGE_API_KEY=tu_clave_api_de_currencylayer
   ```

4. Ejecuta el servidor de desarrollo:
   ```bash
   pnpm dev
   ```

   La aplicación estará disponible en `http://localhost:4321`.

## 🔑 APIs Utilizadas

- **CurrencyLayer**: Para conversiones en tiempo real. Obtén tu clave API en [exchangerate.host](https://exchangerate.host/).
- **ExchangeRate-API**: Para datos históricos de tasas de cambio.

## 📖 Uso

1. Ingresa la cantidad a convertir en el campo "Cantidad".
2. Selecciona la moneda de origen en "De".
3. Selecciona la moneda de destino en "A".
4. Haz clic en "Convertir" para obtener el resultado.
5. El gráfico muestra automáticamente el histórico de las tasas seleccionadas.

## 🏗️ Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── CurrencyConverter.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 📜 Scripts Disponibles

- `pnpm dev`: Inicia el servidor de desarrollo.
- `pnpm build`: Construye la aplicación para producción.
- `pnpm preview`: Previsualiza la build localmente.
- `pnpm astro`: Ejecuta comandos de Astro CLI.

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
