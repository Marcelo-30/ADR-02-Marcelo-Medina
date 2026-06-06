# ADR-02: Vistas arquitectónicas iniciales de CatalogoAPP

| Campo  | Valor |
|--------|-------|
| Autor  | Marcelo Medina |
| Fecha  | 05/06/2026 |
| Estado | Aceptado |

---

## Contexto

CatalogoAPP es una aplicación web para pequeños vendedores y revendedores de ropa. El sistema busca permitir la administración y visualización de productos como prendas, categorías, tallas, colores, precios e imágenes, evitando que el vendedor dependa únicamente de redes sociales, notas o archivos separados para mostrar su catálogo.

En el ADR-01 se aceptó utilizar C#, ASP.NET Core MVC, Entity Framework Core, SQL Server, arquitectura MVC y GitHub como base tecnológica del proyecto. A partir de esa decisión, este ADR documenta las vistas arquitectónicas iniciales que se usarán para explicar la estructura del sistema desde diferentes perspectivas.

La necesidad principal de esta decisión es poder defender la arquitectura en clase y tener una guía clara para continuar el desarrollo del proyecto durante el cuatrimestre.

---

## Decisión

Se decidió documentar la arquitectura inicial de CatalogoAPP mediante cuatro vistas arquitectónicas:

- **Vista lógica:** muestra la organización del sistema en capas y responsabilidades.
- **Vista física:** muestra cómo se organiza el código en carpetas, archivos y componentes del proyecto.
- **Vista de despliegue:** muestra dónde se ejecuta cada parte del sistema y cómo se comunican.
- **Vista de procesos:** muestra el flujo de operación principal cuando un vendedor administra productos y un cliente consulta el catálogo.

### ¿Por qué?

Se eligieron estas vistas porque permiten explicar el sistema desde diferentes niveles de detalle. La vista lógica ayuda a entender la separación de responsabilidades de MVC; la vista física permite ubicar el código dentro del proyecto; la vista de despliegue muestra la relación entre navegador, aplicación web y base de datos; y la vista de procesos permite explicar cómo fluye una acción real dentro del sistema.

Estas vistas ayudan a justificar que CatalogoAPP no solo es código funcional, sino un sistema diseñado con una estructura clara, mantenible y entendible.
