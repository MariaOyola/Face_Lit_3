# 🎓 Sistema de Control de Asistencia por Reconocimiento Facial — SENA

---

## 📌 Problema

Actualmente, el registro de asistencia en el SENA se hace **de forma manual**: los instructores llaman lista y anotan en hojas de cálculo (Excel). Este método tiene varios problemas graves:

- **Errores humanos** — se omiten aprendices o se registran datos incorrectos.
- **Suplantación de identidad** — cualquier persona puede responder por otra.
- **Pérdida de tiempo** — el proceso tarda entre 5 y 10 minutos por sesión, restando tiempo valioso a la formación.
- **Falta de trazabilidad** — no hay un historial confiable y automatizado del comportamiento de asistencia.
- **Dificultad para generar reportes** — el seguimiento académico depende de que el instructor actualice manualmente las planillas.

> Según el Observatorio de la Universidad Colombiana (2022), cerca del **35% de las instituciones educativas** en Colombia reportan dificultades en el control de asistencia, siendo la suplantación y los errores humanos los principales inconvenientes.

---

## 🎯 ¿Qué se quiere lograr?

Desarrollar un **sistema automatizado de registro de asistencia** que use **reconocimiento facial** para identificar a los aprendices al ingresar al ambiente de formación, sin ninguna intervención manual del instructor.

---

## ✅ Lo que el sistema debe hacer

### 👤 Registro e identificación de usuarios
- Registrar aprendices con sus datos básicos (nombre, ficha, programa).
- Capturar y almacenar su información biométrica facial.
- Identificar automáticamente al aprendiz mediante la cámara al ingresar al aula.

### 🕐 Control de asistencia automático
- Registrar la hora exacta de ingreso.
- Clasificar el estado del aprendiz como:
  - ✅ **Puntual**
  - ⚠️ **Tardío**
  - ❌ **Ausente**
- Validar que el aprendiz esté en el ambiente correcto según su horario.

### 📊 Reportes y seguimiento
- Generar reportes individuales y grupales de asistencia.
- Visualizar historial por calendario.
- Mostrar estadísticas de puntualidad e inasistencias.
- Exportar reportes en **Excel o PDF**.

### 🔔 Notificaciones
- Alertas automáticas sobre ausencias o retrasos.
- Envío de notificaciones por correo electrónico.

### 🔐 Gestión de accesos y roles
- Inicio de sesión con roles diferenciados: **Administrador**, **Instructor**, **Aprendiz**.
- Auditoría de acciones del sistema (bitácoras).

---

## 🛠️ Tecnología clave

| Componente | Descripción |
|---|---|
| **Reconocimiento facial** | Captura y comparación de rostros en tiempo real |
| **Raspberry Pi** | Dispositivo físico que ejecuta el reconocimiento en el aula |
| **Base de datos** | Almacena usuarios, registros de asistencia y horarios |
| **Aplicación web/móvil** | Interfaz para instructores y administradores |
| **Generador de reportes** | Exportación automática en Excel/PDF |

---

## 👥 Equipo del proyecto

| Nombre | Rol |
|---|---|
| Valery Sinaí Trujillo Quintero | Diseñadora |
| María José Rodríguez Oyola | Codificación |
| Mariana Valenzuela Penagos | Base de datos |

---

## 🏁 Resultado esperado

Un sistema funcional, desplegado en el SENA, que permita al instructor **olvidarse de llamar lista** y enfocarse completamente en la formación, mientras el sistema registra, valida y reporta la asistencia de manera automática, precisa y confiable.
