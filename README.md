
# ☁️ Azure Cloud Portfolio – Antonio Zapata

Este repositorio centraliza mi portfolio técnico como **Azure Cloud & Identity Administrator**.  
Incluye laboratorios prácticos que simulan entornos reales de empresa siguiendo buenas prácticas de Microsoft.

El entorno está desplegado en una suscripción real llamada **Zapata-Cloud**, con foco en:
- Seguridad (SC-300)
- Infraestructura (AZ-104)
- Gobernanza y operaciones
- Automatización de infraestructura con Terraform

---

## 🧱 Arquitectura del entorno

El laboratorio simula una empresa llamada **Zapata-Cloud** con:

- Microsoft Entra ID (Identidades, MFA, PIM, B2B)
- Redes Azure (VNets, Subnets, NSG, Bastion)
- Máquinas Virtuales y servicios PaaS
- Backup, Monitorización y Cost Management

Todo se construye progresivamente desde cero.

---

## 🧪 Laboratorios

Cada laboratorio está documentado con:
- Objetivo
- Pasos realizados
- Evidencias (capturas)
- Aprendizaje para entrevista


| Fase | Laboratorio | Descripción |
|------|------------|-------------|
| Identidad | [Lab 01 – Break Glass](https://github.com/zapata-antonio/Azure-Lab-01-BreakGlass) | Cuenta de emergencia |
| Identidad | [Lab 02 – SSPR](https://github.com/zapata-antonio/Azure-Lab-02-SSPR) | Autoservicio de contraseñas |
| Identidad | [Lab 03 – App Registration Hardening](https://github.com/zapata-antonio/Azure-Lab-03-AppRegistrations-Hardening) | Bloqueo de Shadow IT |
| Identidad | [Lab 04 – B2B](https://github.com/zapata-antonio/Azure-Lab-04-B2B-Invitados) | Invitados externos |
| Identidad | [Lab 05 – Conditional Access](https://github.com/zapata-antonio/Azure-Lab-05-CA-GeoBlock) | Políticas de riesgo |
| Identidad | [Lab 06 – PIM (JIT)](https://github.com/zapata-antonio/Azure-Lab-06-PIM-JIT) | Privilegios Just-In-Time (Eligible/Activate) |
| Identidad | [Lab 07 – Access Reviews](https://github.com/zapata-antonio/Azure-Lab-07-AccessReviews) | Revisión periódica + auto-remediación |
| Identidad | [Lab 08 — RBAC: Azure Key Vault (Users & Managed Identity)](https://github.com/zapata-antonio/Azure-Lab-08-RBAC-BillingReader) | Lectura segura de secretos desde portal y App Service |
| Identidad | [Lab 09 — Conditional Access + Intune (BYOD Compliance)](https://github.com/zapata-antonio/Azure-Lab09-conditional-access-intune-byod-noncompliant) | Control de acceso BYOD mediante cumplimiento del dispositivo |
| Identidad | [Lab 10 – Enterprise Applications (SSO)](https://github.com/zapata-antonio/Azure-Lab-10-EnterpriseApps-SSO) | Enterprise Applications |Administrative Units](https://github.com/zapata-antonio/Azure-Lab-09-AdministrativeUnits) | Delegación regional sin visibilidad global |
| Identidad | [Lab 11 – Administrative Units](https://github.com/zapata-antonio/Azure-Lab-11-AdministrativeUnits) | Delegación regional sin visibilidad global |
| Infraestructura | [Lab 12 – VNet & Subnets](https://github.com/zapata-antonio/Azure-Lab-12-VNet-Subnets) | Diseño de red |
| Infraestructura | [Lab 13 – NSG](https://github.com/zapata-antonio/Azure-Lab-13-NSG-Web) | Control de tráfico (seguridad de red) |
| Infraestructura | [Lab 14 – Bastion](https://github.com/zapata-antonio/-Lab-14---Administraci-n-segura-de-m-quinas-virtuales-con-Azure-Bastion) | Acceso seguro sin IP pública |
| Infraestructura | [Lab 15 – Peering](https://github.com/zapata-antonio/Lab-15-Interconexi-n-de-Redes-con-VNet-Peering) | Redes entre regiones / VNets |
| Infraestructura | [Lab 16 – Private Endpoints](https://github.com/zapata-antonio/Azure-Lab-16-PrivateEndpoints-Storage) | Acceso privado a servicios (Storage, etc.) |
| Infraestructura | [Lab 17 – VM & Disks](https://github.com/zapata-antonio/Azure-Lab-17-VM-DataDisks) | Compute + discos + rendimiento |
| Infraestructura | [Lab 18 – Backup](https://github.com/zapata-antonio/Azure-Lab-18-AzureBackup) | Continuidad de negocio |
| Infraestructura | [Lab-19-Despliegue-de-Aplicaciones-PaaS](https://github.com/zapata-antonio/Lab-19-Despliegue-de-Aplicaciones-PaaS) | Despliegue de Aplicaciones PaaS |
| Seguridad | [Lab-20-Firmas-de-Acceso-Compartido-SAS](https://github.com/zapata-antonio/Azure-Lab-20-Firmas-de-Acceso-Compartido-SAS-) | Shared Access Signature (SAS) – Acceso temporal a un blob |
| Seguridad | [Lab 21 – Key Vault](https://github.com/zapata-antonio/Azure-Lab-21-Azure-Key-Vault---Proteccion-de-Secretos) | Gestión de secretos y claves |
| Operaciones | [Lab 22 – Budgets + Runbook](https://github.com/zapata-antonio/Azure-Lab-22-Budgets) | Budgets + Runbook (Stop VM por umbral) |
| Operaciones | [Lab 23 – Monitor](https://github.com/zapata-antonio/Lab-23-Azure-Monitor-Alerta-de-CPU-en-m-quina-virtual) | Métricas, logs y alertas |
| Gobierno | [Lab 24 – Policy](https://github.com/zapata-antonio/Lab-24-Azure-Policy---Restricci-n-de-Regiones) | Cumplimiento y guardrails |
| Seguridad | [Lab 25 – Log Analitics - KQL](https://github.com/zapata-antonio/Lab-25-Log-Analytics-y-consultas-KQL) | Log Analitics - KQL |
| Troubleshooting | [Lab 26–34 – Incidencias reales](https://github.com/zapata-antonio/Incidencias) | Casos prácticos de diagnóstico |


## ⚙️ Terraform / Infraestructura como código

| Fase | Laboratorio | Descripción |
|---|---|---|
| Terraform | [Lab TF-01 – VNet + Subnet + NSG + VM](https://github.com/zapata-antonio/Lab TF-01) — Despliegue de infraestructura básica con Terraform-Microsoft Azure
 | Despliegue básico de red y máquina virtual con Terraform |
| Terraform | Lab TF-02 – Storage + Key Vault + Private Endpoint | Despliegue seguro de Storage y Key Vault con acceso privado |
---

## 👨‍💻 Sobre mí

Administrador Cloud especializado en:
- Azure (AZ-104)
- Identidad y Acceso (SC-300)
- Seguridad y Gobierno Cloud
- Automatización de infraestructura con Terraform

Este portfolio refleja **mi forma real de trabajar en entornos empresariales**.


## 📫 Contacto

LinkedIn:www.linkedin.com/in/antonio-zapata-cloud

Email: zapatantonio@gmail.com
