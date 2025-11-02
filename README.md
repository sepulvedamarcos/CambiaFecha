# 🕒 Cambiar Fecha y Hora del Sistema

Pequeña aplicación escrita en Gambas3 que permite cambiar la fecha y hora del sistema de forma sencilla mediante una interfaz gráfica.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Made with Gambas](https://img.shields.io/badge/Made%20with-Gambas3-green.svg)](http://gambas.sourceforge.net/)
[![Platform](https://img.shields.io/badge/Platform-Linux-orange.svg)](https://www.linux.org/)

🎯 Descripción

Esta aplicación usa un único comando del sistema para actualizar la fecha y hora:

´´´bash
Shell "pkexec date --set '" & fechaHora & "'" Wait
´´´
Gracias a pkexec, la aplicación puede solicitar permisos de administrador cuando sea necesario, garantizando que el cambio de hora se realice correctamente en sistemas Linux.

🚀 Uso

Ejecuta la aplicación desde el IDE de Gambas o como programa compilado.

Ingresa la nueva fecha y hora en el formato correcto (por ejemplo, 2025-11-02 17:30:00).

Presiona el botón Cambiar.

El sistema solicitará tu contraseña de administrador.

¡Listo! La hora del sistema se actualizará.

📦 Instalación

Puedes compilar la aplicación directamente desde Gambas3 o clonar el repositorio:

``bash
git clone https://github.com/sepulvedamarcos/CambiarFechaHora.git
cd CambiarFechaHora
gbr3
```


## 📄 Licencia

GPL v3 - Software libre para siempre.

Eres libre de usar, modificar y distribuir este código. Si creas algo basado en Log4Gambas3, debe ser también GPL v3.

**Marcos Sepúlveda**  
GitHub: [@sepulvedamarcos](https://github.com/sepulvedamarcos)

## 📖 Recursos adicionales

- [Documentación oficial de Gambas3](http://gambaswiki.org/)
- [Foro de Gambas](https://www.gambas-es.org/)
- [Repositorio oficial de Gambas](https://gitlab.com/gambas/gambas)

---

**¿Te resultó útil Log4Gambas3?**  ⭐ Dale una estrella al repositorio

**¿Quieres apoyar el desarrollo?** ☕ [Invítame un café](https://ko-fi.com/sepulvedamarcos)

*Proyecto creado con fines educativos y de aprendizaje*


