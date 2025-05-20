

# Implementación de Pfsense


* https://www.pfsense.org/download/

Guia para la virtualización de PFsense

* https://simplificandoredes.com/en/install-pfsense-on-virtualbox/


Para la instalación de Pfsense, usamos correo temporal y teléfono temporal

* https://temp-mail.org
* https://temp-number.com/temporary-numbers/Spain

Una vez descargada la imagen ISO la descomprimimos.


```shell

gunzip netgate-installer-amd64.iso.gz


```


Ahora creamos un máquina virtual BSD y cogemos el .iso para carga la máquina.


![](adjuntos/Pasted%20image%2020250519211345.png)



Creación de las interfacez de red en virtualbox

* https://aprendaredes.com/cgi-bin/ipcalc/ipcalc_cgi1?host=10.0.100.0&mask1=24&mask2=
* https://aprendaredes.com/cgi-bin/ipcalc/ipcalc_cgi1?host=10.0.200.0&mask1=24&mask2=


Previamente abría que crear la interfaces de red y poner para la VLAN100 el dhcp activado.

![](adjuntos/Pasted%20image%2020250520194136.png)


Posteriormente las configuramos en la máquina virtual PFsense

![](adjuntos/Pasted%20image%2020250520194011.png)

![](adjuntos/Pasted%20image%2020250520194044.png)



## Configuración de Pfsense


![](adjuntos/Pasted%20image%2020250520201938.png)



![](adjuntos/Pasted%20image%2020250520194256.png)



![](adjuntos/Pasted%20image%2020250520194319.png)



Importante elegir bien las interfaces para configurar la WAN y la LAN, en nuestro caso vamos a usar em0 acabada en 34 para la WAN (100).

![](adjuntos/Pasted%20image%2020250520201952.png)

![](adjuntos/Pasted%20image%2020250520202145.png)


Tarda un rato en proceder con la instalación.


Configuramos la LAN  a 10.0.200.1/24 y desactivamos DHCP y procedemos a instalar.


![](adjuntos/Pasted%20image%2020250520205146.png)





