package com.company;

public class Main {

    public static void main(String[] args) {
        Coche miCoche = new Coche();
        miCoche.QuitarPuerta();
        miCoche.QuitarPuerta();
        miCoche.PonerPuerta();
        System.out.println(miCoche.puerta);



        int resultado = 0;
        resultado = suma( 420, 69, 666);
        System.out.println(resultado);
    }


    public static int suma (int a, int b, int c){
        return a + b + c;

    }

}
class Coche  {
    public int puerta = 0;

    public void PonerPuerta() {
        this.puerta++;
    }
    public void QuitarPuerta() {
        this.puerta--;
    }
}
