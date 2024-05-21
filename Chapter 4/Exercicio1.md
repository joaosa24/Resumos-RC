__1.__

Os routers existentes são A, B e E pois são os únicos que possuem interface para mais do que uma rede IP.

__2.__
Existem 3 Sub-redes.

__SR1:__ Interfaces -> A,X1,...,Xn,E1 (n<20)

__SR2:__ Interfaces -> B1,C,D,E2 

__SR3:__ Interfaces -> B2,F

A rede de acesso que está sob gestão do ISP, é a relativa à interface 2 de A (A2)

Sabemos que os 24 bits do prefixo de rede são fixos, o esquema de subnetting tem recorrer obrigatoriamente ao restantes 8 bits. Desses 8, uma parte será para identificar de sub-redes e outra para a identificação de host interfaces (não nos devemos esquecer que existem endereços reservados).

Com isso podemos alocar 2 bits para identificar sub-redes (2² = 4 => max de sub-redes que podemos identificar com 2 bits) e 6 bits para identificar host interfaces (2⁶ -2 = max de HI que podemos observar)

Este modelo é apenas um exemplo pois se alocassemos 3 bits para sub-redes e 5 para host interfaces, também seria válido!

Máscara de rede original:

CIDR: /24; Decimal: 255.255.255.0

Máscara de rede para subnetting:

CIDR: /26; Decimal: 255.255.255.192