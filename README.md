# Projeto-So
###### Hugo Rodrigo Gomes de Castro - 2707

## Exemplos de como executar:
  ##### $ ./vmm random 10 < anomaly.dat        
  Para executar o Random
	O random pega uma pagina aleatoria.
  
  ##### $ ./vmm fifo 10 < anomaly.dat          
  Para executar o FIFO
	O fifo pega a proxima pagina sendo ela a primeira que entrou.
  
  ##### $ ./vmm second_chance 10 < anomaly.dat          
  Para executar o second chance
	O second chance pega a proxima pagina se ela não foi referenciada recentemente se não manda ela para o final da fila.
  
  ##### $ ./vmm nru 10 < anomaly.dat          
  Para executar o nru
	O nru pega uma pagina aleatoria que não foi referencida recentemente.
  
  ##### $ ./vmm aging 10 < anomaly.dat          
  Para executar o aging
	o aging pega a pagina mais antiga da fila.
