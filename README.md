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
   java -cp bin MetodoEuler.Main
   ```

---

## Salida de Consola
--- RESULTADOSDEMINIMOSCUADRADOSYCORRELACION---
Sumatorias:n=5,X=15.0,Y=20.0,X2=55.0, Y2=86.0, XY=66.0
Pendiente(beta1): 0.6000
Ordenada alorigen(beta0): 2.2000
Modelo obtenido:Y= 2.2000+ 0.6000X
CoeficientedePearson(r): 0.7746
CoeficientedeDeterminacion(r2): 0.6000
Predicción para X = 6.0 -> Y = 5.8000

Process finished with exit code 0

## conclucion
El algoritmo cumple perfectamente su propósito matemático: las fórmulas de mínimos cuadrados funcionan de manera correcta, permitiendo trazar una línea de tendencia confiable y realizar estimaciones futuras.


