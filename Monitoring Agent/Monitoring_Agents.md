# Agentes de Monitoramento

Os agentes de monitoramento Stallae são distribuídos em várias regiões para testar a acessibilidade dos serviços a partir de diferentes localidades físicas. Eles são agrupados em regiões, onde cada região representa uma localidade física diferente. Diversos agentes operam a partir dessas regiões para fins de redundância, desempenho e escalabilidade.

Inicialmente, os agentes suportam três tipos diferentes de testes, mas foram projetados de forma modular para permitir a adição fácil de outros tipos de testes no futuro. Os tipos de testes iniciais incluem disponibilidade de site, ping e porta.

## Características

- **Suporte à Região**: Cada agente de monitoramento é configurado para uma região específica. Em cada região, existe um ou mais agentes de monitoramento, dividindo a carga de trabalho entre si para eficiência e escalabilidade.

- **Tipos de Teste**: Os agentes de monitoramento foram projetados para facilitar a adição de novos tipos de testes no futuro. Os tipos de testes iniciais incluem:

  - **Disponibilidade de Site**: Verifica se uma URL específica retorna uma mensagem "200 OK". Qualquer outra mensagem ou erro é considerado como "indisponível".
  
  - **Ping**: Verifica se um IP de destino ou uma URL resolvida para um IP pode ser alcançado com ping/ICMP.
  
  - **Porta**: Verifica se uma conexão pode ser estabelecida em uma porta específica.

- **Conectividade da Camada de Gerenciamento**: Uma configuração estará disponível para cada monitor com um servidor de camada de gerenciamento preferido e um servidor de backup caso o preferido não esteja disponível. O servidor preferido deve ser usado novamente se voltar a estar disponível.

## Documentação da API

Para uma visão detalhada dos endpoints disponíveis e exemplos de como usá-los, consulte a documentação Swagger da API de Agentes de Monitoramento. A documentação Swagger fornece uma interface interativa que permite que você experimente a API de Agentes de Monitoramento e veja exemplos de respostas.

Você pode acessar a documentação Swagger aqui: [swagger_files/monitoring_agent_swagger.yaml](swagger_files/monitoring_agent_swagger.yaml).

Essa documentação abrange todos os aspectos da API de Agentes de Monitoramento, incluindo detalhes de cada endpoint, os parâmetros que eles aceitam, e os códigos de resposta que eles retornam.