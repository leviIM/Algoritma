# Algoritma
Kulina Test
//1 Bilangan Prima memakai java.

    import java.util.Scanner;
    public class Test{
    public static void main(String[]args){

		Scanner scan = new Scanner(System.in);
		  System.out.println("Input angka : ");

		  int angka = scan.nextInt();

		  int temp;
		  boolean prima = true;

		  for(int i = 2; i <= angka / 2; i++){

		   temp = angka % pembagi;

		   if(temp == 0){

		    prima = false;
		    break;

		   }

		  }
		  
		  if(prima && ((angka > 0)&&(angka != 1)))
		   System.out.println(angka + " adalah bilangan prima");
		  else
		   System.out.println(angka + " bukanlah bilangan prima");
		   
		}
	}
  
  //2 Bilangan Fibonachi memakai java.

        import java.util.Scanner;
        public class Test2{
        public static void main(String[]args){

        Scanner scan = new Scanner(System.in);
        System.out.print(" Input Angka : ");
        int angka = scan.nextInt();
        long fib[] = new long[angka];

        fib[0] = 0;
        fib[1] = 1;

        for(int i = 2; i < angka; i++) {
            fib[i] = fib[i-1] + fib[i-2];
        }

        for (int i = 0; i < angka; i++) {
            System.out.print(fib[i] +  " ");
        }

		}
	}
  
