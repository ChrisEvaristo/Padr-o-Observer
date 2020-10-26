# Padr-o-Observer

Classificação -> Observer abstrai  a relação  dos objetos definindo  como Observer e Subject.



Intenção -> Permitir  que  um objeto  publique mudanças de estado.Também  permite  que outros objetos se inscrevam  para receber notificações sobre  esta mudanças.



Motivation ->  Proporciona baixo acoplamento  entre a  classe  que notifica sobre  mudancas e outras  classes que recebem  esta  notificação.


Objetivo -> Receber  notificação  sobre mudancas  de estado  em outras objetos quando  está   mudança for  relevante.



Applicability ->  Diminuir  acoplamento  entre classe  dependentes através do  encapsulamento . Quando uma mudança a um  objeto requer  outros  objetos  devem mudar ou quando um objetos deve  ser capz  de avisar  outos  sem fazer suposições sobre  quem são  os objetos .


Participantes
  Subject ->  é Classe que possui a informação  o estado  que se  deseja observar,
  Observer -> Interface  que define  os métodos de notificação  de interesse dos observadores;
  Concrete ObserverA,concreteB, Classes concretas que observam  a classe Subject.

