# Guía de Uso para Impresoras 3D FabLabUV

## **Flujo de Trabajo**

### **Diseño en Fusion 360:**

1. **Diseña la Pieza:**
   - Crea tu diseño en el entorno de Fusion 360 creando un nuevo diseño de electrónica para crear tu modelo 3D.
   - Exporta el modelo 3D como archivo **STL**.

2. **O descarga un diseño de internet:**
   - [Cults3D](https://cults3d.com/es).
   - [Thingiverse](https://www.thingiverse.com/).

## **Configuración de las Impresoras Ender-3 en FabLabUV**

### **Software de Impresión: Ultimaker Cura**
- Descarga e instala **Ultimaker Cura** desde su [sitio oficial](https://ultimaker.com/software/ultimaker-cura/).
- Configura el perfil de la impresora (Ender-3 V2, Ender-3 Neo, Ender-3 Pro S1) en Cura seleccionando las opciones predefinidas para cada modelo.

### **Configuración General para las Impresoras Ender-3:**

1. **Tipo de Filamento Utilizado:**
   - **Material recomendado**: Filamentos de la marca **Esun** (PLA, ABS, PETG, etc.).

2. **Configuración de Extrusión:**
   - **Temperatura de extrusión**:
     - **PLA**: 190-220 °C.
     - **ABS**: 220-250 °C.
     - **PETG**: 220-245 °C.
   - **Temperatura de la cama caliente**:
     - **PLA**: 50-60 °C.
     - **ABS**: 80-100 °C.
     - **PETG**: 60-75 °C.

3. **Retracción Recomendada**:
   - **Distancia de retracción**: 6 mm.
   - **Velocidad de retracción**: 45-60 mm/s para minimizar las imperfecciones.

4. **Altura de Capa y Calidad**:
   - **Altura de capa**: 0.1 mm (alta calidad) a 0.3 mm (impresiones rápidas).
   - **Velocidad de impresión**: 40-60 mm/s (ajustar según el material).

5. **Configuración de Soportes y Adhesión**:
   - **Soportes**: Activar en Cura para modelos con partes sobresalientes. Usar la opción "Toque de la placa de construcción".
   - **Adhesión a la cama**: Se recomienda usar **brim** o **raft** para mejorar la adherencia y evitar deformaciones.

### **Configuración Específica por Modelo de Impresora:**

- **Ender-3 V2**: Configuración estándar en Cura, adecuada para PLA.
- **Ender-3 Neo**: Similar a la V2, con mejoras en la nivelación de la cama. Asegurar que la nivelación automática esté habilitada.
- **Ender-3 Pro S1**: Posee un extrusor directo para mayor precisión y compatibilidad con diferentes filamentos como PETG y filamentos flexibles.

### **Consejos Adicionales:**

- **Nivelación de la Cama**: Realizar antes de cada impresión para asegurar una buena adherencia.
- **Limpieza del Extrusor**: Mantener el extrusor limpio para evitar obstrucciones.
- **Pruebas de Retracción**: Imprimir modelos de prueba para ajustar la configuración y evitar hilos.
