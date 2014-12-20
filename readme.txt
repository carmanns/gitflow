Prácticas de Git±Flow flexible.

Laboratorio de Git±Flow para prácticas con el flujo de trabajo gitflow flexible

El objetivo de este laboratorio de prácticas de gitflow es el de establecer una serie de bases y procedimientos flexibles partiendo de gitflow.

Espacio de trabajo:
	- Se configura gitflow con git flow init como es habitual.
	- Se configuran con user.name, user.email, flow init
	- Se configura un $ORIGIN con "gitflow.origin origin" para agregar a gitflow tareas de remotos (fetch, push, etc): git config gitflow.origin origin
	- Se clonan dos repositorios (gitflow y gitflow2) para poder comprobar las tareas remotas. Se configuran igual ambos.
	- Se modifica un único fichero (readme.txt) con el fin de simplificar el ejemplo.

PRUEBAS REALIZADAS
	
	PRUEBA1: VARIAS FEATURES EN ORDEN
	- Se inician y finalizan varias features, una detrás de otra. Cuando las features llevan varios commits se realiza siempre un --no-ff.
	Si la feature lleva sólo un commit, no se realiza --no-ff, y da la impresión de que se ha realizado directamente en develop.
	Las ramas de las features se eliminan una vez que se finaliza la feature, y si fueron publicadas previamente, al finalizarlas también se eliminan del remoto.
	Una vez finalizada la feature se mergea en develop. Los cambios en develop hay que subirlos con git push, no se suben solos.



CONCLUSIONES

PRINCIPIOS

PROCEDIMIENTOS
