# Bomba
Temporizador Bomba

	
	try {
		for (int i = minutos; i >=0; i--) {
			for (int j = 59; j >=0; j--) { // colocar no lugar do 60 segundos crias um sysout. com variavel segundo
				System.out.println(i + ":"+ j);
				
			}
		// passar ele para segundos=59;
			Thread.sleep(1000);
			
		}
		
	} catch (Exception e) {
		
		
		sc.close();
		
	}
	System.out.println("BUUUUUUM");
	}

}
