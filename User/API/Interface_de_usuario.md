# Usuário Stallae

A interface do usuário Stallae é voltada para o usuário e é utilizada principalmente através de uma interface de front-end para realizar tarefas como registro de usuários, gerenciamento de contatos, administração de monitores e visualização de dados históricos.

### Gerenciamento de Contatos

Os usuários devem ter à disposição as seguintes funcionalidades para gerenciar contatos para alertas:

- **Adicionar Contato**: Capacidade para adicionar novos contatos que receberão alertas.

- **Modificar Contato**: Capacidade para alterar as informações de um contato existente.

- **Excluir Contato**: Capacidade para remover um contato.

- **Pausar/Iniciar Contato**: Capacidade para suspender ou iniciar alertas para um contato específico.

As operações acima devem ser coordenadas com os vários canais de comunicação suportados pelo agente de alerta. Dependendo do canal, poderão ser necessários tipos diferentes de configurações.

Espera-se que a interface do usuário para o gerenciamento de contatos seja intuitiva e fácil de usar, facilitando aos usuários o gerenciamento eficiente de seus contatos.

### Gerenciamento de Monitores

Para o gerenciamento de monitores, o usuário deve ter à disposição as seguintes funcionalidades:

- **Adicionar Monitor**: Capacidade para adicionar novos monitores com o objetivo de rastrear a disponibilidade e o desempenho dos serviços.

- **Editar Monitor**: Capacidade para alterar as configurações de um monitor existente.

- **Excluir Monitor**: Capacidade para remover um monitor.

- **Pausar/Iniciar Monitor**: Capacidade para suspender ou iniciar a monitoração de um serviço específico.

- **Resetar Estatísticas do Monitor**: Capacidade para zerar as estatísticas de um monitor.

- **Suporte para Vários Tipos de Teste**: O sistema deve suportar uma variedade de tipos de teste (Ping, Verificação de Porta, etc.), permitindo aos usuários monitorar a disponibilidade do site, a capacidade de resposta do ping e a abertura da porta.

- **Suporte para Ações em Massa**: O sistema deve suportar ações em massa, permitindo aos usuários iniciar, suspender ou zerar estatísticas para vários monitores simultaneamente.

- **Estatísticas para Monitores Específicos**: O sistema deve fornecer estatísticas para monitores específicos, incluindo tempo de atividade geral (últimos 1/7/30 dias) e registros de incidentes.