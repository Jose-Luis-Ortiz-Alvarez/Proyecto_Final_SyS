# Proyecto_Final_SyS
Este proyecto es una simulación interactiva y educativa que explora las bases de los sistemas de comunicación digital modernos, como WiFi y 5G, a través de conceptos clave como la modulación QAM, señales I/Q, filtrado digital, OFDM, y canales ruidosos.
Está diseñado para combinar teoría y práctica en un entorno visual, donde se pueden manipular parámetros y observar cómo afectan a las señales y a su transmisión.
## Objetivos: 
  - Entender cómo se representan las señales en el dominio del tiempo y frecuencia.
  - Aplicar filtrado digital para extraer o eliminar componentes de una señal.
  - Generar señales analíticas y construir componentes I/Q.
  - Simular sistemas de modulación digital (QAM).
  - Evaluar el impacto del ruido en la comunicación (canal AWGN).
  - Explorar el funcionamiento del sistema OFDM como base de WiFi/5G.
  - Visualizar el flujo completo: bits → símbolos → señal → canal → recuperación de bits.
## ¿Qué incluye este proyecto?
  1. Transformada de Fourier:
      - Descomposición de señales en frecuencia, usando FFT y visualización del espectro. Se analiza una señal compuesta y se ve cómo la frecuencia revela su estructura
  2. Filtrado Digital:
     - Comparación entre filtros FIR e IIR aplicados a una señal con componentes no deseadas. Se visualiza cómo se eliminan frecuencias no deseadas, tanto en el tiempo como en el espectro.
  3. Transformada de Hilbert y Señales Analíticas:
     - Se genera una señal analítica a partir de una senoidal utilizando la transformada de Hilbert. Se visualiza la relación entre componente real e imaginaria y su interpretación como envolvente y fase instantánea.
  4. Señales I/Q y Modulación QAM:
     - Simulación de una constelación 16-QAM con puntos generados aleatoriamente. Se explican los conceptos de I y Q, cómo se combinan para transmitir símbolos, y cómo la constelación representa la modulación.
  5. OFDM – Multiplexación Ortogonal en Frecuencia:
     - Se realiza una simulación OFDM básica:
       - Mapeo QAM
       - IFFT para obtener señal en el tiempo
       - Comparación del espectro original y recuperado (FFT)
       - Comparación de un símbolo antes y después del canal
  6. WiFi y 5G:
     - Explicación completa del flujo de transmisión y recepción digital que usan tecnologías como WiFi y 5G: modulación QAM, multiplexación OFDM, señales I/Q, transformadas, y cómo estos sistemas logran alta eficiencia espectral.
## Estructura del Repositorio
### 1. Análisis y Filtrado de Señales:
  - Análisis en dominio del tiempo y frecuencia (FFT).
  - Construcción de señales sintéticas combinando varias frecuencias.
  - Diseño de filtros digitales (FIR/IIR).
  - Aplicación de filtros a señales ruidosas.
  - Visualización de resultados: formas de onda originales vs filtradas, y espectros comparativos.
### 2. Señales I/Q y Transformada de Hilbert: 
  - Generación de una señal base en fase (I).
  - Cálculo de su versión en cuadratura (Q) mediante la Transformada de Hilbert.
  - Visualización en el plano (Lissajous) y análisis espectral.
  - Extracción de envolvente y fase instantánea (dependiendo de la implementación actual).
  - Interpretación visual y teórica de cada componente.
### 3. Modulación, Canal Ruidoso y Demodulación (QAM + AWGN):
  - Implementación de modulación QAM (16, 64, 256 niveles).
  - Integración de canal AWGN ajustable por SNR (Eb/N0).
  - Demodulación y recuperación de componentes I/Q.
  - Visualización interactiva de las constelaciones original vs con ruido.
  - Gráfico comparativo de señales moduladas vs recibidas (primeros símbolos).
  - Evaluación del impacto de la SNR y orden QAM en la precisión de la demodulación.

**Realizado por:**
Esteban Becerra Loaiza
Laura Lorena Duque Ospina
Jose Luis Ortiz Alvarez
