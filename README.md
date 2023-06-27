# aws-practitioner

### Beneficios da cloud

 - Custos variáveis, pagando somente pelo que usar.
 - Sem necessidade de manter uma infraestrutura local.
 - Alcance global.
 - Escalável.


### Tipos de nuvem

- 100% nuvem
- Local/Privada
- Hibrida


### EC2 Elastic Compute Cloud

Oferece capacidade de computação escalável, com ele é possível executar servidores virtuais.

**Tipos de instancias EC2**

- Instâncias de uso geral - Equilibra recursos de computação, memória e rede.
- Instâncias otimizadas para computação - Ideais para aplicações que necessitam de alto desempenho de processadores.
- Instâncias otimizadas para memória - Ideais para cargas de trabalho que processam grandes quantidades de dados na memória.
- Instâncias de computação acelerada - Utilizam aceleradores de hardware/processadores para aumentar a eficiência.
- Instâncias otimizadas para armazenamento - Ideais para cargas de trabalho que necessitam de alto acesso sequencial de leitura/gravação a grandes conjuntos de dados.

**Definicoes de preco**

- Sob demanda.
- Saving Plans - A AWS oferece planos de diversos servicos para quantidades mínimas que serão sempre utilizadas por períodos de 1 a 3 anos. Caso seja utilizado um volume maior do que o contratado, o preço excedente será cobrado de acordo com a modalidade sob demanda.
- Instâncias reservadas - Praticamente a mesma coisa que o Saving Plans, porém é menos flexível. É necessário especificar a quantidade exata e o tipo de instância.
- Spot - e um "leilao" de instancias ociosas da AWS. Descontos pode4m chegar a 90%, ideal para cargas de trabalho que poedm ser interrompidas.
- Hosts dedicados - são servidores físicos com capacidade de instância do Amazon EC2 totalmente dedicada ao uso do cliente.

**Amazon EC2 Auto Scaling**

Provisiona ou remove automaticamente instâncias EC2 de acordo com a demanda da aplicação.

**Elastic Load Balancer**

Distribui o tráfego de entrada entre as instâncias EC2 para evitar a sobrecarga de uma única instância.

### Amazon Simple Notification Service SNS

Serviço de publicação/assinatura. Utilizando tópicos do Amazon SNS, um editor publica mensagens para assinantes. Os assinantes podem ser servidores web, endereços de e-mail, funções do AWS Lambda ou diversas outras opções disponíveis.

### Amazon Simple Queue Service SNS

Serviço de fila. É utilizado para enviar, armazenar e receber mensagens entre componentes de software, garantindo que as mensagens sejam processadas de forma confiável e sem o risco de perda.

### AWS Lambda

O serviço que permite fazer o upload do código sem a necessidade de provisionar ou gerenciar servidores e configurar um gatilho para executá-lo, pagando somente pelo tempo de computação utilizado

### Amazon Elastic Container Service ECS

Serviço de gerenciamento de contêineres altamente escalável e de alto desempenho. É compatível com o Docker.


