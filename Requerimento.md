# Procedimiento previo con excel antes del bot de sap. 


1er procedimiento en SAP. (Crear recaudo en SAP)

Conexión de la hoja con google sheets destinado. 

(Generales)
Campos en sap: 
- Clase : DZ  
- Sociedad : SISS
- Moneda : COP 
- Referencia: "19 - Nombre del formato"
- Fehca documento: Fecha del pago 
- Fecha factura : Fecha actual ( hoy )
- text doc y text comp. : Concatenar: PG + Fecha del pago (sheets) + "$valor del pago" (sheets). 


Datos bancarios: 

Cuenta bancaria: Cuenta contable ( sheets)
Importe: Valor del pago. 
Fecha valor : Fecha del pago
Texto == text doc 
Asignación: 16 - R Medellin (Cod red / Nom of vtas)


Selección de partida. 

Cuenta: Cod cliente (formato)
Clase de cuenta: "D"
Indicador CME: "A"
Otras cuentas ( Marcar casilla)


Luego de diligenciar las tres secciones anteriores le damos (Enter).

Se abre la ventana de: **Otras cuentas**

Cuenta: 

- Se ingresa el codigo del cliente (Cuenta)
- ClCta : D : 
- Soc. :  AGCO
# Está en un veremos: PAs Marcar casilla 
- Indicador CME : "A"
- Click en boton Continuar.

