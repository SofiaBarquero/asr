# PRÁCTICA 2: VIRTUAL MACHINES
## Arquitectura de Servicios de Red
### Sofía Barquero Jiménez- 1ºA MIT, 201805688
En esta práctica, se crearán máquinas virtuales con las siguientes reglas de seguridad: 
  *	Regla del mínimo privilegio.
  *	Exponer únicamente lo mínimo imprescindible a internet.
  *	Usar siempre tráfico cifrado (siempre en internet)
  *	Usar siempre un doble salto para un acceso a un servidor si este está expuesto a internet

#### 1ª Solución: creación de máquina de salto
*	Exponer únicamente en el servidor web lo mínimo indispensable
*	Montar una máquina de salto para poder acceder a nuestra máquina. Esta máquina se debería encender y apagar cada vez que se quiera modificar algo del servidor web.

