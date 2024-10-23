## Ejemplo 4.5.2

Vamos a analizar el sistema más sencillo de dos partículas, donde cada partícula puede ocupar solo dos lugares.

## Reflexiones

- **Estructura del Estado Cuántico**: Este estado se puede ver como una suma de combinaciones de los estados de cada partícula.

- **Importancia del Producto Tensorial**: Esto muestra que en el mundo cuántico, las propiedades de las partículas están conectadas, y el estado total es una mezcla de cómo contribuyen cada parte del sistema.

- **Amplitudes de Probabilidad**: En esta representación, cada estado está ligado a ciertos números, \(C_0\) y \(C_1\), que indican las probabilidades de que cada estado ocurra, lo cual es esencial en la mecánica cuántica.

- **Indeterminación Cuántica**: La forma en que se presenta el estado refleja que en los sistemas cuánticos, el resultado de una medición no se conoce hasta que se hace.

- **Relevancia en Computación Cuántica**: Entender cómo se combinan estos estados es clave para la computación cuántica, donde se aprovechan las propiedades de superposición y entrelazado para mejorar el rendimiento.

## Ejemplo 4.5.3

$$
|\psi\rangle = |x_0\rangle \otimes |y_1\rangle + |x_1\rangle \otimes |y_1\rangle
$$

Ahora, podemos expresar esto como una suma de combinaciones:

$$
|\psi\rangle = 0|x_0\rangle \otimes |y_0\rangle + 1|x_0\rangle \otimes |y_1\rangle + 0|x_1\rangle \otimes |y_0\rangle + 1|x_1\rangle \otimes |y_1\rangle
$$

Luego, tenemos:

$$
|\psi_x\rangle = C_0|x_0\rangle + C_1|x_1\rangle
$$

$$
|\psi_y\rangle = C_0|y_0\rangle + C_1|y_1\rangle
$$

Después:

$$
|\psi_x\rangle \otimes |\psi_y\rangle = C_{0x}C_{0y}|x_0\rangle \otimes |y_0\rangle + C_{0x}C_{1y}|x_0\rangle \otimes |y_1\rangle + C_{1x}C_{0y}|x_1\rangle \otimes |y_0\rangle + C_{1x}C_{1y}|x_1\rangle \otimes |y_1\rangle
$$

Podemos concluir que:

$$
C_{0y} = 0,
$$

$$
C_{1y} = 0,
$$

$$
C_{0x} = 1,
$$

$$
C_{1x} = 1.
$$

Por lo tanto, el sistema es separable.
 
