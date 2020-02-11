package zerojudge;

import java.util.Scanner;

public class main {
	private static int base;

	public static void main(String[] args) {
		int number;
		Scanner kb = new Scanner(System.in);
		
		while(kb.hasNextLine()) {
			base = kb.nextInt();
			
			while(kb.hasNext()) {
				number = kb.nextInt();
				if (number!=0) {
					if(isEnoughToShip(number)) {
						System.out.println(number/base);
					}else {
						System.out.println(base-number%base);
					}	
				}
			}
				
		}
	}
	
	
	public static boolean isEnoughToShip(int i){
		if (i%base==0) return true;
		else return false;		
	}

}
