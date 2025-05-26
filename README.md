# Ejercicio: Sistema Completo de Gestión para Veterinaria con Serialización CSV y JSON

### Contexto:
La Clínica Veterinaria "Amigos Peludos" continúa mejorando su sistema digital de gestión. Ahora desean añadir funcionalidades avanzadas que permitan almacenar y recuperar fácilmente información sobre mascotas, dueños y consultas mediante archivos externos, usando formatos CSV y JSON para facilitar el intercambio de datos y respaldos.

## Descripción del Ejercicio:
En equipos de 2 a 3 personas, expandirán la aplicación previamente desarrollada para incorporar la capacidad de serializar (guardar) y deserializar (cargar) datos en archivos CSV y JSON.

## 📌 Requisitos adicionales de la Aplicación:
### 1. Serialización y Deserialización:

- Implementar funciones que permitan:

    - Guardar la información de mascotas y dueños en archivos CSV.
    - Guardar las consultas veterinarias en archivos JSON.
    - Cargar la información previamente guardada desde estos archivos al iniciar la aplicación.
    - Guardar la información existente en la aplicación al finalizar la aplicación.

- Opcionalmente, se podrán proporcionar opciones específicas en el menú principal para:
    - Exportar información actual (guardar).
    - Importar información existente (cargar).


### 2. Estructura de archivos recomendada:

- `mascotas_dueños.csv`: información básica de mascotas y dueños.
- `consultas.json`: historial de consultas veterinarias.


### 3. Interacción en consola actualizada:

- Añadir al menú principal opciones claras para exportar/importar información (si lo deciden así).
- Gestionar excepciones y logging al manipular archivos.
 
### 🔧 Aspectos técnicos obligatorios adicionales:
- Serialización y deserialización con módulos csv y json.,
- Manejo robusto de archivos (abrir, cerrar, leer, escribir).,
- Integración con manejo de excepciones y logging ya implementados.,

### Consideraciones adicionales:
- Asegurar que la serialización/deserialización sea clara y bien documentada.,
- Validar la integridad de los datos al cargar desde archivos.,

### 📦 Entregable:
- Código fuente actualizado del proyecto (.py).
- Archivos generados durante la serialización (mascotas_dueños.csv, consultas.json).
- Archivo de logs actualizado.
- Comentarios detallados sobre la implementación de la serialización y deserialización.

## Integrantes
- Daniel Cano Suarez
- Miguel Cerquera Arias
- Esteban Eusse Munera
