# operadores_ineficaces
Se requiere identificar a los operadores ineficientes que trabajan en el servicio de telefonía CallMeMaybe porque están desarrollando una nueva función que brindará dicha información a los supervisores y supervisoras de la compañía y así mejorar el servicio a los clientes.
## Data:

El dataset **calls** contiene los siguientes campos:

- *user_id* — ID de la cuenta de cliente.
- *date* — fecha en la que se recuperaron las estadísticas.        
- *direction*  — "dirección" de llamada (out para saliente, in para entrante).  
- *internal* — si la llamada fue interna (entre los operadores de un cliente o clienta).     
- *operator_id* — identificador del operador.
- *is_missed_call* — si fue una llamada perdida.  
- *calls_count* — número de llamadas.  
- *call_duration*  — duración de la llamada (sin incluir el tiempo de espera).  
- *total_call_duration* — duración de la llamada (incluido el tiempo de espera).

El dataset **clients** contiene los siguientes campos:

- *user_id*: ID de usuario/a
- *tariff_plan*: tarifa actual de la clientela
- *date_start*: fecha de registro de la clientela

## Libraries used:

pandas

matplotlib.pyplot

seaborn

numpy

scipy.stats as stats
