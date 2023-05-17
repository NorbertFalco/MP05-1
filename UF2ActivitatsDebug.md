# Activitats:

## Activitats debug:

### Factorial:

El factorial d'un nombre és el resultat de multiplicar el número per ell mateix -1 tantes vegades com  siguin necessàries fins arrivar a 1.

Per exemple el factorial de 5 és:

5 * 4 * 3 * 2 * 1

![image](https://user-images.githubusercontent.com/110727546/206031980-55e59610-42bb-4cc6-9b5f-039d7f67e185.png)

Fes una funció factorial que rebi un número com paràmetre i retorni el seu factorial.

Es demana:

- Codi del programa.

```

import java.util.Scanner;

public class Factorial {
    public static int calcularFactorial(int num) {
        int resultat;
        if (num<=1){
            resultat = 1;
        }
        else{
            resultat =  num*calcularFactorial(num-1);
        }
        return resultat;
    }

    public static void main(String[] args) {
        Scanner ent = new Scanner(System.in);
        int numero = ent.nextInt();

        int resultat = calcularFactorial(numero);
        System.out.println("El factorial de " + numero + " és: " + resultat);
    }
}

```

- Captura de pantalla amb un punt d'interrupció que deixi veure totes les crides a la funció (agafeu un valor menor a 10).

![Selecció_1491](https://github.com/NorbertFalco/MP05-1/assets/114875463/5ebc2ead-9eba-46c0-82ac-8711ded76647)


### Taula de multiplicar:

Fes un programa que crea una matriu de números del 1 al 10.
Aquest programa rep per argument d'entrada un número sencer i retorna per terminal la taula de multiplicar d'aquest número multiplicant el argument per cada valor de la matriu.

Es demana:

- Codi del programa.
```
public class TaulaMultiplicar {
    public static void main(String[] args) {
        int[] numbers = new int[10];
        for (int i = 0; i < 10; i++) {
            numbers[i] = i + 1;
        }

        int n = Integer.parseInt(args[0]);
        generateMultiplicationTable(n);
    }

    public static void generateMultiplicationTable(int n) {
        for (int i = 1; i <= 10; i++) {
            System.out.println(n + " x " + i + " = " + (n * i));
        }
    }
}
```


- Captura de pantalla de com li passeu a IntelliJ com argument del programa un número. (Mireu exemple findAverage).

![Selecció_1492](https://github.com/NorbertFalco/MP05-1/assets/114875463/bdd7b871-6d47-4144-82cd-b58d64b81cd3)



- Captura de com feu un punt d'interrupció al bucle de creació de la matriu i mostreu els valors de la matriu.

![Selecció_1493](https://github.com/NorbertFalco/MP05-1/assets/114875463/4f8cd0ed-8911-4142-bd8a-b841c3ced67c)




- Captura de punt d'interrupció al bucle de multiplicació i com modifiqueu a ma els valors de la matriu de números per a que l'execució retorni el número 1 10 vegades quan l'argument d'entrada era 1.


![Menú_011](https://github.com/NorbertFalco/MP05-1/assets/114875463/3ea661ab-c601-41d6-aa89-0d5706fd7e7f)



![Selecció_1494](https://github.com/NorbertFalco/MP05-1/assets/114875463/2900b0b9-b1ab-478b-8b91-917e28be95c7)






