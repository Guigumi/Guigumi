# Política de Privacidade da Luna

**Última atualização:** 30 de julho de 2026  
**Vigência:** 30 de julho de 2026  
**Versão:** 1.0

Esta Política de Privacidade ("**Política**") explica como a **Luna**, uma
aplicação automatizada para Discord ("**Luna**", "**Aplicação**", "**Bot**" ou
"**Serviço**"), acessa, coleta, utiliza, armazena, compartilha e elimina dados.

A Luna é mantida pelo responsável identificado publicamente como
**Guigumi** ("**Operador**" ou "**Controlador**"). Solicitações de privacidade
podem ser abertas de forma privada no
[servidor de suporte da Luna](https://discord.gg/ZXEHJBhCnx).

## Resumo essencial

- A Luna trata dados fornecidos pelo Discord e pelos próprios usuários para
  executar comandos, configurações, moderação, níveis, música, tickets,
  lembretes, integrações e demais funcionalidades solicitadas.
- Dependendo das funções habilitadas por um administrador, a Luna pode
  processar conteúdo de mensagens, anexos, reações, cargos e atividade em voz.
- Conteúdo comum de mensagens é usado para funções como comandos por prefixo,
  AutoMod, registro de edições ou exclusões, starboard e contagem de atividade.
- A Luna não vende dados pessoais e não os utiliza para publicidade
  comportamental.
- Registros técnicos e eventos internos possuem rotação de até **7 dias** no
  ambiente atualmente configurado. Dados necessários a funcionalidades podem
  permanecer enquanto a funcionalidade ou relação com o Serviço existir.
- Dados podem ser enviados a serviços externos quando isso for necessário para
  atender um comando, como Discord, Steam, osu!, Spotify, provedores de mídia e
  Mojang.
- O titular pode solicitar acesso, correção ou exclusão abrindo um atendimento
  privado no servidor de suporte.
- A Luna não deve ser usada por menores de 13 anos nem por pessoas abaixo da
  idade mínima exigida pelo Discord em seu país.

Este resumo facilita a leitura, mas as seções seguintes contêm as informações
completas.

## 1. Escopo

1.1. Esta Política se aplica ao tratamento realizado pelo Operador por meio da
Luna, incluindo:

- interações, comandos, botões, menus e formulários;
- eventos recebidos pelas APIs do Discord;
- dados persistidos no banco de dados da Aplicação;
- arquivos de log e cópias de segurança operacionais;
- integrações solicitadas com serviços externos; e
- comunicações de suporte relacionadas ao Bot.

1.2. Esta Política não controla o tratamento realizado:

- pelo Discord, que possui política própria;
- pelos administradores dos servidores do Discord;
- por sites, APIs e serviços externos independentes;
- por outros bots instalados no mesmo servidor; ou
- fora das funcionalidades da Luna.

1.3. O repositório de código da Luna é privado. A versão pública desta Política
é disponibilizada separadamente para que usuários e o Discord possam
consultá-la sem acesso ao código-fonte.

## 2. Papéis e responsabilidades

2.1. **Operador da Luna.** Guigumi determina as finalidades e os meios
essenciais do tratamento realizado para operar, proteger e manter a Luna.

2.2. **Administradores de servidores.** Administradores escolhem instalar a
Luna, concedem permissões, habilitam recursos, definem canais de logs e
configuram regras locais. Em relação a essas decisões, podem atuar como
controladores independentes e devem cumprir suas próprias obrigações legais.

2.3. **Discord.** O Discord fornece a plataforma e suas APIs e trata dados de
acordo com seus próprios termos e políticas. A Luna é uma aplicação
independente e não é operada pela Discord Inc.

2.4. Um administrador deve informar os membros sobre automações relevantes,
principalmente monitoramento de atividade, AutoMod, logs de mensagens,
transcrições de tickets, starboard e sistemas de níveis.

## 3. Dados acessados ou coletados

A Luna trata somente as categorias aplicáveis às funcionalidades habilitadas e
às ações executadas.

### 3.1. Identificadores e dados básicos do Discord

Podem ser acessados ou armazenados:

- ID do usuário;
- ID do servidor, canal, mensagem, interação, cargo e webhook;
- nome de usuário, nome de exibição, apelido e menção;
- avatar, banner e respectivas URLs;
- cargos, permissões e situação de membro no servidor;
- data de criação da conta ou entrada no servidor, quando necessária para
  verificação ou apresentação de perfil;
- idioma ou localidade configurada, quando disponibilizada; e
- informações básicas de servidores e canais, como nome, ícone e tipo.

IDs do Discord são identificadores persistentes e podem ser considerados dados
pessoais quando associados a uma pessoa.

### 3.2. Mensagens, comandos e interações

Conforme a configuração do servidor, a Luna pode processar:

- conteúdo de comandos slash e comandos enviados por prefixo;
- argumentos, consultas, URLs e opções fornecidas aos comandos;
- conteúdo de mensagens necessário à detecção de comandos ou expressões;
- conteúdo novo e anterior de mensagens editadas;
- conteúdo e metadados de mensagens excluídas;
- anexos, nomes de arquivos, URLs, tipo e tamanho dos anexos;
- reações, emojis, quantidade de reações e usuários envolvidos;
- respostas a botões, menus de seleção e formulários;
- menções a usuários, cargos ou todos os membros;
- conteúdo incluído em tickets, lembretes, notificações, sorteios, templates,
  playlists e configurações; e
- data, hora, autor e canal relacionados à interação.

O conteúdo de mensagens comuns pode ser lido em tempo real para funcionalidades
como AutoMod, comandos por prefixo, rolagem passiva de dados, ponte com
Minecraft, atividade, logs de edição ou exclusão e starboard.

### 3.3. Atividade e voz

Quando o rastreamento correspondente estiver habilitado, podem ser tratados:

- quantidade e comprimento de mensagens;
- horário da última atividade;
- canal relacionado à atividade;
- entrada, saída e movimentação em canais de voz;
- início, checkpoints e duração acumulada de sessões de voz;
- estado necessário para canais temporários e reprodução musical;
- reações utilizadas para XP, verificação, cargos ou starboard; e
- estatísticas derivadas, como XP, nível, sequência diária e rankings.

A Luna não grava o áudio das conversas de voz. Ela processa estados e duração de
participação necessários às funções habilitadas.

### 3.4. Administração, moderação e segurança

Podem ser tratados:

- advertências, motivos, data e usuário afetado;
- ações de silenciamento, expulsão, banimento e desbloqueio;
- regras de AutoMod, palavras bloqueadas, filtros, limites e punições;
- eventos de entrada e saída de membros;
- alterações de cargos, canais, servidor, apelido, avatar e voz;
- autor ou executor provável de uma ação, quando identificável pelo registro de
  auditoria do Discord;
- configurações de logs e categorias habilitadas;
- verificações passivas e idade aproximada da conta;
- tentativas de abuso, falhas, violações e medidas aplicadas; e
- dados necessários à prevenção de fraude e proteção da infraestrutura.

### 3.5. Tickets, suporte e transcrições

O sistema de tickets pode tratar:

- ID do criador, atendente e responsável pelo fechamento;
- servidor, canal, status e horários;
- até as 100 mensagens mais recentes do ticket no momento do fechamento;
- nome de usuário, ID, horário e conteúdo das mensagens;
- nomes dos arquivos anexados; e
- arquivo de transcrição enviado ao canal de logs escolhido pelo administrador.

Depois de enviada ao canal de logs, a transcrição passa a permanecer também na
infraestrutura do Discord e sob o controle dos administradores do servidor.

### 3.6. Perfil, níveis e economia virtual

Podem ser armazenados:

- mensagens contabilizadas, tempo em voz, XP e nível;
- recordes de voz e comprimento de mensagem;
- tema, fundos e opções visuais escolhidos;
- moedas, saldo bancário virtual, itens e inventário;
- sequência e horário de recompensas diárias;
- posições em rankings e conquistas; e
- configurações de canais, multiplicadores e cargos de nível.

Esses elementos são virtuais e não possuem valor monetário.

### 3.7. Música

Para disponibilizar recursos musicais, a Luna pode tratar:

- ID do usuário e do servidor;
- faixa, artista, plataforma, URL e termo de busca;
- duração de reprodução e histórico de faixas;
- playlists criadas pelo usuário, nomes e músicas incluídas;
- fila e estado temporário do player; e
- comandos de controle e usuário que solicitou uma faixa.

### 3.8. Minecraft

Quando a integração estiver habilitada, podem ser tratados:

- ID do usuário e do servidor do Discord;
- nickname e UUID público do Minecraft;
- situação de vínculo ou whitelist;
- erros de sincronização;
- mensagens e eventos encaminhados entre Discord e Minecraft;
- configurações de canal e webhook; e
- endereço público do servidor Minecraft quando necessário à função de status
  ou conexão.

A integração não exige o endereço IP residencial do usuário. Serviços externos
consultados pelo servidor da Luna podem receber o endereço IP da infraestrutura
que executa o Bot, como ocorre normalmente em requisições de internet.

### 3.9. Sorteios, eventos e lembretes

Podem ser armazenados:

- ID de criadores, participantes, inscritos e vencedores;
- título, descrição, prêmio e quantidade de vencedores;
- horários de criação, lembrete, início e encerramento;
- servidor, canal e mensagem relacionados;
- preferência de participação ou saída; e
- texto de lembretes pessoais.

### 3.10. Configurações e conteúdo personalizado

Administradores e usuários podem fornecer:

- mensagens de boas-vindas e saída;
- imagens, cores, textos, links e URLs de fundo;
- templates de containers e mensagens;
- macros de dados;
- configuração de cargos automáticos e canais temporários;
- canais, categorias, mensagens, regras e opções do servidor; e
- URLs de webhook inseridas voluntariamente por administradores.

URLs de webhook devem ser tratadas como credenciais. Administradores não devem
compartilhá-las em canais públicos.

### 3.11. Integrações e informações públicas externas

Conforme o comando solicitado, a Luna pode consultar e apresentar:

- perfis, pontuações e estatísticas públicas do osu!;
- jogos, avaliações, conquistas e contagem de jogadores da Steam;
- metadados públicos de Spotify, YouTube e outras fontes musicais;
- perfil público e UUID do Minecraft fornecidos pela Mojang;
- imagens de avatar e cabeça de Minecraft;
- GIFs e imagens de serviços de conteúdo recreativo;
- dados públicos de animes; e
- metadados de URLs fornecidas para download ou conversão.

Algumas respostas públicas podem ser mantidas temporariamente em cache para
reduzir chamadas repetidas.

### 3.12. Registros técnicos

Para operação, segurança e diagnóstico, podem ser registrados:

- ID de usuário, servidor, canal, interação e mensagem;
- comando ou componente utilizado;
- data, hora, identificador de rastreamento e tipo de evento;
- nomes de usuário e servidor presentes em mensagens operacionais;
- erros, códigos, stack traces e informações de execução;
- estado de conexão e latência;
- atividade administrativa e eventos internos; e
- em modo de depuração, conteúdo de mensagens recebido pelo fluxo de mensagens.

Segredos reconhecidos por chaves como senha, token, secret e authorization são
removidos dos registros estruturados. Ainda assim, o usuário não deve inserir
segredos em campos comuns de texto.

## 4. Dados que a Luna não pretende coletar

A Luna não solicita intencionalmente:

- senha ou token de acesso do Discord;
- token de outros bots;
- número de cartão ou dados bancários reais;
- documento de identidade;
- dados de saúde;
- biometria;
- localização precisa;
- orientação sexual, religião ou opinião política; ou
- conteúdo íntimo ou dados de crianças abaixo da idade permitida.

Não envie essas informações à Luna. Caso sejam inseridas em mensagens ou campos
processados por uma função habilitada, elas poderão ser tratadas incidentalmente
até serem removidas.

## 5. Como os dados são obtidos

Os dados podem ser obtidos:

- diretamente do Discord por eventos, interações e APIs;
- diretamente do usuário por comandos, mensagens, botões e formulários;
- de administradores por configurações do servidor;
- de serviços externos consultados a pedido do usuário;
- de informações públicas associadas a identificadores fornecidos; e
- automaticamente a partir do uso, como contadores, duração e registros
  técnicos.

## 6. Finalidades do tratamento

Os dados são tratados para:

1. executar comandos e entregar respostas;
2. manter configurações específicas de servidores e usuários;
3. operar níveis, perfis, rankings, economia e recompensas;
4. reproduzir música e manter playlists ou histórico solicitado;
5. executar AutoMod, logs, advertências, tickets e outras ferramentas de
   administração;
6. criar lembretes, eventos, notificações e sorteios;
7. integrar Discord, Minecraft e serviços públicos externos;
8. gerar cartões, imagens, templates e conteúdo recreativo;
9. prevenir spam, fraude, exploração de falhas e abuso;
10. diagnosticar erros, medir estabilidade e manter a segurança;
11. atender suporte e solicitações de titulares;
12. cumprir obrigações legais e ordens válidas;
13. exercer ou defender direitos em procedimentos; e
14. melhorar funcionalidades por meio de informações agregadas ou
    desidentificadas, quando possível.

Dados obtidos pelas APIs do Discord não são utilizados para publicidade
comportamental, venda de perfis ou finalidades incompatíveis com as funções
declaradas da Luna.

## 7. Bases legais

Quando a Lei Geral de Proteção de Dados Pessoais brasileira ("**LGPD**") for
aplicável, o tratamento poderá se apoiar, conforme o caso, em:

- **execução de contrato ou procedimentos relacionados:** para fornecer a
  funcionalidade solicitada e cumprir os Termos de Uso;
- **legítimo interesse:** para segurança, prevenção de abuso, diagnóstico,
  manutenção e funcionamento esperado do Serviço, após consideração dos
  direitos do titular;
- **consentimento:** quando uma função opcional exigir manifestação específica,
  que poderá ser retirada sem afetar tratamentos anteriores legítimos;
- **cumprimento de obrigação legal ou regulatória;**
- **exercício regular de direitos** em processo judicial, administrativo ou
  arbitral; e
- **proteção da vida ou da incolumidade física**, em situações excepcionais
  previstas em lei.

A base aplicável depende da finalidade e do contexto. A simples aceitação dos
Termos não é tratada como consentimento genérico para todas as operações.

## 8. Uso de conteúdo de mensagens

8.1. A Luna utiliza o intent de conteúdo de mensagens porque oferece comandos
por prefixo e funções que dependem da análise de mensagens.

8.2. O conteúdo pode ser processado para:

- reconhecer e executar comandos;
- aplicar regras de AutoMod;
- registrar edições e exclusões quando o administrador habilitar a categoria;
- gerar starboard;
- compilar transcrições de tickets;
- encaminhar mensagens à integração Minecraft;
- reconhecer expressões de dados; e
- contar atividade e comprimento de mensagens.

8.3. Para XP comum, a Luna persiste contadores e comprimento máximo, não uma
cópia permanente de cada mensagem. Outras funções, como logs de moderação,
starboard e tickets, podem reproduzir conteúdo em canais escolhidos pelo
administrador.

8.4. Em modo de depuração, conteúdo de mensagens pode aparecer em logs técnicos
rotacionados. O Operador deve limitar o modo de depuração ao diagnóstico e
evitar sua utilização desnecessária em produção.

## 9. Compartilhamento e destinatários

A Luna não vende nem aluga dados pessoais. Dados podem ser compartilhados
somente nas situações descritas abaixo.

### 9.1. Discord

Respostas, logs, cards, transcrições, mensagens e arquivos gerados pela Luna são
enviados ao Discord. O Discord também fornece os eventos e dados necessários ao
Bot. Esse tratamento é regido adicionalmente pela
[Política de Privacidade do Discord](https://discord.com/privacy).

### 9.2. Administradores e membros do servidor

Conforme a função, dados podem ser exibidos:

- em rankings, perfis, starboard e respostas públicas;
- em canais de logs, moderação, tickets ou suporte;
- a administradores autorizados;
- a participantes de sorteios, eventos ou canais; e
- ao próprio titular em respostas privadas ou públicas.

O nível de visibilidade depende das permissões e configurações do servidor. Um
administrador não deve expor dados além do necessário.

### 9.3. Infraestrutura e prestadores técnicos

Dados podem ser processados por serviços necessários a hospedagem, banco de
dados, rede, backup, monitoramento ou manutenção. Esses prestadores devem ter
acesso limitado à prestação do serviço e estar sujeitos a obrigações
compatíveis de segurança e confidencialidade.

### 9.4. Serviços consultados por funcionalidades

Uma consulta, termo, nickname, URL ou outro dado necessário pode ser transmitido
ao serviço correspondente, incluindo:

- Discord;
- Steam;
- osu!;
- Spotify;
- YouTube e provedores de mídia compatíveis;
- Lavalink ou infraestrutura de reprodução musical;
- Mojang, Microsoft e serviços de avatar Minecraft;
- provedores de GIFs e informações de anime; e
- sites indicados pelo próprio usuário em comandos de download.

Esses terceiros podem registrar endereço IP da infraestrutura da Luna,
user-agent, consulta e outros metadados técnicos conforme suas próprias
políticas. A Luna normalmente não envia o ID do Discord a esses serviços, salvo
se isso for necessário, informado ou estiver contido no dado fornecido pelo
próprio usuário.

### 9.5. Obrigações legais e proteção

Dados poderão ser preservados ou fornecidos:

- em cumprimento de lei ou ordem válida de autoridade competente;
- para investigar fraude, abuso ou incidente de segurança;
- para proteger direitos, integridade ou segurança de pessoas;
- para exercer ou defender direitos; ou
- em reorganização ou transferência legítima da operação, com salvaguardas
  adequadas.

## 10. Transferências internacionais

Discord e alguns serviços ou prestadores externos podem operar fora do Brasil.
Consequentemente, dados enviados a esses destinatários podem ser tratados em
outros países.

Quando aplicável, o Operador buscará utilizar mecanismos admitidos pela
legislação, limitar os dados ao necessário e selecionar serviços com medidas
compatíveis de proteção. As leis de outros países podem diferir das leis
brasileiras.

## 11. Retenção

Os prazos variam conforme a finalidade:

| Categoria | Retenção praticada ou critério |
|---|---|
| Logs técnicos da aplicação | Rotação de até 7 dias |
| Eventos internos de auditoria no banco | Exclusão automática após 7 dias |
| Cache de consultas externas | Até a expiração definida para o cache |
| Sessão de voz em andamento | Até o encerramento ou recuperação da sessão; a duração agregada pode permanecer no perfil |
| Filas de música e cooldowns | Em memória, durante a sessão ou pelo tempo do controle |
| Configurações de servidor | Enquanto necessárias à configuração ou até remoção, redefinição ou solicitação válida |
| XP, perfil, economia e estatísticas | Enquanto a funcionalidade ou conta no Serviço permanecer, ou até solicitação válida |
| Playlists, macros e templates | Até exclusão pelo usuário, descontinuação da função ou solicitação válida |
| Lembretes, sorteios e notificações | Enquanto necessários à execução, histórico operacional, prevenção de duplicidade ou solicitação válida |
| Advertências e moderação | Conforme necessidade administrativa do servidor, exercício de direitos e solicitação válida |
| Metadados de tickets | Enquanto necessários ao histórico de atendimento ou até solicitação válida |
| Transcrição publicada no Discord | Conforme retenção do Discord e decisões dos administradores do servidor |
| Vínculo Minecraft | Até desvinculação, remoção administrativa ou solicitação válida |
| Backups do banco de dados | Rotação de até 7 dias |

11.1. Nem todas as categorias funcionais possuem atualmente um prazo automático
fixo. Nesses casos, os dados são mantidos enquanto necessários à finalidade,
segurança, funcionamento ou exercício de direitos e devem ser excluídos quando
deixarem de ser necessários ou após solicitação válida, ressalvadas hipóteses
legais de conservação.

11.2. Após exclusão do banco principal, cópias residuais podem permanecer em
backups rotativos por até 7 dias e serão eliminadas no ciclo normal, salvo
obrigação legal de preservação.

11.3. A remoção da Luna de um servidor não garante, por si só, eliminação
instantânea de todas as configurações e históricos. Um administrador ou titular
deve solicitar a exclusão quando ela não estiver disponível diretamente por
comando.

11.4. Conteúdo copiado para canais do Discord, como logs, cards, starboard e
transcrições, deve ser removido também pelos administradores do servidor ou pelo
Discord, pois não permanece exclusivamente sob controle do Operador.

## 12. Exclusão de dados

### 12.1. Como solicitar

Para solicitar exclusão:

1. entre no [servidor de suporte da Luna](https://discord.gg/ZXEHJBhCnx);
2. abra um ticket ou atendimento **privado**;
3. informe que se trata de uma solicitação de privacidade ou exclusão;
4. forneça seu ID de usuário do Discord e, se aplicável, os IDs dos servidores
   abrangidos;
5. descreva o escopo desejado, como perfil, playlists, lembretes, Minecraft ou
   todos os dados vinculados; e
6. conclua a verificação razoável de titularidade solicitada pelo atendimento.

Não publique documentos, tokens, senhas ou dados sensíveis em canais públicos.

### 12.2. Verificação

O Operador poderá confirmar que a solicitação partiu da conta envolvida, pedir
identificadores adicionais ou verificar a autoridade de um administrador. Essa
verificação busca impedir exclusão ou acesso fraudulento a dados de terceiros.

### 12.3. Limites

Alguns dados podem ser conservados quando necessário para:

- cumprir obrigação legal ou ordem válida;
- exercer ou defender direitos;
- prevenir fraude e abuso;
- resguardar segurança;
- respeitar pedido legítimo de outro controlador; ou
- atender outra hipótese permitida pela legislação.

Quando possível, dados serão bloqueados ou minimizados em vez de mantidos em uso
comum.

## 13. Direitos dos titulares

Nos limites da legislação aplicável, o titular pode solicitar:

- confirmação da existência de tratamento;
- acesso aos dados;
- correção de dados incompletos, inexatos ou desatualizados;
- anonimização, bloqueio ou exclusão de dados desnecessários, excessivos ou
  tratados em desconformidade;
- portabilidade, quando regulamentada e tecnicamente aplicável;
- informação sobre compartilhamentos;
- informação sobre a possibilidade de negar consentimento e suas consequências;
- revogação do consentimento;
- oposição a tratamento irregular;
- revisão de decisões tomadas unicamente com base em tratamento automatizado,
  quando aplicável; e
- petição perante a Autoridade Nacional de Proteção de Dados ou órgãos de
  defesa do consumidor.

Uma resposta poderá exigir verificação de identidade. Direitos podem estar
sujeitos a exceções legais e à proteção de dados de terceiros.

## 14. Decisões automatizadas

14.1. AutoMod, verificação passiva, XP, atribuição de cargos, sorteios e outros
sistemas aplicam regras automatizadas configuradas pelo Operador ou por
administradores.

14.2. Essas decisões podem afetar visibilidade de mensagens, advertências,
cargos, acesso a canais, XP ou participação em funções do servidor.

14.3. Sistemas automatizados podem produzir erros. Contestações sobre regra
local devem ser dirigidas primeiro aos administradores do servidor. Questões
relacionadas ao funcionamento da Luna podem ser encaminhadas ao suporte.

14.4. Quando a legislação assegurar revisão de decisão exclusivamente
automatizada, o titular poderá solicitá-la pelo canal de privacidade.

## 15. Segurança

O Operador adota medidas técnicas e administrativas proporcionais ao risco,
incluindo:

- limitação de acesso à infraestrutura;
- armazenamento de segredos fora do código;
- remoção de campos reconhecidos como senhas e tokens dos logs estruturados;
- rotação de logs e backups;
- validação de permissões e ações administrativas;
- uso de conexões e APIs autenticadas quando disponíveis;
- atualizações e monitoramento operacional; e
- procedimentos para resposta a falhas e abuso.

Nenhum sistema conectado à internet é totalmente seguro. O Operador não pode
garantir ausência absoluta de incidentes, mas buscará agir de forma razoável
para prevenir, detectar, conter e remediar riscos.

Usuários e administradores devem proteger suas contas, conceder somente as
permissões necessárias e comunicar suspeitas de incidente imediatamente.

## 16. Incidentes de segurança

Quando um incidente puder causar risco ou dano relevante, o Operador avaliará
seu impacto, adotará medidas de contenção e realizará as comunicações exigidas
pela legislação às autoridades e aos titulares afetados.

Informações poderão ser comunicadas em etapas caso a investigação ainda esteja
em andamento. Detalhes que ampliem o risco de exploração poderão ser
temporariamente limitados.

## 17. Crianças e adolescentes

17.1. A Luna não é destinada a pessoas com menos de 13 anos nem abaixo da idade
mínima estabelecida pelo Discord e pela legislação de seu país.

17.2. Pessoas sem capacidade para consentir sozinhas devem utilizar o Serviço
somente com autorização e supervisão do responsável legal.

17.3. Administradores não devem usar a Luna para solicitar deliberadamente
informações pessoais de crianças.

17.4. Se houver suspeita de tratamento indevido de dados de menor, o
responsável legal poderá contatar o suporte para análise e exclusão.

## 18. Cookies e páginas externas

18.1. A Luna opera dentro do Discord e não utiliza cookies próprios para
executar seus comandos.

18.2. A página pública que hospedar estes documentos e os links externos podem
utilizar cookies ou registros técnicos sob responsabilidade de seus respectivos
operadores. Consulte a política da plataforma de hospedagem utilizada.

## 19. Alterações desta Política

19.1. Esta Política poderá ser atualizada para refletir mudanças legais,
técnicas, operacionais ou nas funcionalidades da Luna.

19.2. A data e a versão no início do documento identificarão a edição vigente.

19.3. Mudanças materiais serão comunicadas de forma razoável pela Luna, pela
página pública da Política ou pelo servidor de suporte, quando possível.

19.4. Se uma nova finalidade exigir consentimento ou outra medida específica,
ela será adotada antes do tratamento correspondente.

## 20. Legislação e documentos relacionados

Esta Política deve ser interpretada em conjunto com:

- os [Termos de Uso da Luna](./terms.md);
- os [Termos de Serviço do Discord](https://discord.com/terms);
- a [Política de Privacidade do Discord](https://discord.com/privacy);
- os [Termos para Desenvolvedores do Discord](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service);
- a [Política para Desenvolvedores do Discord](https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy); e
- a [Lei Geral de Proteção de Dados Pessoais](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm).

Se houver conflito, normas legais obrigatórias e regras aplicáveis da plataforma
prevalecerão em seus respectivos âmbitos.

## 21. Contato

Para exercer direitos, solicitar exclusão, comunicar incidente ou esclarecer
dúvidas:

- **Responsável público pelo Serviço:** Guigumi
- **Canal de atendimento:** [servidor de suporte da Luna](https://discord.gg/ZXEHJBhCnx)
- **Forma recomendada:** ticket privado identificado como solicitação de
  privacidade

Para agilizar o atendimento, informe seu ID do Discord e o escopo da
solicitação. Nunca envie senha, token ou documento em canal público.

