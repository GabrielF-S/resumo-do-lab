# Desafio de Projeto Microsoft Azure 

## Resumo do conteúo aprendido 

Neste laboratório, foi explicado detalhadamente o conceito de SLA (Service Level Agreement) dos serviços e como funciona
o tempo de inatividade aceitável de acordo com cada nível de SLA. Quanto mais dígitos após a vírgula, menor será o tempo
de inatividade. Por exemplo, um SLA de 99,999% é superior ao de 99,9%, consequentemente mais robusto e confiável.

Por isso, é essencial considerar a importância do tempo de inoperância do sistema ao planejar a arquitetura ideal para um 
cliente ou empregador, pois cada serviço possui seu próprio SLA.Ao configurar a instanciação de máquinas virtuais, há opções relacionadas à disponibilidade e Zonas de Disponibilidade.

Podemos clicar nos ícones para obter mais detalhes sobre os campos ou acessar o botão "Saiba mais", que direciona para a 
documentação do serviço. Essa documentação esclarece as opções correspondentes a cada SLA. Também foi abordado o conceito 
de redundância, demonstrando que, ao instanciarmos o serviço em mais de uma zona de disponibilidade (seja por redundância
geográfica ou local), o nível de indisponibilidade diminui. Isso ocorre porque o serviço opera em mais de um local, 
reduzindo as chances de ficar inoperante.