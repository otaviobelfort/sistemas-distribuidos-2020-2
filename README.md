# Síntese - Tipos de Sistemas Distribuídos e Middleware

## Tipos de sistemas distribuídos
 Sistema distribuído consiste em um sistema que possui componentes localizados em computadores interligados em rede e que se comunicam e coordenam suas ações através da troca de mensagens entre os componentes. É comum pensarmos em componentes como sendo apenas servidores e máquinas conectadas em rede, mas quando falamos de componentes podem ser componentes de hardware (servidores) ou de software ( aplicações e serviços ).

 Falaremos dos seguintes tipos de sistemas distribuidos:

* Computação em Cluster 
* Computação em Grade
* Computação em Nuvem
* Sistema de Informação Distribuidos
* Sistemas distribuidos Pervasivos

### Sistemas de computação em cluster
Construir  supercomputadores não é uma tarefa fácil e muito menos barata. No entando, com o passar do tempo a relação custo beneficio deu abertura para se investir em tais computadores, assim como especialmente sistema de computação em cluster. A sua aplicação, se dá pela forte utilização de progamação paralela, que permite um unico programa seja executado simultaneamnete de várias máquinas.

### Computação em Grade
Um aspecto caracteristico da computação em grade é a sua heterogeneidade, que não estabele pré-requisitos quanto a hardware, redes, sistemas operacionais, políticas de segurança, etc. Dessa forma, esse sistema atua agrega a utilização de recursos de diferentes setores para trabalharem em conjunto no ambito de uma organozação virtual. Servidores de computação, supercomputadores incluindo por vezes cluster, banco de dados e equipamentos em redes, são alguns exemplos desses recursos.

Dada a importancia desses recursos dos mais variados domínios administrativos, muitos softwares são elaborados com o intuito de dá acesso aos mesmos. Em decorrencia disso, o atenção geralmente é direcionada para os aspectos de aquitetura.

Foster propoe uma arquitetura, estruturada em quatro camadas: camada coletiva, camada de conetividade, camada de recurso e camada de base.

* A *camada base* atua no provimento de interfaces desenvolvidas afim de proporcionar o compartilhamento de recursos.

* A *camada de conectividade* por meio de protocolos de comunicação irá trabalhar para que as transações da grade tenha acesso a múltiplos recursos. Alguns desses protocolos são usados especificamente para autenticação de usuarios e recursos atuando como uma camada de segurançã.

* A *camada de recursos* interage de maneira direta com as duas camadas ja descritas, faz uso das funções na camada de conectividade e das interfaces na camada base. Dessa forma, ela adminiostra um unico recurso por vez.

* A *camada coletiva* é responsavel pela manipulação do acesso a múltiplos recursos e comumente propoe serviços para descoberta de recursos, alocação e escalonamento de multiplas tarefas entre outros.

### Computação em Nuvem
Caracterizada por organizações abertas, a computação em nuvem tem crescido bastante e ocupado o lugar cada vez mais da computação em grade. Ela permite asssociação de diferente agentes aos seus recursos, como: maquina virtual, armazenamento ou aplicações; a exemplos temos a Google que provem esses tipos de recursos ou serviços terceirizados. Sendo assim pessoas ou empresas já não lidam de maneira direta, mas terceirizam esses recursos.

### Sistema de informação distribuidos
Sistemas de bancos é um exemplo de implementações desse sistemas, em que é necessario a integração de diversas aplicações e a interoperabilidade é fortemente requerida.
Duas implementaçõe importantes desses  sistemas acontecem em sistemas de processamento de transações e integração de aplicações empresariais.

### Sistemas distribuidos Pervasivos
	
A maioria dos sistemas distribuidos possuem uma boa estabilidade em suas conexões, diferente dos sistemas distrinuidos pervasivos, em que uma certa instabilidade é esperada. Tais sistemas gerelmente são pequenos, alimentados por baterias em decorrencia de sua mobilidade e por terem conexão sem fio.

Esses sistemas são caracterizados por sua autonomia, a medida que são devidamente configurados por seus proprietarios, assim eles atuam tanto provendo quanto acessando informações. Na área de internet das coisas é um ambiente em que se tem explorado com abrangencias as possibilidades desses sistemas.
Outros exemplos de aplicações de sistemas distribuidos pervasisvos: *sistemas domesticos 	sistemas eletronicos de tratamento de saúde e redes de sensores.*

# Exemplos de Middleware




Middleware | Função | Linguagens
--------- | ------ | ----------------------------
Apache spark     | |
JBoss    |    |
Batata    |   |
Macarrão  | |






# sistemas-distribuidos-2020-2
