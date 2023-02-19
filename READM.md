Operações intermediárias e terminais

• O pipeline é composto por zero ou mais operações intermediárias e 
uma terminal.

• Operação intermediária: 

• Produz uma nova streams (encadeamento)
• Só executa quando uma operação terminal é invocada (lazy evaluation)
• Operação terminal:
• Produz um objeto não-stream (coleção ou outro)
• Determina o fim do processamento da stream


Operações intermediárias

• filter
• map
• flatmap
• peek
• distinct
• sorted
• skip
• limit (*)
* short-circuit
 

Operações terminais

• forEach
• forEachOrdered
• toArray
• reduce
• collect
• min
• max
• count
• anyMatch (*)
• allMatch (*)
• noneMatch (*)
• findFirst (*)
• findAny (*)
* short-circuit
