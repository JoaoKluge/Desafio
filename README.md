# Desafio_2
package Desafio_2;

public class Desafio_2 {
	
	public static void main(String[] args) {
			
			Integer[] horaChegada = {-1,-2,0,0,3,4,5};
					
			int x=3;
			int horario = 0;		
			for(int i = 0; i <horaChegada.length; i++ ) {
							
				if(horaChegada[i]<= 0) {
					horario++;
											
				}
			}
			if( horario >= x ) {
				
				System.out.println("Aula NORMAL");
				
			}else {
				System.out.println("Aula CANCELADA");
		}
	}
}
