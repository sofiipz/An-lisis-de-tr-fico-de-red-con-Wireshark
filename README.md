# Análisis de Tráfico de Red con Wireshark

## Descripción

Este repositorio contiene los resultados de la práctica realizada en la asignatura **Sistemas Informáticos** del **1º de DAM** en **abril de 2025**. En esta práctica se utilizó **Wireshark**, un analizador de protocolos de red, para capturar y analizar el tráfico ICMP tanto en una red local (LAN) como en conexiones remotas.

### **Objetivos de la práctica:**
- Capturar y analizar los paquetes ICMP generados por solicitudes de **ping**.
- Obtener direcciones IP y MAC de los dispositivos locales y remotos.
- Comparar los datos obtenidos en la red local con los datos de tráfico de sitios web externos.

### **Pasos realizados en la práctica:**

1. **Captura y análisis de tráfico ICMP local:**
   - Se realizó un ping a otro dispositivo en la misma red local.
   - Se capturaron los paquetes de red usando Wireshark y se examinaron los encabezados de Ethernet y los protocolos ICMP.
   
2. **Captura y análisis de tráfico ICMP remoto:**
   - Se realizó un ping a sitios web remotos como **www.cisco.com**, **www.wikipedia.org** y **www.educa2.madrid.org**.
   - Se compararon las diferencias entre los paquetes ICMP locales y los de sitios externos.

### **Tecnologías utilizadas:**
- **Wireshark**: Analizador de tráfico de red.
- **Red Local (LAN)**: Para la captura de tráfico local.
- **Símbolo de sistema de Windows (cmd)**: Para realizar los pings a las IPs de los dispositivos.

**Fecha de realización: abril de 2025**
