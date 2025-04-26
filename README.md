# redesaulas
Dados do exercício de rota estática.
192.168.010.000 
255.255.255.192   /26
Teremos 4 redes
	Rede 1 - 192.168.010.000 
		válidos 1 até 62
		Broadcast 192.168.010.063
	Rede 2 - 192.168.010.064 
		válidos 65 até 126
		Broadcast 192.168.010.127
	Rede 3 - 192.168.010.128 
		válidos 129 até 190
		Broadcast 192.168.010.191
	Rede 4 - 192.168.010.192 
		válidos 193 até 254
		Broadcast 192.168.010.255
Para toda conexão ponto a ponto as boas práticas será usar um /30

010.010.010.000 /30
255.255.255.252
		128+64+32+16+8+4 = 252
10.10.10.0
	1 até 2
10.10.10.4
	5 até 6
10.10.10.8
	9 até 10
10.10.10.12
....
