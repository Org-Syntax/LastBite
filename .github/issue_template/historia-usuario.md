# Historias de Usuario - LastBite (Sprint 1)

## HU-01: Registro y Perfil de Comercio Local
**Como** propietario de un establecimiento comercial (panadería, repostería, restaurante),  
**Quiero** registrar mi negocio con sus datos básicos (nombre, dirección, horario de recogida y contacto),  
**Para** poder publicar paquetes de excedentes de comida a precio reducido.

### Criterios de Aceptación:
1. El sistema permite registrar datos: Nombre del local, NIT/Identificación, Dirección, Teléfono, Horario habitual de atención y Horario permitido para recogida de paquetes.
2. La contraseña debe cumplir con políticas mínimas de seguridad (mínimo 8 caracteres, mayúscula, número y carácter especial).
3. Una vez registrado, el usuario puede iniciar sesión y editar la información de su perfil comercial.
4. Si falta algún campo obligatorio, el sistema muestra mensajes de validación claros en pantalla.

---

## HU-02: Publicación de Paquete Excedente de Comida
**Como** comerciante registrado,  
**Quiero** crear y publicar un paquete de comida sobrante especificando foto, descripción, cantidad disponible y precio con descuento,  
**Para** ponerlo a la venta antes del cierre del día.

### Criterios de Aceptación:
1. El formulario solicita: Título del paquete, Descripción breve, Categoría (Panadería, Dulce, Salado, Mixto), Precio original, Precio de oferta (mínimo 30% de descuento), Cantidad disponible e Imagen del paquete.
2. El sistema calcula automáticamente el porcentaje de descuento ofertado para mostrarlo en el catálogo.
3. El estado inicial del paquete pasa a "Disponible" inmediatamente después de guardarse.
4. El comercio puede editar la cantidad disponible o inactivar la publicación en cualquier momento.

---

## HU-03: Visualización de Catálogo de Ofertas Cercanas
**Como** cliente/usuario final,  
**Quiero** explorar la lista de paquetes disponibles en los comercios locales,  
**Para** seleccionar la oferta de comida de mi interés.

### Criterios de Aceptación:
1. El catálogo muestra tarjetas (cards) con: Imagen del paquete, Nombre del local, Título de la oferta, Precio original (tachado), Precio final, Porcentaje de descuento y Horario de recogida.
2. Los paquetes cuyo stock sea cero (0) o cuyo horario de recogida haya vencido se muestran como "Agotado" o "Finalizado".
3. Se incluye un buscador simple por texto (por nombre de paquete o nombre del local) y filtro por categoría.
4. El diseño es 100% responsivo y ejecutable en dispositivos móviles y de escritorio.

---

## HU-04: Reserva de Paquete y Confirmación
**Como** cliente/usuario final,  
**Quiero** reservar un paquete de comida desde la plataforma,  
**Para** asegurar mi compra y pagar directamente en el establecimiento al momento de recogerlo.

### Criterios de Aceptación:
1. Al presionar "Reservar", se descuenta 1 unidad del stock disponible del paquete.
2. El sistema genera un código de reserva único (ejemplo: `LB-8921`) y muestra una pantalla de confirmación con el resumen de la orden y la dirección del local.
3. El estado de la reserva queda marcado como "Pendiente de Recogida y Pago en Sitio".
4. Si el stock del paquete es 0, el botón "Reservar" se inhabilita.