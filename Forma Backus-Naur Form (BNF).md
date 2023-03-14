---
share: true
folder: LENGUAJES FORMALES Y AUTOMATAS
---
Esta notación por John Backus y peter Naur para lenguaje de AlGOL58(1958)
- El simbolo de reescritura $\rightarrow$ a ::= 
#### Ejemplo de notación :
	programa{
	a=2;
	b=3;
	c=a+b+1;
	}
##### Bloque de sentencias	
	####Sentencias 
		a=2; Asignación (a identificador 2 valor )
		b=3;
### Ejemplo programa 
	<Programa>::= programa{<BloqueSentencias >}
	<BloqueSentencias>::=<Sentencia>
	<BloqueSentencias>::=<Sentencia><BloqueSentencias>
	<Sentencia>::=<Asignación>
	<Asignación>:=<Id>=<Val>;
	<Val>::=<Numero>|<Id>|<Val>+<Val>
	<Numero>:= [0-9]
	<Id>=[a-c]
