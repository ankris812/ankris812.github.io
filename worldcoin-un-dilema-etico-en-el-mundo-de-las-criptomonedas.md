Worldcoin: Un dilema ético en el mundo de las criptomonedas

En este post voy a hacer un pequeño analisis sobre la privacidad que se supone que tiene la criptomoneda WorldCoin

Primero de todo que es worldcoin(segun ellos): 

Worldcoin es un proyecto de criptomonedas que promete darte dinero a cambio de escanear tu iris. El proyecto, liderado por Sam Altman, CEO de OpenAI, tiene como objetivo crear una red global de identidad y finanzas registrando al menos a 2 mil millones de personas en todo el mundo. 

Sin embargo, los posibles riesgos y preocupaciones éticas en torno a la recopilación y almacenamiento de datos biométricos sensitivos han generado serias dudas sobre la viabilidad del proyecto.

Expondre esos riesgos y/o problemas en las siguientes lineas:

De primeras, si, segun ellos el orb elimina los escaneos del iris nada mas crear tu irishash( una cadena unica derivada del escaneo de tu iris), 
por lo menos ahora, que por defecto no almacena los datos biometricos recabados, ya que la app te da la opcion de hacerlo( antes venia marcado por defecto patra guardarlos, y de hecho, si lo desmarcabas no podias registrarte)

Que sea posible el uso indebido de datos biométricos y la falta de protección contra el robo o manipulación de datos, a parte de la poca claridad que se expone en el momento del registro, ya que no te dicen nada, y hasta ahora ni siquiera habia una indicacion de para mayores de edad( cosa que en muchos stand sigue sin estar) han provocado un escepticismo generalizado en la comunidad de las criptomonedas.

Segun ellos no registran a menores de edad, lo cual no es cierto en muchos stands, yo he visto con mis propios ojos a menores apuntandose.

Y sus orbes, tampoco es que sean tan perfectos como dicen, ya que en kenia, por ejemplo, se uso un fallo de seguridad, para crear identidades falsas y obtener tokens adicionales

Multiples paises han prohibido que sigan operando en su territorio: 

India

Kenia, que les obligo a cesar tras ver el atractivo que tenia, pero lo poco claros que eran con el manejo de los datos.

Francia, por lo mismo que kenia, que tiene ademas una investigacion en curso, y de la cual, la organizacion que la lleva, opina que su legalidad es cuanto menos, cuestionable

Por otra parte, las agencias de proteccion de datos de Alemania, España(la cual tiene varias denuncias en el tintero), Francia, Argentina, Brasil, tienen abiertas investigaciones contra la compañia que lo lleva por cuestiones de privacidad y legalidad.

Lo unico transparente en todo esto es el contrato inteligente que lo maneja, el cual tras cambiar a la cadena de optimism fue reemplazado( y lo hicieron mejor, el viejo era un autentico desastre), el cual tampoco esta exento de problemas que expondre ahora:

La version actual del contrato esta muy bien programada, y no habria demasiados probelmas, si no fuera porque el dueño del contrato, puede alterar el saldo a voluntad
Y no menos importnate, porque dos cuentas( propiedad del fundador y la empresa), poseen mas de la mitad de los tokens( cantidad suficiente para poder alterar el precio a voluntad)

Por otro lado, se supone que seria una red descentralizada, pero al menos por ahora( dijeron que seria cambiado, lo cual requiere un contrato nuevo), todo el sistema esta controlado por una unica wallet, que maneja las operaciones, es la dueña del contrato, y que puede ser reemplazada sin nignun problema por otra si el operador del contrato asi lo desea.
Esto implica que si un actor malicioso tomara el contrato bajo su control( no voy a explicar aqui como seria posible, pero lo es), podria reemplazar la cartera de gobernanza por una suya, transfiriendo de manera efectiva, el contrato y el control de la red a si mismo.

Bueno, pasemos al contrato antiguo, ya se que no es relevante actualmente, pero los antecedentes son importantes, no creen?, mas aun en un proyecto de este calibre.

El contrato/wallet que creaba los tokens, 

1. es privado  
2. no tiene limite de emision(mint)   
3. No hay limite de transferencia de tokens( importante cuando el owner posee el 47% de los activos)  
4. Todos los efectivos del contrato fueron emitidos usando un mixer(suele ocurrir cuando se quiere cometer un rugpull(tirar de la alfombra, tomar el dinero y huir), asi no podran rastrear la wallet original, para pedir responsabilidades)  
5. no hay ninguna clase de liquidez( en este caso es normal, el token estaba en closed mainnet, osea se puede transferir y emitir, pero no vender.  
6. el dueño posee gran parte de los tokens, lo que le permite hacer cosas como hacer caer el precio catastroficamente, vendiendo sus tokens y huyendo, osea un rugpull.  
