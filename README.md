# Propósito del Código: Simulación y Análisis de Señales con la Transformada de Fourier
El objetivo de este código es simular y analizar señales en el dominio del tiempo y de la frecuencia utilizando la Transformada de Fourier (FFT) en Python. Se generan tres tipos de señales básicas:
- **Pulso rectangular**
- **Función escalón**
- **Señal senoidal**

El propósito principal es transformar estas señales del dominio del tiempo al dominio de la frecuencia para visualizar cómo se descomponen en componentes de frecuencia. Además, se verifica el comportamiento de las señales y las propiedades matemáticas fundamentales de la Transformada de Fourier, como:

- **Linealidad**: Verificar cómo la suma de señales en el dominio del tiempo afecta al espectro de frecuencia.
- **Desplazamiento en el tiempo**: Analizar cómo el desplazamiento temporal de una señal afecta a su espectro de frecuencia (cambio de fase).
- **Escalamiento en frecuencia** (opcional): Explorar cómo cambiar la frecuencia de una señal afecta a su espectro de frecuencia.


# Propósito del código
Este código se diseñó para lograr los siguientes objetivos:

1. **Generar señales elementales**:
   - **Pulso rectangular**: Señal de duración corta con un cambio brusco de 0 a 1.
   - **Función escalón**: Señal constante después de \( t = 0 \).
   - **Señal senoidal**: Onda periódica de frecuencia específica (50 Hz).
   
2. **Aplicar la Transformada de Fourier (FFT)**:
   - Calcular la Transformada de Fourier de cada señal utilizando la función `np.fft.fft()`.
   - Usar `np.fft.fftshift()` para centrar el espectro de frecuencia, mostrando tanto las frecuencias negativas como las positivas.

3. **Visualización**:
   - Mostrar las señales originales en el dominio del tiempo para observar su forma.
   - Graficar los espectros de frecuencia de cada señal, para ver las componentes de frecuencia de las señales originales.

4. **Comprobar propiedades de la Transformada de Fourier**:
   - **Linealidad**: Se verifica sumando señales y observando si la FFT de la suma es igual a la suma de las FFTs individuales.
   - **Desplazamiento en el tiempo**: Se observa cómo el desplazamiento temporal de una señal afecta a la fase de su espectro.
   - **Escalamiento en frecuencia**: Se analiza cómo cambiar la frecuencia de una señal afecta su espectro (si se opta por incluir este análisis).

Este código proporciona una manera práctica de visualizar cómo las señales se componen de diferentes frecuencias y cómo su comportamiento cambia cuando se transforman al dominio de la frecuencia.



