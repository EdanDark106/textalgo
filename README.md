# MiTeleferico
-lineas:Linea()
-cantidadIngresos;float
+mi teleferico()
+agregarPersonasFila(persona p ,string,linea)
+agregarCabina(String linea)

(MiTeleferico tiene dirigido un rombo negro desde Linea)

Linea
-color:string
-filaPersona:Persona
-cabinas:Cabinas
-cantidadCabinas:int
+linea(color)
+agregarPersona(persona p)
+agregarCabina(nroCab)

(Linea tiene dirigido un rombo negro desde cabina)
(Linea tiene dirigido un rombo vacio desde Persona)

cabina
-NroCabina:int
-personaAbordo:persona
+Cabina(nroCabina)
+agregarPersona(persona p)

(Cabina tiene dirigido un rombo vacio desde Persona)

persona
-nombre: string
-edad:imt
-pesoPersona :float
+persona(nombre, edad, peso)

implementar un metodo para agrefar la primera persona en la cabina nroX (se per,ite maximo 10 personas o que no se supere el peso maximo 850 kg por cabina)
Verificar  que todas las cabinas cumplan con las reglas de abordo a las lineas de mi teleferico
Calcular el ingreso total de toads las lineas
-tarifa preferencia:personas menores a 25 y mayores a 60 pagan 1.5
-tarifa regular :3 bs
Mostrar la linea con mas ingreso solo con tarifa regular
NOta: la implemetacion y soluciondebe estar deacuerdo al diagrama. Solamente se tienen las lineas Amarillo rojo y verde se pueden agregar metodos adicionales en todas las cllases no se pueden agrefar atributos adicionales
















app spotify registrar usuarios gestionar artistas y administrar el catalogo de canciones disponibles
los artistas tienen seguidores que aumentan cada artista puede una varias canciones
realizar un diagrama uml de 4 clases
con almenos 3 atributos en cada clase y 2 metodos en el diagrama 
(el segundo tiene dirigido un rombo vacio desde el primero)
(el segundo tiene dirigido un rombo vacio desde el tercero)
el tercero tiene dirigido un rombo negro desde el cuarto

el cuarto tiene dirigido una linea desde el primero y tercero

2
