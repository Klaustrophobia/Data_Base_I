## TABLAS 

    - Suscriptores
    - Lineas Telefonicas
    - Tipos Lineas
        Post-Pago
        Pre-Pago
    - Marcas
    - Modelos
    - Tipos de Servicios
        Llamadas
        Mensajes
        Internet
    - Historial de Acreditacion de Saldo [PREPAGO]
    - Paquetes Promocionales PREPAGO
    - Tipos de Pago
    - Planes PostPago
    - Historial de Pagos POSTPAGOS
    - Historial de Eventos
        Llamadas
        Mensajes
        Mb de Internet
    - Sucursales
    - Administradores
    - 


### ESTRUCTURA
    Suscriptores
        ID Suscriptor [PRIMARY KEY]
        Nombre
        Apellido
        ID
        Fecha Registro
        Fecha Nacimiento
        Genero
        Email
        Telefono Movil
        Telefono Fijo
        Profesion
        Empresa

    Lugar
        Codigo Lugar [Primary Key]
        Nombre Lugar
        Latitud
        Longitud

    Tipo Lugar
        Codigo Tipo Lugar [Primary Key]
        Tipo Lugar

    ** HACER UNA RELACION DE LUGAR A SUSCRIPTORES DE LUGAR DE NACIMIENTO Y DE RESIDENCIA **

    Tipo Identificacion 
        Codigo Tipo Identificacion [Primary Key]
        Tipo Identificacion
    
    Lineas Telefonicas
        Codigo Linea Telefonica [Primary Key]
        Numero Telefonico [Unique Key]        
        ID Suscriptor [Foreign Key]
        Codigo Tipo Linea [Foreign Key]
        Fecha Registro
        IMEI


    Tipos de Lineas
        Codigo Tipo Linea [Primary Key]
        Nombre Tipo Linea 

    



    
        




