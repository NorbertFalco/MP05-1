# Activitats:

## Activitats Caixa Negra:

### Pizzeria Pepe:

Un programa controla si una comanda de pizzes la pot portar un repartidor.

Heu de tenir en compte que un repartidor pot portar 10 pizzes com a màxim a la moto.

El programa retorna true si la comanda es pot portar i false en cas contrari.

Es demana:

- Fer el codi font del programa.

![image](https://user-images.githubusercontent.com/114875463/216810572-518af581-fce0-48fd-a3f6-f323aced3316.png)


- Fer la taula amb les particions equivalents i casos vàlids i no vàlids.

![image](https://user-images.githubusercontent.com/114875463/216813022-8e0bf547-3eac-4727-8e54-9ce9d16de0f3.png)


![image](https://user-images.githubusercontent.com/114875463/216813137-8b3d912d-602c-44fa-8730-765eecf99a35.png)


- Fer la taula amb l'anàlisis de valors límit i casos vàlids i no vàlids.

![image](https://user-images.githubusercontent.com/114875463/216813298-5bbc55bc-8378-4e9b-a147-3d65711bc6f1.png)


![Captura de pantalla de 2023-02-05 10-16-17](https://user-images.githubusercontent.com/114875463/216811027-87e18b7c-7b33-4e42-bfb8-4ac323313ec6.png)



### Transports Jean Claude:

Un programa gestiona si una càrrega es pot portar amb una furgoneta.

Una càrrega sempre pesarà almenys 500 kg. per aprofitar el transport, però no podrà pesar més de 900kg.

Una furgoneta ha de tenir la capacitat de portar un pes mínima de 500kg i màxima de 750kg.

Si una càrrega no es pot portar el programa retorna -1, en cas contrari retorna 0.

Es demana:

- Fer el codi font del programa.

![image](https://user-images.githubusercontent.com/114875463/216812753-476c4adf-57c3-41e2-80b9-56c034586cc6.png)



- Fer la taula amb les particions equivalents i casos vàlids i no vàlids.

![image](https://user-images.githubusercontent.com/114875463/216813964-385b7bd1-93ba-4a9c-a828-d2686642598b.png)


- Fer la taula amb l'anàlisis de valors límit i casos vàlids i no vàlids.

![image](https://user-images.githubusercontent.com/114875463/216814185-e546c916-27ca-4804-9e44-cee9f9cf0c0f.png)

![image](https://user-images.githubusercontent.com/114875463/216815727-0dde9acb-4d46-45e5-9f5c-092193ad0d6d.png)



### Control de temperatura:

Un programa gestiona el modificador de temperatura del sistema de calefacció d'un restaurant.

Aquest programa rep la medició de la temperatura del restaurant en graus celsius, acceptant com entrades vàlides de -10 a 50 graus. (medidor)

A més té una entrada d'usuari/a amb la temperatura que es vol mantenir, que va de 15 a 40 graus. (termostat).

El sistema té tres sortides possibles que representen la potencia del sistema de calefacció: 0, 1, 2.

Segons la informació que té en cada moment el programa farà el següent:

Si la temperatura del medidor és més alta que la del termostat, la potencia del sistema serà 0.
Si la temperatura del medidor és més baixa o més alta que la del termostat però només entre 0 i 2 graus, la potència serà 1.
Si la temperatura del medidor és més baixa que la del termostat en més de dos graus, la potència del sistema serà 2.

Es demana:

- Fer el codi font del programa.

![image](https://user-images.githubusercontent.com/114875463/216815875-757b6b53-ee22-4b5d-b07a-06ed8cdf39cd.png)

- Fer la taula amb les particions equivalents i casos vàlids i no vàlids.

![Selecció_231](https://user-images.githubusercontent.com/114875463/216912529-532b1f13-c8a4-4b53-a5fd-7e4cb8d93cf9.png)

- Fer la taula amb l'anàlisis de valors límit i casos vàlids i no vàlids.

![Selecció_229](https://user-images.githubusercontent.com/114875463/216911830-4312c2e0-5646-45b0-a4d5-3ff57ce8326f.png)



## Activitats debug:

### Factorial:

El factorial d'un nombre és el resultat de multiplicar el número per ell mateix -1 tantes vegades com  siguin necessàries fins arrivar a 1.

Per exemple el factorial de 5 és:

5 * 4 * 3 * 2 * 1

![image](https://user-images.githubusercontent.com/110727546/206031980-55e59610-42bb-4cc6-9b5f-039d7f67e185.png)

Fes una funció factorial que rebi un número com paràmetre i retorni el seu factorial.

Es demana:

- Codi del programa.

![Selecció_232](https://user-images.githubusercontent.com/114875463/216915887-cc98c687-fae4-4afc-8e9b-fd5751ebedcd.png)

- Captura de pantalla amb un punt d'interrupció que deixi veure totes les crides a la funció (agafeu un valor menor a 10).

![Selecció_233](https://user-images.githubusercontent.com/114875463/216919553-be954164-6cda-4715-bd57-968a87c785d7.png)


### Taula de multiplicar:

Fes un programa que crea una matriu de números del 1 al 10.
Aquest programa rep per argument d'entrada un número sencer i retorna per terminal la taula de multiplicar d'aquest número multiplicant el argument per cada valor de la matriu.

Es demana:

- Codi del programa.

![Selecció_257](https://user-images.githubusercontent.com/114875463/217325101-b92bf67f-f953-4b35-a221-6331079e5f73.png)

- Captura de pantalla de com li passeu a IntelliJ com argument del programa un número. (Mireu exemple findAverage).

![Selecció_258](https://user-images.githubusercontent.com/114875463/217328169-6ffcaef6-d7a1-4eee-b02d-d3ebab000c3c.png)

- Captura de com feu un punt d'interrupció al bucle de creació de la matriu i mostreu els valors de la matriu.

![Selecció_259](https://user-images.githubusercontent.com/114875463/217328619-41ffa4e7-6f8a-46a9-9e42-e4bd34a26214.png)

- Captura de punt d'interrupció al bucle de multiplicació i com modifiqueu a ma els valors de la matriu de números per a que l'execució retorni el número 1 10 vegades quan l'argument d'entrada era 1.

![Selecció_260](https://user-images.githubusercontent.com/114875463/217329629-63fdbffd-f8b7-4c16-b405-303b021412e8.png)

![Menú_006](https://user-images.githubusercontent.com/114875463/217329656-30848137-360e-46a3-a406-7498b17f2737.png)

![Selecció_261](https://user-images.githubusercontent.com/114875463/217329912-ead57e56-44a6-4d80-9187-21943a875996.png)

![Selecció_262](https://user-images.githubusercontent.com/114875463/217329940-73f7297d-2ded-4755-a44e-0414d77e630b.png)







