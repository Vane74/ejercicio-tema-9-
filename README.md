# ejercicio-tema-9-
ejercicio herencia


class Persona{

   private int edad;
   
   private String nombre;
   
   private String telefono;
   
   
   public int getEdad(){
   
       return this.edad;
       
}


public int setEdad(int edad){

    this.edad = edad;
    
}

public String getNombre(){

    return this.nombre;

}

public String setNombre(String nombre){

         this.nombre = nombre;
     
}

public String getTelefono(){

         return this.telefono;
        
}

public String setTelefono(String telefono){

         this.telefono = telefono;
        
    }
    
}



class Cliente extends Persona{

         private double credito;
       
       
       
public double getCredito(){

         return this.credito;
       
}

public double setCredito( double credito){

        this.credito = credito;
        
    }
 
 }
 
 
 class Main{
 
 
public static void main(String[] args){
          
          Cliente cliente = new Cliente();
          
          cliente.setEdad(35);
          
          cliente.setNombre("Juan");
          
          cliente.setTelefono("7226548990");
          
          cliente.setCredito(1,400.00);
          
          System.out.println(cliente.getEdad());
          
          System.out.println(cliente.getNombre));
          
          System.out.println(cliente.getTelefono));
          
          System.out.println(cliente.getCredito));
          
   }
   
   
}

class Trabajador extends Persona{

         private double salario;
         
         
 public double getSalario(){
 
         return this.salario;
         
}

public double setSalario(double salario){

       this.salario = salario;
       
}



       

