<p align="center">

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Security](https://img.shields.io/badge/Focus-Security-blue)
![DevOps](https://img.shields.io/badge/DevOps-Automation-green)
![Governance](https://img.shields.io/badge/AWS-Governance-232F3E)
![FinOps](https://img.shields.io/badge/FinOps-Cost%20Optimization-5B2C6F)
![Serverless](https://img.shields.io/badge/Architecture-Serverless-FF9900)
![Networking](https://img.shields.io/badge/AWS-Networking-1E90FF)
![IAM](https://img.shields.io/badge/Security-IAM%20Least%20Privilege-8B0000)
![Containers](https://img.shields.io/badge/Containers-Docker-2496ED?logo=docker\&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-Automated-blue)
![Jenkins](https://img.shields.io/badge/CI%2FCD-Jenkins-D24939?logo=jenkins\&logoColor=white)
![Virtualization](https://img.shields.io/badge/Virtualization-Proxmox-E57000)
![Automation](https://img.shields.io/badge/Automation-Ansible-EE0000?logo=ansible\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?logo=ubuntu\&logoColor=white)
![Profile Views](https://komarev.com/ghpvc/?username=JonasCC8\&color=blue)

</p>

# ☁ Jonas Carrillo Carballo

## Cloud Infrastructure & SRE Engineer | AWS | DevOps | Observability | Security | FinOps | Virtualization

Ingeniero especializado en diseño, implementación y automatización de infraestructuras en la nube, enfocadas en alta disponibilidad, seguridad y escalabilidad.

Enfocado en confiabilidad, observabilidad y respuesta a incidentes en entornos cloud e híbridos.

---

# 🚀 Sobre Mí

Experiencia práctica en:

🔐 Arquitecturas AWS multi-cuenta con Organizations
☁ Diseño de arquitecturas altamente disponibles (HA) en AWS
📈 Implementación de Auto Scaling basado en métricas
📡 Monitoreo y alertamiento con CloudWatch y SNS  
📊 Observabilidad y alertamiento proactivo con Zabbix + Telegram 
🧯 Troubleshooting e identificación de incidentes en infraestructura  
⚖️ Balanceo de carga con Application Load Balancer (ALB)
🏢 Gobernanza mediante Service Control Policies (SCPs)
🌐 Networking cross-account con VPC Peering
🛡 Seguridad con WAF y controles IAM
🔁 Automatización con Lambda y eventos
🐳 Despliegue de contenedores con ECR + ECS (Fargate)
⚙️ CI/CD automatizado con Jenkins y GitHub
📦 Acceso y sincronización S3 cross-account
⏰ Optimización de costos con automatización
🖥 Virtualización y automatización en Proxmox
🛡 Implementación de SIEM con Wazuh
🚀 Deploy automatizado de aplicaciones con Docker

---

# 🏗 Proyectos Destacados

## 🔐 AWS IAM Security Lab

Endurecimiento de configuraciones IAM aplicando principio de mínimo privilegio y control granular de accesos.

Incluye:

* Creación de usuarios y roles
* Políticas IAM personalizadas
* Restricciones por servicio
* Aplicación del principio de mínimo privilegio

---

## 🏢 AWS Organizations – Multi-Account Governance

Diseño de arquitectura multi-cuenta utilizando AWS Organizations.

Incluye:

* Creación de Organizational Units (OUs)
* Aplicación de Service Control Policies
* Centralización de logs
* Separación de entornos (Dev / Prod)

---
## 🚀 Arquitectura de Alta Disponibilidad en AWS (ECS + ALB + Auto Scaling + SNS)

Diseño e implementación de una arquitectura altamente disponible en AWS utilizando contenedores y escalamiento automático.

Incluye:

* ECS Fargate distribuido en múltiples Availability Zones
* Application Load Balancer (ALB) para balanceo de tráfico
* Auto Scaling basado en métricas de CPU
* Arquitectura tolerante a fallos (self-healing)
* Monitoreo con CloudWatch
* Notificaciones por email con SNS
   
## 🌐 VPC Peering Cross-Account

Implementación de conectividad privada entre cuentas AWS.

Incluye:

* Diseño de CIDR
* Configuración de VPC Peering
* Gestión de Route Tables
* Comunicación privada entre cuentas

---

## 🔁 AWS S3 Cross-Account Access & Sync

Configuración de acceso entre cuentas para buckets S3.

Incluye:

* Bucket Policies
* IAM Roles
* Acceso seguro cross-account
* Sincronización con AWS CLI

---

## 🐳 CI/CD Pipeline for Containerized Applications (AWS)

GitHub → CodeBuild → ECR → ECS Fargate

Pipeline automatizado para despliegue de contenedores.

Incluye:

* Build automático
* Push a ECR
* Deploy en ECS Fargate
* Automatización CI/CD

---

## 🛡 AWS WAF – Geo Blocking

Implementación de reglas de seguridad para bloquear tráfico por ubicación geográfica.

Incluye:

* Creación de Web ACL
* Geo Match Rules
* Protección de aplicaciones web

---

## ⏰ RDS Auto Start/Stop Automation

Optimización de costos mediante automatización de bases de datos.

Incluye:

* AWS Lambda
* Amazon EventBridge
* Programación automática de apagado y encendido

---

## 💰 Cloud Cost Analysis & Remediation (FinOps)

Análisis de consumo de recursos en AWS.

Incluye:

* AWS Cost Explorer
* Identificación de recursos costosos
* Aplicación de optimizaciones
* Automatización de ahorro de costos

---

# 🖥 Proyectos de Infraestructura & Automatización

## 🛡 Implementación de SIEM con Wazuh en Proxmox

Despliegue de plataforma SIEM para monitoreo de seguridad.

Incluye:

* Wazuh Manager
* Wazuh Indexer (OpenSearch)
* Wazuh Dashboard
* Agente Windows
* Monitoreo de eventos de seguridad
* Alertas por intentos fallidos de login

---
## 📊 Zabbix 7.4 Monitoring & Alerting Platform (AWS EC2)

Despliegue de plataforma de monitoreo empresarial utilizando Zabbix 7.4 sobre AWS EC2 con agentes en Linux y Windows.

Incluye:

* Implementación de Zabbix Server en EC2 (Ubuntu Server)
* Configuración de base de datos MySQL
* Apertura y gestión de puertos (10050 / 10051)
* Instalación de agentes en Linux y Windows
* Monitoreo de infraestructura en tiempo real
* Configuración de hosts y templates
* Notificaciones en tiempo real vía Telegram
* Detección proactiva de incidentes (CPU, memoria, disponibilidad de servicios)
* Reducción del MTTR mediante alertamiento automatizado
* Mejora en la visibilidad del estado y rendimiento de la infraestructura
* Arquitectura escalable para entornos productivos
* Monitoreo de disponibilidad de servicios y health checks

---
## 🐳 Docker Swarm en Proxmox VE

Cluster de contenedores desplegado sobre máquinas virtuales en Proxmox.

Incluye:

* Manager Node
* Worker Nodes
* Escalamiento horizontal
* Rolling updates
* Alta disponibilidad

---

## ⚙️ Automatización con Ansible en Proxmox VE

Provisionamiento automatizado de infraestructura.

Incluye:

* Creación automática de VMs
* Conexión SSH remota
* API Tokens
* Playbooks idempotentes
* Gestión de roles

---

## 🚀 CI/CD Pipeline Jenkins + Proxmox + Docker

Pipeline CI/CD implementado sobre una VM en Proxmox.

Arquitectura del proyecto:

Developer → GitHub → Jenkins → Docker Build → Deploy API

Incluye:

* Instalación de Jenkins en VM Ubuntu
* Integración con repositorio GitHub
* Pipeline automatizado
* Construcción de contenedor Docker
* Deploy de API
* Pruebas de endpoint

---

# 🛠 Skills Técnicos

## ☁ Cloud Platforms

* AWS (VPC, EC2, ECS Fargate, ECR, S3, IAM, WAF, Lambda, RDS, EventBridge, Organizations, ALB, Auto Scaling, CloudWatch, SNS)
* Google Cloud Platform (Intermedio)
* Microsoft Azure (Básico)
* Oracle Cloud Infrastructure (Básico)

---

## 🔐 Seguridad en la Nube

* IAM Policies & Roles
* Service Control Policies
* Security Groups
* WAF Geo-Blocking
* MFA
* Principio de Mínimo Privilegio
* SIEM con Wazuh
* Monitoreo de logs
* Monitoreo y alertamiento (CloudWatch + SNS)
* Observabilidad básica en arquitecturas distribuidas
---

## 🔁 DevOps & Automatización

* Jenkins
* AWS CodePipeline
* AWS CodeBuild
* CI/CD con GitHub
* Docker
* Ansible
* AWS CLI
* Automatización con Lambda
---

## 📊 Observabilidad & Monitoreo

* Zabbix (monitoreo de infraestructura, triggers, alertas, auto-descubrimiento, agentes Linux/Windows)
* AWS CloudWatch (métricas, alarmas y dashboards)
* AWS EventBridge (alertamiento basado en eventos e integraciones)
* Monitoreo de logs y SIEM (Wazuh)
* New Relic (APM, dashboards y alertamiento - certificación Foundation)
* Datadog (métricas, dashboards y alertamiento - nivel Foundation)
* Detección proactiva de incidentes y alertamiento en tiempo real (integración con Telegram)
* Monitoreo de disponibilidad de servicios y health checks
---

## 🌐 Networking

* VPC Peering
* Diseño de CIDR
* Route Tables
* Arquitecturas multi-account
* Networking en AWS

---

# 🎯 Enfoque Profesional

✔ Seguridad primero
✔ Automatización como estándar
✔ Gobernanza multi-cuenta
✔ Optimización continua de costos
✔ Arquitecturas escalables
✔ Infraestructura híbrida Cloud + On-Premise

---
# 📈 Impacto

* Implementación de monitoreo proactivo reduciendo tiempos de detección de incidentes  
* Automatización de alertamiento mejorando la respuesta operativa  
* Mejora de la confiabilidad y visibilidad de la infraestructura
  
# 📫 Contacto

GitHub
https://github.com/JonasCC8

LinkedIn
https://www.linkedin.com/in/jonas-carrillo-33389025/

---

> Construyendo entornos en la nube y on-premise seguros, escalables y automatizados.


