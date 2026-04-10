<table>
  <tr>
    <td> <img src="./assets_readme/mono.gif" alt="Canine Care" width="200"> </td>
    <td>

# Canine Care
> Expertos en lo que más quieres ≽(•⩊ •マ≼.
## Descripción
Plataforma de gestion optimizada, nuestra interfaz está construida para transmitir confianza y estetica, somos presentacion y estetica con todas las herramientas para ayudar a tu mascota.
</td> </tr> </table>

## Arquitectura
El proyecto sigue una estructura modular con responsabilidades claramente separadas. La capa visual se compone de componentes reutilizables y la lógica de negocio permanece desacoplada.  
Se adopta un enfoque **static-first** mediante SvelteKit, con generación bajo demanda, lo que permite:
- Tiempos de carga mínimos incluso en conexiones móviles.
- Cero JavaScript innecesario en el cliente.
- Control total del SEO.
- Escalabilidad sin reescrituras costosas.
## Stack Tecnológico
El sistema está construido sobre un stack moderno y bastante comodo me tome el lujo de probar nuevamente varias herramientas y puedo decir q fue grato retomar el rollo de cada herramienta.

| Capa          | Tecnología                  | Justificación                                                                 |
|---------------|-----------------------------|-------------------------------------------------------------------------------|
| **Frontend**  | SvelteKit + TypeScript      | Framework ligero con compilación a JavaScript puro. Sin virtual DOM, lo que se traduce en cargas instantáneas. |
| **Estilos**   | Tailwind CSS + shadcn/ui    | Sistema de utilidades para diseño rápido. Componentes accesibles y personalizables copiados directamente al proyecto. |
| **Backend**   | SvelteKit (endpoints)       | Lógica de servidor integrada en el mismo proyecto. Permite SSR/SSG bajo demanda sin complejidad adicional. |
| **Base de Datos** | PostgreSQL               | Motor relacional robusto, ideal para manejar múltiples conexiones concurrentes y garantizar integridad de datos clínicos. |
| **ORM**       | Prisma                      | Capa de abstracción type‑safe para consultas SQL. Facilita migraciones y modelado de datos. |
## Estado actual
La plataforma está **terminada y en funcionamiento**, cubriendo todas las necesidades operativas actuales de la clínica:
- Sección de contacto con mapa interactivo y horarios actualizados.
- Panel administrativo para la gestión de contenidos, permitiendo actualizaciones sin intervención técnica.
- Presentación clara de servicios
## Proyección
La evolución del sistema está orientada a integrar funcionalidades adicionales bajo demanda del cliente:
- Sistema de pagos integrado para abonar servicios o planes de salud preventiva.
- Notificaciones automáticas vía WhatsApp o correo electrónico.
## Paleta de colores
- `#1E3F20` Verde bosque – Fondos oscuros, encabezados, botones.
- `#5B8C51` Verde hoja – Elementos interactivos, acentos.
- `#F4F1EA` Crema claro – Fondo principal, tarjetas.
- `#D98A44` Terracota – Llamadas a la acción, íconos destacados.
- `#2C2A29` Gris carbón – Textos principales, contraste.
## Fuentes
- **Títulos:** Plus Jakarta Sans 
- **Cuerpo de texto:** Inter 
