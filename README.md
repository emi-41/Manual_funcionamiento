# Manual de Operación y mantenimiento

### **1. Introducción**
El presente documento proporciona directrices detalladas para la operación  y mantenimiento del brazo cartesiano, incluyendo procedimientos de uso, diseño, planes de colocación de equipos, programación de mantenimiento y protocolos de emergencia.

### **2. Características Técnicas**
- **Motores**: 3x Nema 17
- **Controlador**: ESP32
- **Drivers**: A4988
- **Sensor**: Hall
- **Correa Dentada**:
- **Rodamiento radial**: x4
- **Rodamiento Exéntrico**: x2
- 
# *Añadir dibujo con señalamiento de las piezas*

### **3. Procedimientos de Operación**
- **3.1. Inicio del sistema** <br>
   1. Verificar la alimentación eléctrica y encender la ESP32.
   2.  Revisar que los motores Nema 17 y los sensores de fin de carrera estén operativos.
   3.  Calibrar la posición inicial utilizando los sensores de fin de carrera.
   4.  Activar el sistema y ejecutar pruebas de movimiento sin carga.
- **3.2. Operación del Brazo Cartesiano** <br>
   1. Mover el brazo a la posición deseada utilizando el software de control.
   2. Activar el electroimán para sujetar el material metálico.
   3. Transportar el material a 90 grados y descender el brazo.
   4. Desactivar el electroimán para liberar el material.
   5. Retornar el brazo a su posición inicial.
### **4. Uso**
- Para mover el brazo, enviar comandos desde la interfaz.
- Para resetear la posición, presionar el botón de home.
### **5. SOP para Programación de Mantenimiento**
- **5.1. Mantenimiento Preventivo
1. Inspección visual de conexiones y componentes cada 30 horas de uso.
2. Lubricación de los tornillos sin fin y guías lineales cada 3 meses.
3. Verificación de la alineación de los motores y ajuste si es necesario.
4. Pruebas de detección de material con el sensor Hall.
- ** 5.2. Mantenimiento Correctivo**
1. Diagnóstico de fallos en sensores y motores.
2. Reemplazo de piezas desgastadas o defectuosas.
3. Recalibración del sistema tras la reparación.
4. Registro de mantenimiento con detalle de la intervención realizada.
### **6. Protocolos de Emergencia y Directrices de Seguridad**
-**6.1.Procedimientos en Caso de Emergencia** 
1. **Corte de energía:** En caso de sobrecarga, apagar el sistema y revisar el cableado.
2. **Fallo en motores:** Detener el sistema, revisar conexiones y drivers.
3.**Fallo del electroimán:** Verificar la alimentación y asegurarse de que el voltaje es el correcto.
-**6.2.Directrices de Seguridad** 
1. Uso obligatorio de guantes y gafas de protección durante el mantenimiento.
2. No operar el equipo con piezas sueltas o fuera de calibración.
3. Mantener el área de trabajo libre de obstrucciones.
4. Capacitación periódica en operación y mantenimiento del sistema.
