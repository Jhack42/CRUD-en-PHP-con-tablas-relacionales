# CRUD en PHP con Tablas Relacionales

El diseño web es fundamental para la interacción del usuario. Busca la usabilidad y mejora la experiencia del usuario. Un diseño atractivo y funcional marca la diferencia en la interacción con el usuario.

## Objetivo
Desarrollar un programa CRUD con un buen diseño de pantalla y todas las funcionalidades.

Considerar las siguientes funcionalidades:
- **Nuevo**
- **Editar**
- **Eliminar**
- **Buscar**
- **Exportar a Excel**
- **Exportar a PDF**
- **Paginación**

[![chrome-91817-MPWZ1.png](https://i.postimg.cc/tgb1qLRp/chrome-91817-MPWZ1.png)](https://postimg.cc/3kLr9fDc)

use ecommerce;
 
CREATE TABLE tabla (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(255) NOT NULL,
    descripcion TEXT
);
