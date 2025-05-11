# Proyecto de Seguridad Avanzada en Azure: MFA, Access Policies e Identity Protection

Este proyecto demuestra la implementación de controles avanzados de seguridad en Microsoft Azure, con enfoque en autenticación multifactor (MFA), políticas de acceso condicional y protección de identidad, alineado con los conceptos de la certificación **SC-900**.

## 📌 Objetivos

- Configurar la autenticación multifactor (MFA) para usuarios en Azure AD.
- Crear políticas de acceso condicional basadas en riesgo, ubicación y aplicación.
- Implementar Microsoft Entra Identity Protection para mitigar amenazas de inicio de sesión.
- Monitorear eventos de seguridad en Azure y ajustar configuraciones en tiempo real.

## 🛠 Tecnologías y Servicios Utilizados

- Microsoft Azure Portal  
- Azure Active Directory (Microsoft Entra ID)  
- Azure AD Conditional Access  
- Microsoft Entra Identity Protection  
- Azure Security Center  
- Windows Server (para simulación de entornos y usuarios)

## 🔐 Funcionalidades del Proyecto

- Activación y prueba de MFA en cuentas específicas.
- Aplicación de políticas de acceso condicional para reforzar la seguridad de aplicaciones y usuarios.
- Detección y respuesta a inicios de sesión sospechosos mediante Microsoft Entra.
- Monitoreo de eventos y ajuste de políticas de seguridad.

## 📂 Estructura del Proyecto

AzureSecurity-Advanced:
- screenshots/ # Imágenes del proyecto (configuraciones, alertas, pruebas)
- Proyecto_Seguridad_Azure_MFA_Identity_Protection_2025.pdf # Informe en PDF
- LICENSE
- README.md

## 📸 Evidencias del laboratorio

### 1. Creacion de Usuarios
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Creacion%20de%20Usuarios.jpg)

### 2. Agregar Usuarios a Grupos
![VM]([https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Agregar%20Usuarios%20a%20Grupos.jpg)

### 3. Habilitar Autentificacion MFA
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Habilitar%20Autentificacion%20MFA.jpg)

### 4. Test de Ingreso MFA a un usuario
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Test%20de%20Ingreso%20MFA%20a%20un%20usuario.jpg)

### 5. Prueba de Acceso MFA 2
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Prueba%20de%20Acceso%20MFA%202.jpg)

### 6. Portal Seguridad de Azure
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Portal%20Seguridad%20de%20Azure.jpg)

### 7. Creacion de Nueva directiva - Acceso Condicional
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Creacion%20de%20Nueva%20directiva%20-%20Acceso%20Condincional.jpg)

### 8. Nueva Directiva Creada y Activada - Acceso Condicional
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Nueva%20Directiva%20Creada%20y%20Activada%20-%20Acceso%20Condicional.jpg)

### 9. Prueba de Acceso Condicional de acuerdo ala Directiva
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Prueba%20de%20Acceso%20Condicional%20de%20acuerdo%20ala%20Directiva.jpg)

### 10. Creacion de Directiva - Microsoft Entra Identity Protection
![VM](https://github.com/Jhon010690/AzureIdentityProtection/blob/main/Imagenes%20Seguridad/Creacion%20de%20Directiva%20-%20Microsoft%20Entra%20Identity%20Protection.jpg)

## ✅ Resultados y Aprendizajes

- Se implementó MFA exitosamente, mejorando la seguridad de acceso a los recursos.
- Las políticas de acceso condicional permitieron restringir el acceso por ubicación, riesgo y tipo de dispositivo.
- Se aprendió a detectar inicios de sesión sospechosos y mitigar riesgos en tiempo real con Identity Protection.
- El monitoreo continuo y la posibilidad de ajustar políticas fueron clave para un entorno seguro y adaptable.

## 📘 Relación con Certificación

Este proyecto está alineado con la certificacion **SC-900: Microsoft Security, Compliance, and Identity Fundamentals**, demostrando conocimientos aplicados en:

- Identidades seguras en Azure
- Gestión de accesos
- Protección contra amenazas
- Arquitectura de confianza cero (Zero Trust)

## 📎 Recursos adicionales

- [Documentación oficial Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/)
- [Guía MFA en Azure](https://learn.microsoft.com/en-us/azure/active-directory/authentication/tutorial-enable-azure-mfa)
- [Introducción a Identity Protection](https://learn.microsoft.com/en-us/azure/active-directory/identity-protection/overview-identity-protection)

---



