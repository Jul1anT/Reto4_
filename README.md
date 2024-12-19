## Ejercicio 1: Sistema de Clases Geométricas

### Descripción
Este sistema modela varias clases geométricas como puntos, líneas, rectangulos y triángulos. Permite calcular propiedades de estos como área, perímetro y distancias entre puntos según sea el caso.

### Componentes principales

1. **`Point`**:
   - Representa un punto en un plano cartesiano, definido por sus coordenadas `x` y `y`.

2. **`Line`**:
   - Representa una línea definida por dos puntos. Calcula distancias, pendientes y cruces con los ejes.

3. **`Shape`**:
   - Clase base para figuras geométricas. Gestiona los vértices y aristas de la figura, y permite verificar si la figura es regular.
   - **Atributos**:
     - `vertices`: Lista que contiene los puntos que forman la figura.
     - `edges`: Lista que contiene las líneas que forman la figura.

4. **`Rectangle` y `Square`**:
   - Clases que representan un rectángulo y un cuadrado, respectivamente, con métodos para calcular su área y perímetro.

5. **`Triangle`**:
   - Representa un triángulo definido por tres vértices. Permite calcular su área y perímetro.

## Ejercicio 2: Sistema de Restaurante

### Descripción
Un sistema que gestiona un menú, permite realizar pedidos, calcula totales con descuentos según las condiciones, y procesa pagos en efectivo o tarjeta.

### Componentes principales
1. **`MenuItem`**:
   - Clase base para ítems del menú con atributos comunes como nombre, precio, y tamaño.

2. **Subclases**:
   - **`Beverage`**: Para bebidas.
   - **`Appetizer`**: Para aperitivos.
   - **`MainCourse`**: Para platos principales.

3. **`Order`**:
   - Gestión de los pedidos, cálculo de totales, y aplicación de descuentos.

4. **`PaymentMethod`**:
   - Proporciona clases para manejar pagos en efectivo (`Cash`) o tarjeta (`Card`).

### Ejecución
El sistema permite:
- Visualizar el menú.
- Crear un pedido con múltiples ítems.
- Aplicar descuentos automáticos.
- Realizar pagos utilizando el método deseado.
