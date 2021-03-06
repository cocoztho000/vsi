---



copyright:
  years: 2017
lastupdated: "2017-11-15"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# Sobre servidores virtuais

{{site.data.keyword.BluVirtServers}} são servidores virtuais escaláveis que são comprados com núcleos dedicados e alocações de memória. Eles são uma boa opção se você estiver procurando por recursos de cálculo, que podem ser incluídos em minutos, com acesso a recursos como modelos de imagem. O hypervisor é totalmente gerenciado pelo {{site.data.keyword.BluSoftlayer_full}} e você pode executar tarefas de configuração e gerenciamento usando o {{site.data.keyword.slportal_full}} e o {{site.data.keyword.slapi_short}}. Os servidores virtuais são implementados nas mesmas VLANs que os servidores físicos, permitindo difundir cargas de trabalho entre servidores virtuais e servidores bare metal, enquanto mantém a interoperabilidade. Os servidores virtuais são totalmente customizáveis ao serem pedidos, com opções para aumentar a capacidade conforme seu cálculo precisa crescer.
{:shortdesc}

Ao criar um servidor virtual, é possível escolher entre faturamento por hora e mensal. Também é possível escolher entre um ambiente público (ocupação variada) ou um ambiente dedicado (ocupação única). Em seguida, é possível escolher discos locais de alto desempenho ou armazenamento SAN corporativo para seu servidor virtual.

## Recursos-chave

As informações a seguir listam os recursos-chave que são incluídos com servidores virtuais.
### Integração contínua

Os {{site.data.keyword.BluVirtServers_short}} são implementados no mesmo pod e rede que os servidores bare metal e dispositivos de rede. Isso fornece a flexibilidade para usar a melhor tecnologia para cada carga de trabalho. Múltiplos servidores virtuais são comumente implementados atrás de um balanceador de carga para entregar o tráfego da web. Esses servidores podem ter acesso direto à rede privada de camada 2 para servidores de banco de dados bare metal e outras cargas de trabalho mais intensivas.
### Totalmente customizável

É possível construir sob medida qualquer servidor virtual com várias opções. Não há requisitos predefinidos de pacote, portanto é possível ajustar cada servidor à carga de trabalho que ele suporta.

### Provisionamento rápido

Os servidores virtuais são provisionados no mínimo 5 minutos, fornecendo a você o tempo mínimo de espera entre ordem e fornecimento.
### Gerenciamento remoto

Como todos os nossos serviços e soluções, você tem a capacidade de gerenciar seus servidores virtuais remotamente. Visualize e gerencie todos os detalhes do dispositivo usando o {{site.data.keyword.slportal}} ou {{site.data.keyword.slapi_short}}. Também é possível interagir com o servidor por meio das funções KVM fornecidas ou efetuar login no servidor com controle administrativo integral por meio das interfaces públicas ou privadas.
### Facilmente escalável

Após seu servidor virtual ser provisionado, é possível escalar fácil e rapidamente sua instância para cima ou para baixo e incluir ou remover instâncias extras sob demanda. É possível tomar um modelo de imagem do servidor após ele ser configurado e ajustado e, em seguida, criar mais servidores virtuais com base nessa imagem original.
