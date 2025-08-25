# 📘 Conceptos Básicos de Fundamentos de Programación  

## 1. **Algoritmo**  
Conjunto de pasos ordenados y finitos que permiten resolver un problema.  

- **Ejemplo cotidiano:**  
  > Preparar café: hervir agua → colocar café en la taza → agregar agua caliente → revolver → servir.  

- **Ejemplo en pseudocódigo:**  
  ```text
  INICIO
    Leer número1
    Leer número2
    suma ← número1 + número2
    Imprimir suma
  FIN
  ```

---

## 2. **Lenguaje de Programación**  
Es un medio formal para escribir algoritmos y comunicarse con la computadora.  

- **Ejemplo en Python:**  
  ```python
  numero1 = int(input("Ingresa un número: "))
  numero2 = int(input("Ingresa otro número: "))
  print("La suma es:", numero1 + numero2)
  ```

---

## 3. **Estructura Básica de un Programa**  
1. **Entrada** → Datos iniciales.  
2. **Proceso** → Instrucciones.  
3. **Salida** → Resultado final.  

- **Ejemplo:**  
  > **Problema:** Calcular el área de un rectángulo.  
  ```python
  base = 5
  altura = 3
  area = base * altura
  print("Área:", area)
  ```

---

## 4. **Elementos Fundamentales**  

- **Tipos de datos:**  
  - Entero → `10`  
  - Real → `3.14`  
  - Carácter → `'A'`  
  - Booleano → `True` / `False`  

- **Ejemplo en C++:**  
  ```cpp
  int edad = 20;
  float precio = 45.99;
  char inicial = 'J';
  bool activo = true;
  ```

---

## 5. **Entorno de Desarrollo**  

Proceso de **compilación → enlace → ejecución → depuración**.  

- **Ejemplo de error de sintaxis (Python):**  
  ```python
  print("Hola mundo"  # falta cerrar paréntesis
  ```

---

## 6. **Representación de Algoritmos**  

- **Diagrama de flujo:**  
  Ejemplo: la lámpara no funciona  

  ![Diagrama de flujo - lámpara](/img/imagen1.png "{width='350'}")

- **Pseudocódigo:**  
  ```text
  INICIO
    Si lámpara no funciona Entonces
        Si no está enchufada Entonces
            Enchufarla
        Sino
            Si foco está quemado Entonces
                Reemplazar el foco
            Sino
                Comprar nueva lámpara
            FinSi
        FinSi
    FinSi
  FIN


## 7. **Técnicas de Resolución de Problemas**  

1. **Definir claramente el problema.**  
2. **Divide y vencerás:** separar el problema en partes más pequeñas.  
3. **Análisis causa-efecto:** identificar la raíz del problema antes de resolverlo.  

- **Ejemplo simple:**  
  > Problema: Calcular el promedio de 3 calificaciones.  
  ```python
  cal1 = 90
  cal2 = 85
  cal3 = 95
  promedio = (cal1 + cal2 + cal3) / 3
  print("Promedio:", promedio)
  ```
