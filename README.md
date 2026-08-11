# Team-Origen

Bienvenido a la organización **Team-Origen**. Este espacio centraliza el desarrollo del Sistema de Gestión de Turnos "Origen" para centro de salud.

## 🎯 Sobre el Proyecto
Origen es una plataforma web diseñada para la gestión integral de turnos médicos, la comunicación con los pacientes a través de WhatsApp. 

El sistema tiene como funciones principales:
* Permitir la reserva de turnos interactiva y la gestión de la lista de espera.
* Administrar las agendas profesionales, incluyendo horarios, ausencias y tipos de consulta.
* Enviar notificaciones y recordatorios automáticos de manera integrada.
* Registrar operaciones en una tabla de auditoría inmutable.

Cabe destacar que el sistema se enfoca puramente en la gestión administrativa y operativa; no realizará diagnósticos médicos.

## 👥 Roles del Sistema
La plataforma segmenta los accesos y funcionalidades en cuatro niveles jerárquicos principales:
* **Administrador:** Gestión de cuentas, recuperación de accesos y configuración global.
* **Profesional:** Control de su disponibilidad, seguimiento de turnos asignados y atención administrativa.
* **Secretaría:** Asistencia operativa general, incluyendo la gestión de sobreturnos y validación de comprobantes de pago.
* **Paciente:** Autogestión de turnos y visualización de historial mediante un inicio de sesión "passwordless" (sin contraseñas tradicionales).

## 🏗️ Repositorios Principales
El desarrollo técnico del sistema se encuentra estructurado en los siguientes proyectos:
* **`origen-api`**: Contiene la lógica central del backend, el sistema de Logs de Auditoría y las interfaces con servicios externos (API de WhatsApp Business y Google Auth).
* **`origen-web`**: Contiene la interfaz de usuario, garantizando un diseño adaptativo (Responsive Design) para monitores, tabletas y móviles.

## ⚙️ Flujo de Trabajo y Desarrollo
La gestión de tareas del equipo se administra en el tablero Kanban **Origen Development**, siguiendo el flujo de estados: `New` → `In Progress` → `On Review` → `Done`.

**Políticas de Integración:**
* La arquitectura de ramas mantiene el flujo `feature/*` → `develop` → `main`.
* Las ramas principales (`main` y `develop`) se encuentran protegidas y no pueden ser eliminadas.
* El ingreso de nuevo código a `develop` está restringido exclusivamente a través de Pull Requests provenientes de otras ramas de trabajo.
* Es obligatorio que cada Pull Request sea revisado y aprobado por otro miembro del grupo; un desarrollador no tiene permitido mover su propia tarea de revisión a finalizada.

## 👨‍💻 Equipo de Desarrollo
El diseño y desarrollo de la plataforma es llevado a cabo por:
* Samuel Olmos
* Said Quioto  
* Santiago Casali
* Lucca Giordana
