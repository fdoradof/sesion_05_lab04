# sesion_05_lab04
Laboratorio de Condicionales

# Enunciado del Ejercicio

- Crearemos u repositorio en GitHub con el nombre sesion_05_lab04
- Lo clonaremos en nuestor equipos
- Insertaremos el inventario y el ansible.cfg necesario para conectarnos a los nodos
- Copiaremos el playbook del laboratorio sesion_05_lab01 y realizaremos los siguientes cambios:
	- Si se ejecutamos el playbook los lunes, miercoles, viernes o domingos y la hora es mayor o igual a las 12 a.m se cambiara la zona horaria a moscow
	- Para los demas dias de la semana la zona horaria sera tokio y la hora es mayor o igual a las 10 a.m
	- Crearemos un fichero en la ruta /tmp con el nombre datos_horarios_HOSTNAME.txt
	- Miraremos la HORA (hora, minuto y segundo) actual y la guardaremos en un registro
	- Dentro del fichero anterior deberemos de imprimir los siguientes frases:
		- La zona horaria antes del cambio es ZONA_HORARIA Y la hora era HORA
		- La zona horaria despues del cambio es ZONA_HORARIA Y la hora era HORA
	- Volveremos a dejar la zona horaria como estaba antes de cambiarla (usar el registro anterior)

* Advertencia: Mucho cuidado con las demas tareas tras el cambio a una de las dos zonas horarias.