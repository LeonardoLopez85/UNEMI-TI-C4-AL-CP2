# UNEMI-TI-C4-AL-CP2
Algebra Lineal - Componente Practico 2

Unidad 1 (Sistemas y Matrices):
  Usamos matrices (A = [v1, v2]) para representar la estructura del robot.
  Usamos la resolución de sistemas $Ax=b$ (comando inv(A)*Target_P) para calcular la cinemática inversa: ¿qué combinación de mis motores (vectores) necesito para llegar al punto Target?.
Unidad 2 (Determinantes):
  Calculamos det(A). En ingeniería, esto nos dice si la configuración del robot es válida. Si el determinante es 0, la matriz es singular y el robot pierde un grado de libertad (se "aplana"), lo que hace imposible controlar   su posición en 2D6666.
Unidad 3 (Espacios Vectoriales):
  Definimos el problema en $\mathbb{R}^2$. Tratamos las partes del robot como vectores con dirección y magnitud, aplicando las definiciones de vectores en $\mathbb{R}^n$7777.
Unidad 4 (Transformaciones, Independencia, Kernel):
  Independencia: Verificada implícitamente con el determinante. Si son independientes, forman una Base para el espacio de trabajo8888.
  Transformación: La matriz de rotación T es el ejemplo clásico de una Transformación Lineal. Movemos el robot mediante matemáticas matriciales9.
  Kernel y Rango: Usamos null(T) y rank(T) para demostrar teóricamente que una rotación no pierde información (el Kernel es vacío, el rango es completo)10.
