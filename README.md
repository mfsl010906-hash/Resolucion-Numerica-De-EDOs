# Resolucion-Nuemrica-De-EDOs
- actividad unidad 6
- instituto tecnologico superior de xalapa
- ingeneria en sistemas computacionales
- docente: Victor Hugo Vasquez Harrera
- Integrantes de equipo:
- Maria Fatima Sanchez Landa
- Maria de Los Angeles Rocha Botello
- Oscar Lozada Vargas

## Requerimientos del Entorno
- **Lenguaje:** Java SE 8 o superior (JDK 17 recomendado).
- **IDE Sugerido:** NetBeans, Eclipse, IntelliJ IDEA o VS Code.

## Descripción del Proyecto
Se implementa de forma modular en Java los algoritmos numéricos del Método de Euler y el Método de Runge-Kutta de 4º orden(RK4) para la resolución de Ecuaciones Diferenciales Ordinarias(EDOs), aplicando criterios de paro formales(N), experimentación variando el tamaño de paso (h) y comparación rigurosa contra soluciones analíticas exactas.
1. Clase MetodoEuler: Esta clase aproxima numéricamente la solución de una Ecuación Diferencial Ordinaria (EDO) de primer orden con condición inicial (Problema de Valor Inicial) en un intervalo determinado, de forma modular y controlada.
2. Clase MetodoRungeKutta: El objetivo de esta clase es aproximar con alta precisión (orden de convergencia O(h^4)) la solución de una Ecuación Diferencial Ordinaria (EDO) de primer orden con condición inicial en un intervalo definido.

## Instrucciones de Ejecución
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/mfsl010906-hash/Resolucion-Nuemrica-De-EDOs.git]
   cd Resolucion-Nuemrica-De-EDOs
   ```

2. Compilar el código:
   ```bash
   javac -d bin src/MetodoRungeKutta/*.java
   ```

3. Ejecutar la clase principal:
   ```bash
   java -cp bin MetodoEuler.java
   ```bash
   java -cp bin MetodoRungeKutta.java
---

## Salida de Consola Metodo Euler



## conclucion
El algoritmo cumple perfectamente su propósito matemático: las fórmulas de mínimos cuadrados funcionan de manera correcta, permitiendo trazar una línea de tendencia confiable y realizar estimaciones futuras.


