# Gestion_energia_y_sensores
🔧 Placa Trasera (Arduino #1)
Driver L293D: controla el motor DC trasero.

Sensores: alimentados desde esta placa.

Batería: probablemente conectada aquí (7.4V).

🔧 Placa Delantera (Arduino #2)
Servo motor: conectado a pin de señal.

Sensor ultrasónico: conectado a pines de señal (Trig/Echo).

Cámara IA: conectada para procesamiento o transmisión de datos.

Componentes y fuentes
Arduino #1	5V regulada desde batería	Usa buck converter.
Arduino #2	5V regulada desde batería	Igual que el anterior.
Motor DC	7.4V directa vía L293D	Controlado por Arduino #1.
Servo	5V externa regulada	No desde pin 5V del Arduino.
Sensor ultrasónico	5V regulada	Bajo consumo.
Cámara IA	Según especificación	Algunas requieren 5V o USB.
