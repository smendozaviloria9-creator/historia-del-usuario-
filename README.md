Sistema de Gestión de Inventario (Python)
Un script sencillo en Python diseñado para gestionar el inventario de una tienda pequeña o uso personal. Permite registrar productos con su precio y cantidad, visualizar el stock actual y obtener estadísticas financieras rápidas.
 Características
Registro de Productos: Permite añadir nombres, precios y cantidades.
Manejo de Errores: Incluye validaciones para asegurar que el precio y la cantidad sean números válidos.
Visualización Detallada: Muestra una lista limpia de todos los productos registrados.
Cálculo Automático: Determina el valor total del inventario (precio × cantidad) y cuenta cuántos tipos de productos hay.
Interfaz de Menú: Navegación sencilla mediante consola.
 Requisitos
Python 3.x instalado en tu sistema.
💻 Cómo usarlo
Descarga o copia el archivo inventario.py.
Abre una terminal o consola de comandos.
Ejecuta el programa con:
bash
python inventario.py
Usa el código con precaución.

Sigue las instrucciones del menú en pantalla.
 Estructura del Código
El código se divide en funciones modulares para facilitar su lectura y mantenimiento:
agregar_producto(): Captura y valida los datos.
mostrar_inventario(): Recorre la lista de diccionarios.
calcular_inventario(): Realiza operaciones matemáticas sobre el stock.
menu_principal(): Controla el flujo lógico del programa
