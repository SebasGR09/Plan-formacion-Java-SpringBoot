## Pasos para vender un producto

# Entradas
- SKU del producto.
- Cantidad solicitada.

# Proceso
1. Buscar el producto correspondiente al SKU ingresado. Si no existe, detener la operación e informar que **el producto no fue encontrado**.
2. Consultar el stock disponible del producto. Si no hay unidades disponibles, detener la operación e informar que **no hay stock para ese producto**.
3. Verificar que la cantidad solicitada sea mayor que cero. Si no lo es, detener la operación e informar que **la cantidad es inválida**.
4. Verificar que la cantidad solicitada no supere el stock disponible. Si lo supera, detener la operación e informar que **no hay stock suficiente**.
5. Calcular el subtotal multiplicando la cantidad solicitada por el precio unitario del producto.
6. Mostrar el subtotal de la operación.

# Salidas
- Pueden existir cinco distintas salidas dependiendo los valores dados:

1. *Producto no encontrado:* no existe un producto con el SKU ingresado.
2. *No hay stock:* el producto existe, pero no tiene unidades disponibles.
3. *Cantidad inválida:* la cantidad solicitada es igual o menor que cero.
4. *Stock insuficiente:* la cantidad solicitada supera el stock disponible.
5. *Subtotal calculado:* todas las validaciones son correctas y se muestra el subtotal.
