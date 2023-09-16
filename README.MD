He modelado la base de datos con las entidades que aparecen en el diagrama( aseguradora, Grupo, Marca,Coche y revisión) normalizando todo lo que he visto necesario. 
Pero quería hacer una aclaración. 
Había otra posibilidad de crear otra entidad más: moneda. tras darle muchas vueltas he decidido poner la moneda como un campo de la tabla revisión. Que indicará la Moneda con la que fue pagado el importe de la revisión. 
 Lo he decidido así aunque bien  bien es cierto que podría ser una entidad más y crear una relación entre revisión y moneda. 

Lo he decidido así porque no veo que moneda tenga  condiciones suficientes como para ser una entidad. Es algo que complementa aún campo(importe) de otra entidad(() Revisión). 

La situación cambiaría si por ejemplo almacenaramos el importe que costó el coche con su moneda. 
Al haber dos campos de dos entidades diferentes con la necesidad de guardar la moneda. Si sería candidata a ser un a entidad. 

Pero al final no he visto que tenga las características suficientes para modelarlo así. Además como en clase se dijo que klo modeláramos como creyéramos mejor.He decidido hacerlo así.

Pero quería aclararlo y marcar los motivos por qué modele y normalicé de ese modo. en ese caso.