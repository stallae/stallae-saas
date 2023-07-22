### User_API.md

#  Usuário

A API do usuário Stallae é voltada para o usuário e usada principalmente através de uma interface de front-end para registrar usuários, gerenciar contatos, gerenciar monitores e visualizar dados históricos.

## Características

### Segurança

A API do usuário inclui várias medidas de segurança, incluindo:

- Autenticação multifatorial
- Senha de uso único (OTP)
- Bloqueio temporário de conta para proteção contra ataques de força bruta
- Registro de acesso e alterações em qualquer objeto

### Desempenho

A API do usuário foi projetada para ser eficiente e rápida, incluindo:

- Cache sempre que possível para reduzir chamadas ao banco de dados/camada de gerenciamento para conteúdo que não muda com frequência
- Equilíbrio entre a taxa de transferência de dados (consultas de menor tamanho) e a minimização de chamadas ao banco de dados

### Registro/Login/Reset de Senha

Embora esta seja uma API voltada para o usuário, queremos limitar o registro, o login e o reset de senha apenas à nossa própria interface para prevenir abusos. Esta função deve exigir uma chave/senha especial para ser usada. O usuário terá uma chave API que ele usará para acessar seu perfil.

### Gerenciamento de Contatos

A API do usuário oferece funcionalidades para gerenciar contatos para alertas. Aqui estão as operações que são suportadas:

- **Adicionar Contato**: Os usuários podem adicionar novos contatos para receber alertas.

- **Modificar Contato**: Os usuários podem modificar as informações de um contato existente.

- **Excluir Contato**: Os usuários podem remover um contato.

- **Pausar/Iniciar Contato**: Os usuários podem pausar ou iniciar alertas para um contato específico.

Essas operações devem ser coordenadas com os vários meios suportados pelo agente de alerta. Alguns meios provavelmente exigirão tipos diferentes de configurações do que outros.

A interface do usuário para o gerenciamento de contatos será intuitiva e fácil de usar, permitindo aos usuários gerenciar seus contatos de forma eficiente.

### Gerenciamento de Monitores

A API do usuário oferece recursos para gerenciar monitores. Aqui estão as operações que são suportadas:

- **Adicionar Monitor**: Os usuários podem adicionar novos monitores para rastrear a disponibilidade e o desempenho dos serviços.

- **Editar Monitor**: Os usuários podem modificar as configurações de um monitor existente.

- **Excluir Monitor**: Os usuários podem remover um monitor.

- **Pausar/Iniciar Monitor**: Os usuários podem pausar ou iniciar a monitoração de um serviço específico.

- **Resetar Estatísticas do Monitor**: Os usuários podem redefinir as estatísticas de um monitor.

- **Suporte para Vários Tipos de Teste**: A API suporta uma variedade de tipos de teste, permitindo aos usuários monitorar a disponibilidade do site, a capacidade de resposta do ping e a abertura da porta.

- **Suporte para Ações em Massa**: A API suporta ações em massa, permitindo aos usuários iniciar, pausar ou redefinir estatísticas para vários monitores ao mesmo tempo.

- **Estatísticas para Monitores Específicos**: A API fornece estatísticas para monitores específicos, incluindo tempo de atividade geral (1/7/30 dias) e incidentes.
