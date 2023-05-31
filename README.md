# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 31/05/2023
Empresa: Abstergo Industries 
Responsável: Angelica Leite de Oliveira Santos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Angelica Leite de Oliveira Santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- EC2
- Processamento
- Estratégias e soluções implementadas
1) Análise de uso e otimização de tamanho de instância: A equipe de operações realizou uma análise detalhada do uso de suas instâncias EC2. Eles identificaram as instâncias que estavam subutilizadas e redimensionaram para tamanhos menores ou tipos de instância mais econômicos. Isso permitiu que eles economizassem dinheiro reduzindo a quantidade de instâncias em execução.
2) Implementação de grupos de Auto Scaling: A empresa configurou grupos de Auto Scaling para ajustar automaticamente o número de instâncias EC2 com base na carga de trabalho. Dessa forma, eles poderiam aumentar ou diminuir dinamicamente o número de instâncias com base na demanda atual, evitando o provisionamento excessivo e o desperdício de recursos.
3) Uso de instâncias reservadas e Savings Plans: A equipe avaliou seu padrão de uso e optou por comprar instâncias EC2 reservadas e Savings Plans. Isso permitiu que eles obtivessem descontos significativos em comparação com o uso sob demanda. Ao planejar suas necessidades a longo prazo, eles conseguiram reduzir substancialmente os custos operacionais.
4) Monitoramento de custos e otimização contínua: A empresa começou a utilizar ferramentas e serviços de monitoramento de custos fornecidos pela AWS, como o AWS Cost Explorer e o AWS Trusted Advisor. Isso deu à equipe uma visibilidade detalhada dos custos associados às instâncias EC2 e ajudou a identificar oportunidades adicionais de otimização.

Etapa 2: 
- Bucket
- Armazenamento
- Estratégias e soluções implementadas
1) Análise de dados: A empresa realizou uma análise detalhada dos dados armazenados no S3 para identificar os arquivos e objetos que não eram mais necessários. Eles identificaram dados antigos, duplicados ou não utilizados e removeram-os do bucket do S3. Isso reduziu significativamente o volume de armazenamento e os custos associados.
2) Uso de classes de armazenamento: A empresa revisou as classes de armazenamento disponíveis no S3 e avaliou o padrão de acesso aos dados. Eles migraram os dados menos acessados para classes de armazenamento de baixo custo, como o S3 Glacier Deep Archive. Isso permitiu que eles economizassem consideravelmente em comparação com o uso de classes de armazenamento de alto custo.
3) Configuração de políticas de ciclo de vida: A equipe implementou políticas de ciclo de vida no S3 para automatizar a movimentação de dados entre as classes de armazenamento com base em regras predefinidas. Isso ajudou a reduzir os custos, movendo automaticamente os dados para classes de armazenamento mais econômicas após determinado período de tempo ou quando não mais necessários.
4) Compactação e criptografia de dados: A empresa aplicou técnicas de compactação de dados para reduzir o tamanho dos arquivos armazenados no S3, o que resultou em economia de custos no armazenamento. Além disso, eles também implementaram criptografia para garantir a segurança dos dados armazenados.
5) Monitoramento e otimização contínua: A equipe implementou ferramentas de monitoramento, como o AWS Cost Explorer e o AWS Trusted Advisor, para rastrear os custos e identificar oportunidades adicionais de otimização. Eles revisaram regularmente as métricas e ajustaram suas estratégias de acordo para garantir a eficiência contínua.

Continue generating
Etapa 3: 
- DynamoDB
- Armazenamento
- Estratégias e soluções implementadas
1) Análise e otimização do modelo de dados: A empresa realizou uma análise detalhada do modelo de dados existente e identificou áreas de ineficiência. Eles refatoraram o modelo de dados para melhorar a eficiência das consultas e reduzir o número de operações necessárias. Isso resultou em menos consumo de capacidade do DynamoDB e, consequentemente, em redução de custos.
2) Uso adequado de índices: A equipe revisou os índices existentes e identificou aqueles que não estavam sendo utilizados ou que poderiam ser substituídos por índices mais eficientes. Eles otimizaram o uso de índices para minimizar as operações de leitura/gravação desnecessárias, reduzindo assim os custos associados.
3) Utilização de capacidade on-demand e provisionada: A empresa avaliou o padrão de tráfego e demanda do seu aplicativo e identificou os momentos de pico e de baixa demanda. Para os períodos de baixa demanda, eles utilizaram a capacidade on-demand do DynamoDB, que permite pagar apenas pelas operações consumidas. Para os períodos de pico, eles utilizaram a capacidade provisionada, dimensionando-a adequadamente para evitar custos excessivos.
4) Monitoramento e ajuste contínuo: A equipe implementou métricas e alarmes no DynamoDB para monitorar o consumo de capacidade e a utilização do serviço. Isso permitiu que eles identificassem gargalos de desempenho e ajustassem a capacidade provisionada conforme necessário, evitando desperdício de recursos e reduzindo custos.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries  tem como esperado redução de custo das ferramentas levantadas, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Angelica Leite de Oliveira Santos
