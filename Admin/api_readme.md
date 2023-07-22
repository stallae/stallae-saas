# API do Admin

A API do administrador Stallae oferece um poderoso conjunto de endpoints para gerenciar e configurar o ambiente Stallae. Com a API do administrador, você pode gerenciar usuários, monitores, agentes de monitoramento e alerta, regiões, modelos de mensagens, e ajustar as configurações globais do sistema.

## Características

- **Segurança avançada**: Autenticação multifatorial, bloqueio temporário de conta para proteção contra ataques de força bruta, lista de IPs para permitir acesso apenas através de IPs específicos, registro de acesso e alterações em qualquer objeto.
- **Gerenciamento de Modelos de Mensagens**: Crie e gerencie modelos de mensagens para diferentes tipos de notificações.
- **Gerenciamento de Usuários**: Adicione, edite, exclua, habilite e desabilite usuários. Gerencie as chaves de API do usuário, obtenha os monitores do usuário, limite o número máximo de monitores por usuário e limite o número máximo de contatos por usuário.
- **Gerenciamento de Monitores**: Adicione, edite, exclua, visualize, pause e inicie monitores de usuários.
- **Gerenciamento de Regiões**: Adicione, edite, exclua e visualize regiões.
- **Gerenciamento de Agentes de Monitoramento**: Adicione, edite, exclua, visualize, habilite e desabilite agentes de monitoramento. Atribua agentes de monitoramento a regiões.
- **Gerenciamento de Agentes de Alerta**: Adicione, edite, exclua, visualize, habilite e desabilite agentes de alerta.
- **Configurações Globais**: Defina o número máximo padrão de monitores por usuário, o número máximo padrão de contatos por usuário e o intervalo de tentativa do agente de alerta.

## Documentação da API

Para uma visão detalhada dos endpoints disponíveis e exemplos de como usá-los, consulte a documentação Swagger da API do Admin. A documentação Swagger fornece uma interface interativa que permite que você experimente a API do Admin e veja exemplos de respostas.

Você pode acessar a documentação Swagger aqui: [swagger_files/admin_swagger.yaml](swagger_files/admin_swagger.yaml).

Essa documentação abrange todos os aspectos da API do Admin, incluindo detalhes de cada endpoint, os parâmetros que eles aceitam, e os códigos de resposta que eles retornam.