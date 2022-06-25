# CrearClaseCoche
Se crea una clase coche y se le establece un número de puertas, y se le añade 1. Se muestra el resultado.
-----------
public class Main {

    public static void main(String[] args) {
    Coche Micoche = new Coche();
    Micoche.AñadirPuerta();
    System.out.println(Micoche.puertas);
    }
static class Coche {
        public int puertas =4;
        public void AñadirPuerta() {
            this.puertas++;
        }
}
}
