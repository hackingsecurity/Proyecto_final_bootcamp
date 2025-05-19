
# Planificación


Planificación de fases futuras en proyecto final del bootcamp


## Spring 1:

  

Configuración inicial de Pfsense con las distintas interfaces de red:

  

Interfaz 1:  Conectividad con internet

interfaz 2: Conectividad interna.

  
  

Asignación de IPs, así como de servicios esenciales para el correcto funcionamiento del firewall en su etapa inicial de configuración.

  
  

## Spring 2:

  

Configuración de OpenWRT (u otro) con las distintas interfaces de red:

  

interfaz 1: Conectividad con Pfsense

Interfaz 2: Conectividad con un segmento de red LAN

interfaz 3: Conectividad con un segmento de red IoT o de elementos de red sin conectividad desde fuera hacia dentro (inbound) con los dispositivos. Esta red es mucho más restrictiva que las demás.

  
  

Además debemos valorar la asignación de IPs dinámicamente o de forma estática.

  
  

## Spring 3:

  

Configuración de máquinas virtuales con diferentes sistemas operativos (Ubuntu, Linux, windows). Instalación de agentes para la monitorización de eventos, que irán al SIEM.

  

## Spring 4:

  

Configuración de un SIEM que actuará de recolector de logs de los diferentes endpoints (valorable ver splunk y wazuh).

  

En clase -> veremos lo que es un SIEM -> Instalación y uso de la herramienta.

  
  

## Spring 5:

  

Configuración de bot con telegram con capacidad de llamadas a la API y poder interactuar con él SIEM.

  

(preguntar sobre cómo afectará si directamente el SIEM dispara alertar y ataca la API de Telegram en cuanto a compliance).

  
  

—