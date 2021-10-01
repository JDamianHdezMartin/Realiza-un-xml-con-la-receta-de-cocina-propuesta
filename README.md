# Realiza-un-xml-con-la-receta-de-cocina-propuesta
Diseñar un documento válido en XML que permita estructurar la información de las recetas de cocina de un restaurante y aplicarlo a la siguiente receta de cocina. Hay que hacerlo de modo que un sistema informático pueda realizar búsquedas por ingredientes, cantidad de comensales o nombre de la receta.
## Sopa de cebolla

```bash
<?xml version="1.0" encoding="iso-8859-1" standalone="yes"?> 

<receta> 

	<plato>Sopa de cebolla</plato> 

	<numComensales>4</numComensales> 

	<ingrediente cantidad="1" unidadDeMedidad="Kg." nombre="cebollas" /> 

	<ingrediente cantidad="2" unidadDeMedidad="litros" nombre="caldo de carne" /> 

	<ingrediente cantidad="100" unidadDeMedidad="gramos" nombre="mantequilla" /> 

	<ingrediente cantidad="1" unidadDeMedidad="cucharada" nombre="harina" /> 

	<ingrediente cantidad="100" unidadDeMedidad="gramos" nombre="queso emmental suizo o gruyére rallado"/> 

	<ingrediente cantidad="" unidadDeMedidad="rebanadas" nombre="Pan tostado en rebanadas" /> 

	<ingrediente cantidad="" unidadDeMedidad="pizca" nombre="Tomillo" /> 

	<ingrediente cantidad="1" unidadDeMedidad="hoja" nombre="Laurel" /> 

	<ingrediente cantidad="" unidadDeMedidad="pizca" nombre="Pimienta" /> 


	<preparacion> 

		<paso>Pelar y partir las cebollas en rodajas finas</paso> 

		<paso>Rehogarlas con la mantequilla, sal y pimienta a fuego lento hasta que estén transparentes sin dorarse</paso> 

		<paso>Añadir la harina sin dejar de remover</paso> 

		<paso>Ponerlo en una cazuela con el caldo, el tomillo y el laurel</paso> 

		<paso>Dejar cocer a fuego lento durante unos 15 minutos</paso> 

		<paso>Poner las rebanadas de pan encima, espolvorear el queso y gratinar al horno</paso> 

	</preparacion> 

</receta> 
```
