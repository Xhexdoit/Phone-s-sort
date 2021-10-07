
package ejerciciotelefono;


public class Ejerciciotelefono {

    public static void main(String[] args) {
        int [] telefonosArray =new int[9];
        
        telefonosArray[0]=913472133;
        telefonosArray[1]=945512762;
        telefonosArray[2]=935602201;
        telefonosArray[3]=913300211;
        telefonosArray[4]=923156651;
        telefonosArray[5]=912234112;
        telefonosArray[6]=945521256;
        telefonosArray[7]=912231236;
        telefonosArray[8]=911235661;
        
        for (int i = 0; i < telefonosArray.length-1; i++) { 
            for (int j = 0; j <telefonosArray.length-i-1; j++) { 
                if (telefonosArray[j]>telefonosArray[j+1]) { 
                    int temp=telefonosArray[j];
                    telefonosArray[j]=telefonosArray[j+1];
                    telefonosArray[j+1]=temp;   
                }    
            }   
        }
        System.out.println("Teléfonos ordenados:");
        System.out.println(" ");
        for (int i=0; i<telefonosArray.length; ++i){
        System.out.print(telefonosArray[i] + " ");
        }
        
    }
    
}
