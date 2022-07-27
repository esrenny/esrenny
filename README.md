public class main {
    public static void main(String[] args) {
        int a=25;
        int b=12;
        int c=9;

        int suma=a+b+c;
        System.out.println("La suma es "+ suma);


        Coche miCoche = new Coche();
        miCoche.SumarPuerta();
        System.out.println(miCoche.puertas);
    }
}
    class Coche {
        public int puertas = 4;

        public void SumarPuerta() {
            this.puertas++;
        }
    }

<!---
esrenny/esrenny is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
