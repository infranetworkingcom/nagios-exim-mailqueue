![enter image description here](https://www.infranetworking.com/images/infranetworking-logo-2015.png)

nagios-exim-mailqueue
---------------------
Plugin de nagios para alertar sobre las colas de salidas de exim y nos informa cuando supera el limite configurado de cantidad de correos. Así podemos identificar cualquier envió no regular de correo **SPAM** en el servidor.

**Requerimientos de configuración en archivo /etc/sudoers**

**Debe contener la siguiente linea para darle acceso libre al usuario *nagios***

    nagios ALL=(ALL) NOPASSWD:ALL

**Y debe estar comentada la siguiente linea**

    #Defaults    requiretty

Desarrollado por [Infranetworking.com](https://www.infranetworking.com/)
