### Monitor

No contexto da Stallae, um "monitor" refere-se a uma entidade ou instância de monitoramento que rastreia a disponibilidade, a capacidade de resposta ou outras métricas de desempenho de um serviço ou recurso específico. Em sua essência, um monitor é configurado para realizar verificações ou "testes" em intervalos regulares e relatar as descobertas.

Um exemplo clássico de um monitor seria um que rastreia a disponibilidade de um site. Este monitor estaria configurado para enviar uma solicitação ao site em intervalos regulares (por exemplo, a cada minuto). Se o site responder apropriadamente, o monitor marcaria o teste como bem-sucedido. Se o site não responder, ou responder com um erro, o monitor marcará o teste como falho e iniciará o protocolo de alerta.

Os monitores podem ser configurados para monitorar uma variedade de serviços ou recursos, dependendo das capacidades da Stallae. Isso pode incluir sites, servidores de e-mail, bancos de dados, servidores de arquivos e assim por diante.

### Teste

No contexto de monitoramento, um "teste" é uma verificação única realizada por um monitor. Cada teste é uma tentativa do monitor para verificar a disponibilidade, a capacidade de resposta, ou alguma outra métrica de desempenho do serviço ou recurso que está sendo monitorado.

Por exemplo, se um monitor está configurado para verificar a disponibilidade de um site a cada minuto, cada uma dessas verificações seria considerada um "teste". Portanto, em um dia, esse monitor realizaria aproximadamente 1440 testes (24 horas x 60 minutos).

Os resultados desses testes são coletados e usados para calcular várias estatísticas, como o tempo total de atividade (a porcentagem de testes bem-sucedidos), a duração média das interrupções (quanto tempo em média o serviço fica indisponível quando ocorre uma falha), entre outros.