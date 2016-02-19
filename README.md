# prueba1
library (foreign) reglin &lt;- read.dbf ("/home/sgr/Desktop/reg_simple.dbf") View (reglin) reg &lt;- lm( GASTO ~ INGRESO , data=reglin) summary (reg)
