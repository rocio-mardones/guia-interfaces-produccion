# guia-interfaces-produccion
Guía para encontrar una interfaz determinada. Verificar los mensajes de entrada y salida en la base de datos. Ambiente: Producción.

# Accesos a las bases de datos

Primero que nada se necesita tener acceso de lectura a las bases IIB y MBroker en SQLVDCSRV2.

-- Interfaces filtrado por nombre
select * from interfaces (nolock) where descripcion like '%Meli%'


# Buscar el nombre de la interfaz

Se debe ejecutar 
