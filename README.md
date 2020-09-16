# Docker
Minha experiencia no docker começa antes da empresa quando tentei usá-lo e não consegui executar ele no windows.
Já na empresa com o linux a instalação e uso se mostrou bem tranquila e hoje percebo que ele facilita muito as coisas.

O docker faz a utilização de containers linux para criação de ambientes isolados.

Pontos Positivos

1-Manutenção , pois fica muito mais facil controlar e alterar versões dos recursos utilizados do sistema.

2-Ajuda na escalabilidade do sistema, em sistemas grandes fica difícil ate entender quais recursos que tem que ativar para funcionar o sistema e com o docker isso não é um problema.

3-Fica mais fácil de trabalhar em conjunto e compartilhar código já que vamos conseguir unificar as versões trabalhadas.



Pontos negativos do docker

Por especificar a versão do ubuntu utilizada vai também carregar uas falhas de segurança

Dificuldade em instalacao e utilizacao no windows. 

Para atualizar e preciso derrubar o docker 

Alternativas

Kubernetes - E um orquestrador de containers e surgiu para suprir um dos problemas do docker que e quando atualizar o sistema e preciso derrubar o sistema.
Seu concorrente direto seria o docker swarm, que e a solucao do docker para esse problema.Acho interessante depois até analisar tanto o kubernetes, quanto o docker swarm pra ver se é interessante utilizar no proximo sistema já que quando se tem um deploy o sistema fica inutilizado pelo tempo do deploy.

Maquina virtual- também e uma forma de virtualização mas que gera um ambiente isolado completo com disco, processador, memoria etc.
Comparando com o docker cado um possui usos recomendados. O uso do Docker e dos containers podem ser mais interessantes exige muito menos memória e espaço em disco do que as VMs. No entanto, existem casos em que todas as funções do sistema operacional é requerida, como a interface gráfica, inexistente nos containers.

Falta realizar de tarefa- 

Executar scripts igual no oxe quando utiliza por exemplo alguns scripts para iniciar os serviços.