# Proyecto de Graduación - Desarrollo de museo en realidad virtual para la conservación y preservación de reliquias antiguas

## 📝 Descripción
El **Ecomuseo de Realidad Virtual de San Andrés Semetabaj** es un proyecto innovador que busca preservar y promover la riqueza cultural y arqueológica de Guatemala a través de una experiencia inmersiva en realidad virtual. Este museo virtual permite a los usuarios explorar colecciones de artefactos en un entorno interactivo y educativo, empleando tecnologías como fotogrametría para garantizar una representación precisa y detallada de los objetos.

---

## 🛠️ Instrucciones de Instalación

### **Requisitos Previos**
Antes de iniciar, asegúrate de contar con los siguientes requisitos previos:

1. **Unity Hub**:
   - Descarga e instala [Unity Hub](https://unity.com/download).
   - A través de Unity Hub, instala la versión **2022.3.20f1** o cualquier versión compatible de Unity 2022.3.x.
2. **Plataformas de Build**:
   - **Meta Quest**: Instala el módulo de soporte para Android desde Unity Hub.  
     - Ve a **Installs > Add Modules** y selecciona **Android Build Support** junto con **OpenJDK**, **SDK** y **NDK**.
   - **PC**: Asegúrate de que el módulo para crear builds para tu sistema operativo esté instalado (Windows, macOS o Linux).
3. **Meta Quest Tools** (si aplicable): 
   - Configura tu dispositivo Meta Quest para el modo desarrollador y asegúrate de tener instalados los controladores necesarios.
4. **Control de Versión**:
   - Instala [Git](https://git-scm.com/) para clonar el repositorio.


---


### **Pasos para Instalar el Proyecto**

1. **Clonar el Repositorio**:
   Ejecuta el siguiente comando en tu terminal para clonar el proyecto:
   ```bash
   git clone https://github.com/Arem58/PG-2024-181099.git
   cd src/Prototipo Inicial

### **Abrir el Proyecto en Unity**

1. Abre **Unity Hub**, selecciona **Open**, y navega hasta la carpeta del proyecto clonado.
2. Verifica que la versión de Unity seleccionada sea **2022.3.20f1** o compatible.

---

### **Configurar el Proyecto**

1. Revisa la configuración del proyecto en **Edit > Project Settings**:
   - **Para Meta Quest**:  
     Configura la plataforma de build en **Android**:  
     Ve a **File > Build Settings > Android > Switch Platform**.
   - **Para PC**:  
     Configura la plataforma en **Windows, macOS o Linux Standalone**:  
     Ve a **File > Build Settings > Windows/Mac/Linux > Switch Platform**.

---

### **Instalar Dependencias**

Unity intentará descargar automáticamente las dependencias al abrir el proyecto. Si esto no ocurre, asegúrate de instalar manualmente las siguientes dependencias clave para el desarrollo VR:

---

- ##### **XR Plugin Management**

- ##### **XR Interaction Toolkit**

---

### **Demo**
- Una demostración visual del proyecto está disponible en el repositorio.  
  [Accede a la demo aquí](./demo/demo.mp4)

---

### **Informe Final**
- El informe final del proyecto de graduación está disponible en formato PDF en la carpeta `/docs/`.  
  [Descargar informe final](./docs/informe.pdf)
