# imo
helloworld
public class Piramides {

    public static void main( String args [] ) {
    	int i = 0;
    	int j = 0;
    	int k = 0;
    	
    	// Piramide 1
    	
    	while (i <= 9) {
    		System.out.println(" ");
    		for (j=0; j<=i; j++){
    			System.out.print(j);	
    		}
    		i++;
    	}
    	
    	// Piramide 2
    	i=0;
    	while (i <= 9) {
    		System.out.println(" ");
    		for (j=0; j<=9-i; j++){
    			System.out.print(j);	
    		}
    		i++;
    	}
    
    
    	// Piramide 3
    	i=0;
    	while (i <= 9) {
    		System.out.println(" ");
    		for (k=0; k<=i; k++)
    			System.out.print(" ");
    		for (j=0; j<=9-i; j++){
    			System.out.print(j);	
    		}
    		i++;
    	}
    	
    	
    	
    	// Piramide 4
    	i=0;
    	while (i <= 9) {
    		System.out.println(" ");
    
    		for (k=0; k<=i/2; k++)
    			System.out.print(" ");
    		for (j=0; j<=9-i; j++){
    			System.out.print(j);	
    		}
    		i++;
    	}		
    }
    
    
}
