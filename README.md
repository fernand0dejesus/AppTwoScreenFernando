// README.md
# Aplicación de Navegación React Native

## Descripción
Esta aplicación React Native cumple con los requisitos del módulo 3.5 "Desarrollo de componentes para dispositivos móviles" del grupo 2A, bajo la supervisión del docente Wilfredo Granados.

## Características Implementadas

### 1. Pantalla Principal (HomeScreen)
- Muestra información básica del módulo
- Nombre del módulo: "Navegación en React Native"
- Descripción del módulo y detalles académicos
- Botón para navegar a la segunda pantalla
- Diseño atractivo con gradientes y iconos

### 2. Segunda Pantalla (StudentScreen)
- Contiene una card personalizada con información del estudiante
- Botón para regresar a la pantalla principal
- Información del estudiante: Fernando de Jesus Hernandez Morales

### 3. Componente StudentCard Reutilizable
- Componente que recibe información como props
- Muestra:
  - Nombre completo: Fernando de Jesus Hernandez Morales
  - Edad: 18 años
  - ID de estudiante: 20200335
  - Imagen del estudiante
  - Información adicional (email, curso, grupo)

### 4. Navegación
- Implementada con React Navigation
- Stack Navigator para navegar entre pantallas
- Botones funcionales de navegación

## Tecnologías Utilizadas
- React Native
- React Navigation
- Expo Linear Gradient
- React Native Vector Icons
- Expo

## Instalación y Ejecución

1. Instalar dependencias:
```bash
npm install
```

2. Ejecutar la aplicación:
```bash
npm start
```

3. Escanear el código QR con Expo Go o ejecutar en simulador

## Estructura del Proyecto
```
├── App.js                 # Componente principal y configuración de navegación
├── screens/
│   ├── HomeScreen.js      # Pantalla principal
│   └── StudentScreen.js   # Segunda pantalla
├── components/
│   └── StudentCard.js     # Componente reutilizable de tarjeta
├── package.json
└── README.md
```

## Estudiante
**Fernando de Jesus Hernandez Morales**
- ID: 20200335
- Edad: 18 años
- Grupo: 2A
- Módulo: 3.5 - Desarrollo de componentes para dispositivos móviles
- Docente: Wilfredo Granados

## Funcionalidades Adicionales
- Diseño responsive y atractivo
- Uso de gradientes y iconos
- Información detallada del estudiante
- Componente completamente reutilizable
- Navegación fluida entre pantallas
