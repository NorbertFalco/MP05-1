# Activitats: 

Per dibuixar els diagrames de flux podeu fer servir [draw.io](https://draw.io) o qualsevol altra eina online.

1. Calcula el CC de les següents figures:
  - ![image](https://user-images.githubusercontent.com/110727546/204613022-4ab64342-2e06-438d-a7e8-570685b3c406.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204613180-6d55bf09-28b8-417e-96f4-f71a762ac44c.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204655229-8c3f28d7-3d8b-4746-a55d-331f89da39d2.png)

  - **Resultat 1: 16 - 14 + 2 = 4
  - **Resultat 2: 16 - 14 + 2 = 4
  - **Resultat 3: 8 - 6 + 2 = 4


2. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:
  - ![image](https://user-images.githubusercontent.com/110727546/204615125-363e5e6c-173b-4ec0-8c0b-cb97985ade06.png)

  - **Diagrama:

![Selecció_189](https://user-images.githubusercontent.com/114875463/216544930-70d386f7-2601-4af6-922c-63bbc53e8150.png)

  - **Resultat CC: 2 + 1 = 3

3. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:

```
public class proves {
    public static  String queEmPoso(int temperatura) {
        String roba = "res";
        if(temperatura<0){
           roba = "roba d'esquiar";
        }
        else if(temperatura<10){
           roba = "roba de muntanya";
        }
        else if(temperatura<20){
           roba = "roba d'hivern";
        }
        else if(temperatura<30){
           roba = "roba d'estiu";
        }
        return roba;
    }    
}
```

  - **Diagrama:
  - 
![Selecció_192](https://user-images.githubusercontent.com/114875463/216549874-46711869-a2dc-4916-9f9c-3728159d30c7.png)

  - **Resultat CC: nombre de sentències condicionals + 1 = 4 + 1 = 5
  - **Resultat proves camins: 
      -1 --> -1, 0, 1
      -2 --> 9, 10, 11
      -3 --> 19, 20, 21
      -4 --> 29, 30, 31
     
4. Dibuixa el diagrama de flux representat per aquest codi, calcula la seva CC i crea una prova per a cada camí posible:

```
    public static Boolean llumsEncesos(int hora) {
        Boolean llums = false;
        if(hora <= 8 || hora >= 20){
            llums = true;
        }
        return llums;
    }
```
  - **Diagrama: 

![Selecció_193](https://user-images.githubusercontent.com/114875463/216552690-67eca9a0-fc97-4709-b48f-a0e954f06824.png)

  - **Resultat CC: nombre de sentències condicionals + 1 = 2
  - **Resultat proves camins:
      -1 --> 7, 8, 9
      -2 --> 19, 20, 21

5. Investiga sobre les proves de caixa negra:

  - Què són? Són proves de la funcionalitat d'un programa per a la qual s'utilitzen específics casos de prova.
  - Quina diferència principal tenen sobre les de caixa blanca? La principal diferència és que quant a les proves de caixa negra, 
    no es coneix el codi del programa.

