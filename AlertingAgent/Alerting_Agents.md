# Agentes de Alerta

Os agentes de alerta do Stallae são responsáveis por enviar alertas e notificações que foram enfileirados por meio de um ou mais canais (e-mail, SMS, chamada, chat, etc). Projetados para serem robustos e flexíveis, os agentes de alerta proporcionam redundância e escalabilidade, garantindo que os alertas sejam entregues de forma confiável e eficaz.

## Características

- **Suporte à Fila**: Os agentes de alerta suportam a fila de e-mails. E-mails são normalmente enviados imediatamente, mas também podem ser programados para envio em um horário específico. Se os e-mails falharem ao enviar, eles permanecem na fila até que três tentativas de reenvio falhem.

- **Canais de Contato**: Os agentes de alerta foram projetados de forma modular para permitir a adição de novos canais de contato no futuro. Inicialmente, suportamos alertas via SMTP com suporte a TLS 1.2.

- **Conectividade da Camada de Gerenciamento**: Para cada agente de alerta, uma configuração específica indica um servidor de camada de gerenciamento preferido e um servidor de backup para uso caso o servidor preferido não esteja disponível.

## Documentação da API

Para uma visão detalhada dos endpoints disponíveis e exemplos de como usá-los, consulte a documentação Swagger da API de Agentes de Alerta. A documentação Swagger fornece uma interface interativa que permite que você experimente a API de Agentes de Alerta e veja exemplos de respostas.

Você pode acessar a documentação Swagger aqui: [Swagger](swagger_files/alerting_agent_swagger.yaml)).

Essa documentação abrange todos os aspectos da API de Agentes de Alerta, incluindo detalhes de cada endpoint, os parâmetros que eles aceitam, e os códigos de resposta que eles retornam.