# Programa-01

package getuserinfo;

/**
 *
 * @author AudiGS
 */
import java.util.Scanner;

public class GetUserInfo{
    
    public static void main(String[] args){
        String name;
        int age;
        
        Scanner inputDevice = new Scanner(System.in);

        System.out.print("Escriba su Nombre >> ");
        name = inputDevice.nextLine();

        System.out.print("Escriba su Edad >> ");
        age = inputDevice.nextInt();

        System.out.println("Tu Nombre es " + name +" Y tienes " + age + " años.");
    }
}
