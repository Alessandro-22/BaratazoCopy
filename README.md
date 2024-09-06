# Sistema de Ventas Online de Componentes de PC

## Descripción
Este proyecto es un sistema de ventas online especializado en componentes de PC. Ofrece una plataforma fácil de usar para que los clientes puedan navegar, comparar y comprar una amplia gama de componentes de PC, desde procesadores y tarjetas gráficas hasta periféricos y accesorios.

## Características principales
- Catálogo completo de componentes de PC
- Sistema de búsqueda y filtrado avanzado
- Comparación de productos
- Carrito de compras y proceso de pago seguro
- Sistema de reseñas y calificaciones de productos
- Panel de administración para gestión de inventario y pedidos
- Integración con proveedores para actualización automática de stock y precios

## Tecnologías utilizadas
- Frontend: React.js
- Backend: Node.js con Express
- Base de datos: MongoDB
- Autenticación: JSON Web Tokens (JWT)
- Pasarela de pago: Stripe

## Instalación
1. Clonar el repositorio:
   ```
   git clone https://github.com/tu-usuario/sistema-ventas-pc.git
   ```
2. Instalar dependencias:
   ```
   cd sistema-ventas-pc
   npm install
   ```
3. Configurar variables de entorno:
   - Crear un archivo `.env` en la raíz del proyecto
   - Añadir las siguientes variables:
     ```
     PORT=3000
     MONGODB_URI=tu_uri_de_mongodb
     JWT_SECRET=tu_clave_secreta_jwt
     STRIPE_API_KEY=tu_clave_api_de_stripe
     ```

4. Iniciar el servidor:
   ```
   npm start
   ```

## Uso
- Acceder a `http://localhost:3000` en tu navegador
- Crear una cuenta de usuario o iniciar sesión
- Explorar el catálogo, añadir productos al carrito y realizar compras

## Contribución
Las contribuciones son bienvenidas. Por favor, sigue estos pasos:
1. Haz un fork del proyecto
2. Crea una nueva rama (`git checkout -b feature/AmazingFeature`)
3. Realiza tus cambios y haz commit (`git commit -m 'Add some AmazingFeature'`)
4. Haz push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## Licencia
Distribuido bajo la licencia MIT. Ver `LICENSE` para más información.

## Contacto
Tu Nombre - [@tu_twitter](https://twitter.com/tu_twitter) - email@example.com

Enlace del proyecto: [https://github.com/tu-usuario/sistema-ventas-pc](https://github.com/tu-usuario/sistema-ventas-pc)
