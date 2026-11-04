# 🍔 FoodDesk - Aplicación Móvil de Comida a Domicilio

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![XML](https://img.shields.io/badge/XML-005FAD?style=for-the-badge&logo=xml&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

## 📖 Descripción del Proyecto
**FoodDesk** es una aplicación móvil nativa para Android desarrollada en **Kotlin** y **Java** que permite a los usuarios explorar, filtrar y pedir comida a domicilio de manera rápida e intuitiva. Cuenta con una interfaz moderna personalizada mediante **XML Layouts**, barra de búsqueda integrada, filtrado dinámico por categorías, carrito de compras y gestión de platillos favoritos.

---

##  Integrantes del Equipo

**Universidad Politécnica de Tecámac (UPT)**  
*Ingeniería en Tecnologías de la Información e Innovación Digital — Grupo 4426ITII*

| Integrante | Usuario de GitHub |
| :--- | :--- | :--- |
| **Citlali Valentina Tapia González** | [@TapiaCG201](https://github.com/TapiaCG201) |
| **Irving Uriel Ramirez Gomez** | `@irvingrami169-dot` |
| **Jessica Alejandra Perez Palomo** |  `@jess9826091-ctrl` |

---

##  Funciones Principales

-  **Pantalla de Inicio (Home):** Interfaz con encabezado personalizado, destacadas y acceso rápido al catálogo de alimentos.
-  **Búsqueda Integrada:** Barra de búsqueda en tiempo real para localizar platillos o restaurantes por nombre.
-  **Filtrado por Categorías:** Navegación organizada por tipos de comida (hamburguesas, pizzas, bebidas, postres, etc.).
-  **Gestión de Favoritos:** Opción para marcar y guardar los platillos preferidos del usuario para pedidos futuros.
-  **Carrito de Compras:** Selección de productos, ajuste de cantidades y cálculo automático del total del pedido.
-  **Diseño Adaptable:** Interfaces construidas con XML Layouts personalizados para una experiencia fluida e intuitiva.

---

## 🛠️ Tecnologías y Herramientas

- **Lenguajes de programación:** Kotlin y Java
- **Diseño de Interfaces:** XML (ConstraintLayout, RecyclerView, CardView, Material Design)
- **Entorno de Desarrollo (IDE):** Android Studio
- **Sistema de Construcción:** Gradle
- **Control de Versiones:** Git y GitHub

---

## 📂 Estructura del Proyecto

```text
FoodDesk/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/fooddesk/
│   │   │   │   ├── activities/       # Actividades y pantallas principales (Main, Carrito, Detalle)
│   │   │   │   ├── adapters/         # Adaptadores para RecyclerViews (Categorías, Platillos)
│   │   │   │   ├── models/           # Modelos de datos (Producto, Categoría, Pedido)
│   │   │   │   └── utils/            # Clases auxiliares y validaciones
│   │   │   ├── res/
│   │   │   │   ├── drawable/         # Íconos, banners, fondos y recursos gráficos
│   │   │   │   ├── layout/           # Diseños XML de las pantallas e ítems de lista
│   │   │   │   ├── values/           # Colores (paleta roja/blanca), strings y temas
│   │   │   └── AndroidManifest.xml   # Configuración general de la app y permisos
│   └── build.gradle.kts              # Configuración de dependencias del módulo
├── gradle/                           # Wrapper de Gradle
├── .gitignore                        # Archivos excluidos del control de versiones
├── build.gradle.kts                  # Configuración global del proyecto
└── README.md                         # Documentación del repositorio
