# Proyecto de Título: Arquitectura WAN Segura Dual-Hub Dual-Cloud con DMVPN Fase 3

**Autor:** Thomas Enrique Villanueva Espinoza  
**Carrera:** Ingeniería en Conectividad y Redes  
**Institución:** Duoc UC  
**Caso de Estudio:** Ferretería Hermanos Vera  

---

## 📋 Descripción del Proyecto

Diseño, implementación y validación de una infraestructura de red WAN empresarial altamente disponible y segura bajo topología **Dual-Hub Dual-Cloud con DMVPN Fase 3**. La solución integra enrutamiento dinámico **EIGRP**, protección criptográfica mediante **IPsec (ISAKMP/ESP)**, resolución dinámica de saltos con **NHRP** (habilitando túneles directos *Spoke-to-Spoke* bajo demanda) y políticas de **Calidad de Servicio (QoS)** para garantizar la continuidad operativa y la eficiencia del tráfico entre sucursales.

---

## 📁 Contenido del Repositorio

* **`Informe_Final_Fase2_APT_Ferreteria_Hermanos_Vera FINAL.pdf`**: Documentación técnica completa del proyecto, memoria de cálculo, direccionamiento IP, topología, configuraciones y análisis de pruebas.
* **`Presentacion_Capstone_DMVPN fase 2 thomas.pptx`**: Presentación ejecutiva y técnica utilizada para la defensa ante la comisión evaluadora.

---

## 🛠️ Tecnologías y Protocolos Implementados

* **Topología Overlay:** DMVPN Fase 3 (Dual-Hub / Dual-Cloud)
* **Resolución de Siguiente Salto:** NHRP (*Shortcut Switching* / *Redirect*)
* **Enrutamiento Dinámico:** EIGRP
* **Seguridad y Cifrado:** IPsec sobre mGRE (IKEv1 / ISAKMP, ESP)
* **Gestión de Tráfico:** Calidad de Servicio (QoS)
* **Entorno de Simulación:** GNS3
