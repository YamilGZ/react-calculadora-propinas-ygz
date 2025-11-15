# Calculadora de Propinas con React + TypeScript

Aplicación web que permite armar una orden de consumo, calcular el costo total y aplicar distintos porcentajes de propina. Todo el flujo de estado (orden, cantidades y porcentaje) se administra con `useReducer`, lo que facilita mantener la lógica de negocio desacoplada de los componentes de UI.

## Características principales

- Gestión de la orden a partir de un menú definido en `src/data/db.ts`.
- Incremento/decremento y eliminación de productos desde `OrderContents`.
- Selección rápida del porcentaje de propina mediante `TipPercentageForm`.
- Totales actualizados en tiempo real mostrando subtotal, propina y total a pagar.

## Tecnologías utilizadas

- React 19 con TypeScript para la interfaz y tipado estático.
- Vite 7 como bundler y entorno de desarrollo.
- Tailwind CSS 4 para los estilos utilitarios.
- ESLint + TypeScript ESLint para mantener un estilo de código consistente.

## Requisitos previos

- Node.js 20+ y npm.
- Git para clonar el repositorio.

## Cómo clonar y ejecutar el proyecto

```bash
# 1. Clonar el repositorio
git clone https://github.com/YamilGZ/react-calculadora-propinas-ygz.git
cd react-calculadora-propinas-ygz

# 2. Instalar dependencias
npm install

# 3. Correr el entorno de desarrollo
npm run dev

# 4. (Opcional) Crear build de producción
npm run build
```

El comando `npm run dev` levantará Vite en `http://localhost:5173` por defecto; abre la URL en tu navegador para ver la calculadora funcionando. Para previsualizar la build estática, ejecuta `npm run preview` después del build.
