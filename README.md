
# 🧪 DevOps Test Project: JUnit & Mockito

Este proyecto es una aplicación de ejemplo desarrollada en Java que implementa pruebas unitarias utilizando **JUnit** y **Mockito**. Es parte de una serie de ejercicios orientados a prácticas de calidad de software y DevOps.

## 📁 Estructura del Proyecto

```
src/
├── main/
│   └── java/
│       └── com/devopsgang/
│           ├── App.java
│           ├── DiscountService.java
│           └── OrderService.java
└── test/
    └── java/
        └── com/devopsgang/
            ├── AppTest.java
            ├── OrderServiceMockTest.java
            └── OrderServiceTest.java
```

## ✅ Tecnologías Utilizadas

- **Java 11+**
- **JUnit 5** - Framework para pruebas unitarias.
- **Mockito** - Biblioteca para pruebas de unidades con mocks.
- **Maven** - Herramienta de construcción y gestión de dependencias.

## 🚀 Cómo ejecutar las pruebas

1. Clona el repositorio:

```bash
git clone https://github.com/hlcxpl/devops-test-mvn.git
cd devops-test-mvn
```

2. Ejecuta las pruebas con Maven:

```bash
mvn test
```

Esto ejecutará todos los test cases definidos en el proyecto.

## 🛠️ Descripción de Clases

- `OrderService`: Clase principal con lógica de negocio para manejo de órdenes.
- `DiscountService`: Servicio auxiliar que aplica descuentos.
- `OrderServiceTest`: Pruebas unitarias básicas para `OrderService`.
- `OrderServiceMockTest`: Pruebas con objetos simulados (mocks) usando Mockito.
- `AppTest`: Prueba de integración básica para la clase principal.

## 📂 Repositorio

Puedes encontrar el código fuente en:  
🔗 [https://github.com/hlcxpl/devops-test-mvn](https://github.com/hlcxpl/devops-test-mvn)

---

📧 Contacto: [hlcxpl@gmail.com](mailto:hlcxpl@gmail.com)
