# Practica-Poo-M-todos
Practica de poo para metodos , sobrecarga, documentación y mas.
/*
Nombre: Diego Uriel Esquivel Vazquez
Materia: Programación Orientada a Objetos
Fecha: 08/09/2026
Objetivo: Conocer algunos comando de Ejecución y compilación en Java dentro de un Hola Mundo
Nombre del Programa: "Hola_Mundo.java"
*/


// paquete o paquetes

// bibliotecas o librerías

// variables globales o métodos polimórficos

// definición de la clase 
public class Hola_Mundo { 
	// Método principal - lo que se va a ejecutar
public static void main (String[] args) {
	msgTxtNum("Hola Mundo con Métodos");
	System.out.print("Diego Esquivel");
	System.out.println("Mi Primer Programa en POO");
	msgTxtNum(20);
}// Fin de Main

	// Métodos
	/**
	 * Método para ingresar valores textuales
	 * @param txt Variable de tipo textual
	 */
	public static void msgTxtNum(String txt){
	System.out.println(txt);
	}//  Fin de msgTxtNum

	/**
	 * Método para ingresar valores tipo Flotante
	 * @param txt Variables de tipo flotante
	 */
	public static void msgTxtNum(float txt){
	System.out.println(txt);
	}//  Fin de msgTxtNum

} // Fin de Case Hola_Mundo 

// métodos
