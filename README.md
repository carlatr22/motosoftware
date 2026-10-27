# motosoftware
Mi primer software.

## 1. Fundamentos del sistema
La empresa se llama MotoSoftware y se dedica al desarrollo de software para que los talleres y tiendas de motos tengan una facilitación.
Vamos a crear un programa llamado MotoGestión, cuyo destino es  a talleres de motos. El programa servirá para gestionar la información de los clientes, las motos y las reparaciones que se hacen.
Será un software de aplicación, ya que su uso será realizar una tarea concreta para el usuario que desea obtener nuestro software.

## 2. Análisis y especificación de requisitiso
-Requisitos funcionales
Registrar clientes.
Registrar motos.
Registrar las reparaciones de cada moto.
Consultar las reparaciones realizadas.
Modificar los datos de clientes y motos.
Eliminar datos.
Buscar una moto o un cliente.
-Requisitos no funcionales
El programa debe ser fácil de utilizar.
Debe funcionar a la perfección.
Debe ser rápido.
Los datos deben estar protegidos para que no haya un traspaso de identidad y sea una app segura.


## 3. Diseño
El programa MotoGestión servirá para gestionar la información de los clientes, las motos y las reparaciones de los talleres de motos.

## 4. Implementación
Public class Hola{
    public static void main(String[ ] args) { 
        System.out.println(“Hola Mundo”);
         if(True){
           System.out.println("Condición verdadera");
          }else{
            System.out.println("Condición falsa");
         }
    }
}

public class Area{
      public static void main(String[ ] args) { 
        int radio = 5;
     final double PI = 3.14159;
        double area = pi*(r*r);
        System.out.println("el area es; " +area);
   }
}

public class Operacionesmatematicas {
  public static int sumarNumeros(int numeroUno, int numeroDos){
       return numeroUno + numeroDos;
  }
  public static int restar (int a, int b){
    return a - b;
  }
   public static int multiplicar(int num1 , int num2){  
     return num1*num2;
   }
  public static int divisiondeenteros(int dividendo, int divisor){
     return dividendo/divisor;
   }
 public static void main(String[] args){
      System.out.println( “sumarNumeros (3,4));
      System.out.println(resta r(5,2));
      System.out.println(multiplicar (2,6));
      System.out.println(divisiondeenteros (8,2));
  }
}

// Esta clase hace operaciones básicas
public class Calculadora {
   // Este método suma dos números enteros
     public int sumar(int x, int y){
       return x+y;
      }
    // Este método resta dos números enteros
     public int restar(int x, int y){
     return x-y;
     }
     // Este método multiplica dos números enteros
      public int multiplicar(int x, int y){
        return x*y;
      }
      // Este método divide dos números enteros
        public int dividir(int x, int y){
          return x/y;
       }
     //Para probar la calculadora
      public static void main(String[] args){
       Calculadora c=new Calculadora();
      System.out.println("resultado:"+c.sumar(5,3));
     }
}
//clase de alumno
public class Alumno{
    private String nombre;
    private int edad; 
    private double notaFinal;
public alumno(String n,int e,double nf){ 
    nombre=n;
    edad=e; 
    notafinal=nf; 
}
public void Mostrardatos(){ 
   System.out.println("Alumno: "+nombre + “Edad:" +edad + Nota Final:" +notafinal); 
}
public boolean aprobado(){ 
    if(notafinal>=5.0){ 
       return true; 
     }else{ 
       return false; 
    } 
}
public void mensajefinal(){ 
   if(aprobado) { 
     System.out.println("felicidades " + nombre + " aprobaste!"); 
    }else{ 
      System.out.println("Lo siento " + nombre +" no aprobaste"); 
    }
}
public class Curso{
    private String nombre_curso;
    private alumno[] lista;
public curso(String n, alumno[] l){ 
nombre_curso=n; 
lista=l; 
}
 public void mostrarTodo(){ 
     System.out.println("curso: "+nombre_curso); 
      for(alumno a:lista){ 
      a.mostrardatos(); 
      a.mensajeFinal(); 
  } 
public static void main(String[] args){
   alumno a1=new alumno("ana",18,6.5);
   alumno a2=new alumno("Pedro",19,4.3);
   alumno a3=new alumno("Lucia",17,8.7);
   alumno lista=(a1,a2,a3);
   curso c1=new curso("Programación" + lista);
   c1.mostrarTodo();
 }
}


## 5. Plan de pruebas del sistema
Añade aquí lo que hicimos para diseñar las pruebas

### 5.1. Pruebas de aceptación
Nada por aquí 

## 7. Los diccionarios de datos

No hagas nada por aquí
