# In or Out

## 1. Introdução

Priorização de requisitos é um processo realizado após elicitar os requisitos, com o intuito de organizar o escopo do projeto e definir um ponto de partida de forma a gerar valor ao cliente desde o inicio do desenvolvimento.
Nessa seção vai ser apresentado a técnica In or Out de priorização de requisitos.

## 2. Metodologia
In or Out é um dos metódos mais simples que consistes em uma decisão binária com relação a cada requisito se ele entra ou sai. Essa decisão é feita por release definindo quais são os requsitos que serão implementados por release.

## 3. In or Out

### 3.1 Requisitos Funcionais
| ID  | Requisito | Técnica | Prioridade |
| :-: | :-------- | :-----: | :--------: |
| RF01 | O sistema deve permitir cadastrar um aluno | Introspecção<br>Storytelling | In |
| RF02 | O sistema deve permitir cadastrar um professor | Introspecção | In |
| RF03 | O sistema deve permitir cadastrar uma disciplina | Introspecção | In |
| RF04 | O sistema deve permitir cadastrar login e senha para entrar nas disciplinas | Introspecção<br>Observação | In |
| RF05 | O sistema deve permitir cadastrar novas atividades | Introspecção<br>Storytelling | In |
| RF06 | O sistema deve permitir listar os alunos cadastrados | Introspecção | Out |
| RF07 | O sistema deve permitir listar as disciplinas cadastradas | Introspecção | In |
| RF08 | O sistema deve permitir pesquisar por uma disciplina a partir do nome do professor | Introspecção<br>Observação  | Out |
| RF09 | O sistema deve permitir pesquisar disciplina por nome | Introspecção<br>Observação  | In |
| RF10 | O sistema deve permitir pesquisar aluno por nome | Introspecção | Out |
| RF11 | O sistema deve permitir a consulta de notas das atividades | Introspecção<br>Observação<br>Storytelling | In |
| RF12 | O sistema deve permitir a inserção de arquivos para envio das atividades | Introspecção<br>Observação | In |
| RF13 | O sistema deve permitir retirar um aluno ou todos os alunos da disciplina | Introspecção | In |
| RF14 | O sistema deve permitir criar restrições de acesso para as atividades | Introspecção | Out |
| RF15 | O sistema deve permitir criar limite de tentativas para as atividades | Introspecção | Out |
| RF16 | O sistema deve permitir criar limite de data de envio para as atividades | Introspecção<br>Storytelling | In |
| RF17 | O sistema deve permitir que o professor crie um forúm | Introspecção | In |
| RF18 | O sistema deve permitir que um aluno/professor cadastre uma pergunta no forúm | Introspecção<br>Observação<br>Storytelling | In |
| RF19 | O sistema deve permitir a inserção de arquivos nas perguntas | Introspecção<br>Observação<br>Storytelling | In |
| RF20 | O sistema deve permitir que um aluno/professor cadastre uma resposta no forúm | Introspecção<br>Observação<br>Storytelling | In |
| RF21 | O sistema deve permitir a inserção de arquivos nas respostas do forúm | Introspecção<br>Observação<br>Storytelling | In |
| RF22 | O sistema deve permitir alterar respostas/perguntas cadastradas feita pelo mesmo nos forúns | Introspecção | Out |
| RF23 | O sistema deve permitir o professor a alterar as restrições de data, tentativas e acesso | Introspecção | In |
| RF24 | O sistema deve permitir o professor a alterar o cargo de um aluno inscrito em sua disciplina | Introspecção | Out |
| RF25 | O sistema deve permitir listar as disciplinas que o aluno se cadastrou | Introspecção | In |
| RF26 | O sistema deve permitir listar as atividades do aluno por data | Introspecção | Out |
| RF27 | O sistema deve notificar aos usuários cadastrados na disciplina quando uma pergunta no forúm é cadastrada | Introspecção | In |
| RF28 | O sistema deve permitir fazer alteração nas informações do usuário cadastrado | Introspecção<br>Observação | In |
| RF29 | O sistema deve permitir que o professor visualize o tempo que os alunos utilizaram para a realização das atividades | Introspecção | Out |
| RF30 | O sistema deve permitir enviar mensagem direta para um aluno/professor | Introspecção<br>Storytelling | Out |
| RF31 | O sistema deve permitir o aluno/professor fazer login | Introspecção<br>Observação<br>Storytelling | In |
| RF32 | O sistema deve permitir o aluno/professor fazer logout | Introspecção | In |
| RF35 | O aluno deve ser capaz de ver a senha digitada | Observação | Out |
| RF36 | O aluno deve ser capaz de recuperar a senha | Observação | In |
| RF37 | O sistema deverá emitir um email de recuperação de senha | Observação | In |
| RF38 | O aluno deve poder visualizar seus dados pessoais | Observação | In |
| RF42 | O aluno deve poder visualizar o resumo dos cursos em que está cadastrado | Observação | Out |
| RF43 | O sistema deve emitir notificações ao aluno quando o prazo de alguma atividade estiver próximo | Observação<br>Storytelling | Out |
| RF44 | O aluno deve ser capaz de marcar atividades como concluída | Observação | Out |
| RF45 | O sistema deve atualizar o progresso do aluno no curso | Observação | Out |
| RF46 | O aluno deve ser capaz de retroceder e avançar uma seção do curso | Observação | Out |
| RF47 | O sistema deve mostrar o nome das seções anterior e posterior a seção em que o aluno se encontra | Observação | Out |
| RF48 | O sistema deve mostrar o índice do curso completa | Observação | Out |
| RF52 | O aluno deve ser capaz de visualizar o status de um arquivo enviado | Observação | In |
| RF53 | O aluno deve ser capaz de visualizar o comentários de um arquivo enviado | Observação | In |
| RF55 | O aluno deve ser capaz de ver as restrições de envio de um arquivo | Observação | Out |
| RF56 | O aluno deve poder baixar diferentes tipos de arquivo disponibilizados pelo professor | Observação<br>Storytelling | In |
| RF57 | O aluno deve poder visualizar a descrição de cada arquivo | Observação | In |
| RF58 | O sistema deve ter diferentes ícones para diferentes tipos de atividades de um curso | Observação | Out |
| RF59 | O sistema deve deixar claro quando o aluno estiver saindo do aplicativo para acessar uma URL no navegador | Observação | Out |
| RF60 | O aluno deve poder ver os próximos eventos de um curso | Observação | In |
| RF61 | O aluno deve ser capaz de ver todos os participantes do curso | Observação | Out |
| RF63 | O aluno deve poder favoritar um curso | Observação | Out |
| RF64 | O aluno deve poder arquivar um curso | Observação | Out |
| RF65 | O aluno deve ser capaz de fazer o download de um curso | Observação | In |
| RF66 | O aluno deve poder ver informações gerais sobre o curso | Observação | Out |
| RF68 | O aluno deve ser capaz de encontrar por cursos que esteja matriculado | Storytelling | Out |
| RF71 | O sistema deve mostrar os cursos mais recentes primeiro | Storytelling | Out |
| RF72 | O professor deve ser capaz de disponibilizar materiais do curso | Storytelling | In |
| RF74 | O professor deve ser capaz de organizar o curso em módulos | Storytelling | In |
| RF75 | O aluno deve ser capaz de visualizar as próximas tarefas do curso | Storytelling | Out |
| RF76 | O aluno deve ser capaz de visualizar a data das tarefas de um curso | Storytelling | Out |
| RF78 | O professor deve ser capaz de cadastrar alunos na disciplina | Storytelling | Out |
| RF79 | O professor deve ser capaz de cadastrar uma disciplina | Storytelling | Out |
| RF86 | O professor deve ser capaz de criar restrições de entrega para as atividades | Storytelling | Out |
| RF87 | O professor deve ser capaz de criar restrições de envio para as atividades | Storytelling | Out |
| RF89 | O aluno deve ser capaz de fazer a revisão da atividade finalizada | Storytelling | Out |

### 3.2 Requisitos Não Funcionais
| ID  | Requisito | Técnica | Prioridade |
| :-: | :-------- | :-----: | :--------: |
| RNF01 | O aluno somente poderá vincular o sistema com sua instituição de ensino através de um endereço eletrônico | Observação | Out |
| RNF02 | O sistema tem que ser disponibilizado como app mobile | Storytelling | In |
| RNF03 | O aluno deve permanecer logado no app até fazer logout | Storytelling | In |

## 4. Referências

>WIEGERS, Karl; BEATTY, Joy. Software Requirements, Third Edition. [S.L.]: Microsoft, [20--]. 9 slides, P&B. Disponível em: https://aprender3.unb.br/pluginfile.php/2124455/mod_resource/content/1/Priorização%20de%20Req.pdf. Acesso em: 30 nov. 2022.

## 5. Versionamento

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 30/11/2022 | 30/11/2022 | Adição técnica In or Out de priorização de requisitos | Artur Vinicius | Rodolfo Cabral |
