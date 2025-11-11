# semana-0.1
Agencia de Viajes "Destinos del Mundo.
**Estudiante:** Alvaro Enrique Espejo Barreto  
**Ficha:** 3228970A  
**Dominio Asignado:** Agencia de Viajes "Destinos del Mundo"  

---

## 📋 Contexto del Dominio

**Tipo de Negocio:** Agencia de Viajes y Turismo  
**Nombre Comercial:** Destinos del Mundo  
**Ubicación:** Bogotá, Zona T  
**Especialidad:** Paquetes turísticos, reservas de vuelos, hoteles, tours.

> *Destinos del Mundo es una agencia que ofrece paquetes turísticos nacionales e internacionales, reservas de vuelos, hoteles, tours guiados y asesoría personalizada. Cuenta con 12 asesores y gestiona cerca de 200 reservas mensuales.*




## 📝 Actividad 1: Identificación de Objetos  
### Ejercicio 01

Identifica **5 objetos principales** del dominio:

---

### 1. Reserva de Viaje

- **¿Qué es?**  
  Es el registro que realiza un cliente para adquirir un paquete turístico u otro servicio de la agencia.
- **Atributos:**  
  - código de reserva  
  - cliente  
  - destino  
  - fecha de salida  
  - fecha de regreso  
  - precio
- **Métodos:**  
  - registrarReserva()  
  - calcularCosto()  
  - confirmarPago()  
  - cancelarReserva()

---

### 2. Cliente

- **¿Qué es?**  
  Persona que utiliza los servicios de la agencia y realiza reservas.
- **Atributos:**  
  - nombre  
  - documento de identidad  
  - correo electrónico  
  - teléfono  
  - historial de reservas
- **Métodos:**  
  - consultarReservas()  
  - actualizarDatos()  
  - realizarPago()

---

### 3. Asesor de Viajes

- **¿Qué es?**  
  Empleado encargado de atender clientes y gestionar las reservas.
- **Atributos:**  
  - nombre  
  - código de empleado  
  - especialidad  
  - listado de clientes asignados
- **Métodos:**  
  - registrarReserva()  
  - asesorarCliente()  
  - modificarReserva()

---

### 4. Paquete Turístico

- **¿Qué es?**  
  Conjunto de servicios ofrecidos por la agencia para un destino específico.
- **Atributos:**  
  - código de paquete  
  - destino  
  - hotel incluido  
  - vuelo incluido  
  - precio
- **Métodos:**  
  - mostrarDetalles()  
  - calcularPrecioTotal()  
  - agregarServicioAdicional()

---

### 5. Hotel

- **¿Qué es?**  
  Establecimiento asociado que aloja a los turistas.
- **Atributos:**  
  - nombre del hotel  
  - destino  
  - categoría (estrellas)  
  - precio por noche  
  - disponibilidad
- **Métodos:**  
  - consultarDisponibilidad()  
  - reservarHabitación()  
  - mostrarServicios()

---





## 📝 Actividad 2: Comparación de Paradigmas  
### Ejercicio 02

**Diferencias entre Programación Estructurada y Programación Orientada a Objetos:**  
- **Estructurada:** El código se organiza en funciones y variables sueltas.  
- **POO:** El código se organiza en clases que contienen atributos y métodos asociados.

---

**Ejemplo Conceptual: Reserva de Viaje**

#### 1. Programación Estructurada (variables y funciones):


