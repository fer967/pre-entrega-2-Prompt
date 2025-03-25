# Bot Mantenimiento
### Problematica
#### Empresa del rubro inyeccion de plastico necesita reducir tiempo de maquina parada por fallas
### Solucion propuesta
#### Implementar una aplicacion con un bot integrado a una base de datos potenciado con IA. La DB tiene informacion tecnica de las maquinas, historial de fallas, reparaciones, etc. Consultando a traves del bot los tecnicos tendran un diagnostico de las fallas reportadas en tiempo real junto a una sugerencia de posibles soluciones
### Objetivos
#### 1. Reduccion del tiempo de maquina parada
#### 2. Optimizacion del mantenimiento preventivo
#### 3. Aumento de la productividad y reduccion de costos operativos
### Metodologia de Prompts aplicada
#### 1. modelo texto-texto  
##### `Input :`  descripcion de la falla
##### `Output :` diagnostico y posible solucion
#### 2. modelo texto-imagen
##### `Input :` solicitud de dashboard
##### `Output :` muestra grafico 
### Tecnologia
#### modelo Gemini 2.0 Flash
### Viabilidad 
#### La empresa cuenta con un area de Informatica para desarrollar la aplicacion, crear la base de datos y bridar soporte 
#### Con respecto a la app el bot primero consulta a DB interna y si no encuentra la respuesta esperada recien ahi consulta a la Api, con el fin de optimizar el rendimiento y reducir el uso de la Api, reduciendo costos 
### Escalabilidad
#### Desplegar la App para que los tecnicos la tengan instalada en sus moviles
#### Entrenar al modelo para que pueda predecir futuras fallas analizando el historial
