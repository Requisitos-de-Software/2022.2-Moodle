# Requisitos

## 1. Introdução

&emsp;&emsp; Para facilitar a consulta aos requisitos elicitados, usaremos essa página para reunir todos os requisitos elicitados, além de excluir aqueles que são duplicados.

## 2. Metodologia

&emsp;&emsp; Como o número de requisitos elicitados foi bastante extenso, achamos interessante a criação desta página para organizá-los em uma única tabela, que irá conter um identificador, os requisitos e a rastreabilidade dos mesmos.

## 3. Tabelas

### 3.1 Legenda

| Código | Significado |
| ------ | ----------- |
| RF | Requisito Funcional |
| RNF | Requisito Não-Funcional |
| IT | Introspecção |
| OP | Observação passiva |
| ST | Storytelling |

### 3.2 Requisitos Funcionais <div id="requisitos" />

| ID | Descrição | Rastreabilidade |
|:--:|:---------:|:------:|
|:--:|:---------:|:------:|
| RF01 | O sistema deve permitir cadastrar um aluno | [IT01](./introspeccao.md#I01), [ST11](./storytelling.md#ST11) |
| RF02 | O sistema deve permitir cadastrar um professor | [IT02](./introspeccao.md#I02) |
| RF03 | O sistema deve permitir cadastrar uma disciplina | [IT03](./introspeccao.md#I03), [ST13](./storytelling.md#ST13) |
| RF04 | O sistema deve permitir cadastrar login e senha para entrar nas disciplinas | [IT04](./introspeccao.md#I04) |
| RF05 | O sistema deve permitir cadastrar novas atividades | [IT05](./introspeccao.md#I05), [ST18](./storytelling.md#ST18) |
| RF06 | O sistema deve permitir listar os alunos cadastrados | [IT06](./introspeccao.md#I06), [OP28](./observacao_etnografia.md#OP28) |
| RF07 | O sistema deve permitir listar as disciplinas cadastradas | [IT07](./introspeccao.md#I07), [ST02](./storytelling.md#ST02) |
| RF08 | O sistema deve permitir pesquisar por uma disciplina a partir do nome do professor | [IT08](./introspeccao.md#I08) |
| RF09 | O sistema deve permitir pesquisar disciplina por nome | [IT09](./introspeccao.md#I09) |
| RF10 | O sistema deve permitir pesquisar aluno por nome | [IT10](./introspeccao.md#I10) |
| RF11 | O sistema deve permitir a consulta de notas das atividades | [IT11](./introspeccao.md#I11), [OP29](./observacao_etnografia.md#OP29), [ST23](./storytelling.md#ST23) |
| RF12 | O sistema deve permitir a inserção de arquivos para envio das atividades | [IT12](./introspeccao.md#I12), [OP19](./observacao_etnografia.md#OP19) |
| RF13 | O sistema deve permitir retirar um aluno ou todos os alunos da disciplina | [IT13](./introspeccao.md#I13) |
| RF14 | O sistema deve permitir criar restrições de acesso para as atividades | [IT014](./introspeccao.md#I14) |
| RF15 | O sistema deve permitir criar limite de tentativas para as atividades | [IT15](./introspeccao.md#I15) |
| RF16 | O sistema deve permitir criar limite de data de envio para as atividades | [IT16](./introspeccao.md#I16) |
| RF17 | O sistema deve permitir que o professor crie um fórum | [IT17](./introspeccao.md#I17) |
| RF18 | O sistema deve permitir que um aluno/professor cadastre uma pergunta no fórum | [IT18](./introspeccao.md#I18), [OP17](./observacao_etnografia.md#OP17), [ST14](./storytelling.md#ST14), [ST16](./storytelling.md#ST16) |
| RF19 | O sistema deve permitir a inserção de arquivos nas perguntas | [IT19](./introspeccao.md#I19) |
| RF20 | O sistema deve permitir que um aluno/professor cadastre uma resposta no fórum | [IT20](./introspeccao.md#I20), [OP18](./observacao_etnografia.md#OP18), [ST15](./storytelling.md#ST15), [ST17](./storytelling.md#ST17) |
| RF21 | O sistema deve permitir a inserção de arquivos nas respostas do fórum | [IT21](./introspeccao.md#I21) |
| RF22 | O sistema deve permitir alterar respostas/perguntas cadastradas feita pelo mesmo nos fóruns | [IT22](./introspeccao.md#I22) |
| RF23 | O sistema deve permitir o professor a alterar as restrições de data, tentativas e acesso | [IT23](./introspeccao.md#I23), [ST20](./storytelling.md#ST20), [ST21](./storytelling.md#ST21) |
| RF24 | O sistema deve permitir o professor a alterar o cargo de um aluno inscrito em sua disciplina | [IT24](./introspeccao.md#I24) |
| RF25 | O sistema deve permitir listar as disciplinas que o aluno se cadastrou | [IT25](./introspeccao.md#I25) |
| RF26 | O sistema deve permitir listar as atividades do aluno por data | [IT26](./introspeccao.md#I26), [ST10](./storytelling.md#ST10) |
| RF27 | O sistema deve notificar aos usuários cadastrados na disciplina quando uma pergunta no fórum é cadastrada | [IT27](./introspeccao.md#I27) |
| RF28 | O sistema deve permitir fazer alteração nas informações do usuário cadastrado | [IT28](./introspeccao.md#I28) |
| RF29 | O sistema deve permitir que o professor visualize o tempo que os alunos utilizaram para a realização das atividades | [IT29](./introspeccao.md#I29) |
| RF30 | O sistema deve permitir enviar mensagem direta para um aluno/professor | [IT30](./introspeccao.md#I30), [ST07](./storytelling.md#ST07) |
| RF31 | O sistema deve permitir o aluno/professor fazer login | [IT31](./introspeccao.md#31), [OP02](./observacao_etnografia.md#OP02), [ST01](./storytelling.md#ST01) |
| RF32 | O sistema deve permitir o aluno/professor fazer logout | [IT32](./introspeccao.md#I32) |
| RF33 | O aluno deve ser capaz de ver a senha digitada | [OP03](./observacao_etnografia.md#OP03) |
| RF34 | O aluno deve ser capaz de recuperar a senha | [OP04](./observacao_etnografia.md#OP04) |
| RF35 | O sistema deverá emitir um email de recuperação de senha | [OP05](./observacao_etnografia.md#OP05) |
| RF36 | O aluno deve poder visualizar seus dados pessoais | [OP06](./observacao_etnografia.md#OP06) |
| RF37 | O aluno deve ser capaz de alterar sua imagem de perfil | [OP07](./observacao_etnografia.md#OP07) |
| RF38 | O aluno deve ser capaz de visualizar o status de um arquivo enviado | [OP20](./observacao_etnografia.md#OP20) |
| RF39 | O aluno deve ser capaz de pesquisar por cursos disponíveis | [OP08](./observacao_etnografia.md#OP08) |
| RF40 | O aluno deve ser capaz de visualizar o comentários de um arquivo enviado | [OP21](./observacao_etnografia.md#OP21) |
| RF41 | O aluno deve ser capaz de ingressar em um curso utilizando uma chave de acesso | [OP09](./observacao_etnografia.md#OP09) |
| RF42 | O aluno deve ser capaz de ver as restrições de envio de um arquivo | [OP22](./observacao_etnografia.md#OP22) |
| RF43 | O sistema deve emitir notificações ao aluno quando o prazo de alguma atividade estiver próximo | [OP11](./observacao_etnografia.md#OP11), [ST04](./storytelling.md#ST04) |
| RF44 | O aluno deve poder baixar diferentes tipos de arquivo disponibilizados pelo professor | [OP23](./observacao_etnografia.md#OP23), [ST03](./storytelling.md#ST03) |
| RF45 | O aluno deve ser capaz de marcar atividades como concluída | [OP12](./observacao_etnografia.md#OP12) |
| RF46 | O aluno deve poder visualizar a descrição de cada arquivo | [OP24](./observacao_etnografia.md#OP24) |
| RF47 | O aluno deve poder visualizar seu o progresso do aluno no curso | [OP13](./observacao_etnografia.md#OP13) |
| RF48 | O sistema deve ter diferentes ícones para diferentes tipos de atividades de um curso | [OP25](./observacao_etnografia.md#OP25) |
| RF49 | O aluno deve ser capaz de retroceder e avançar uma seção do curso | [OP14](./observacao_etnografia.md#OP14) |
| RF50 | O sistema deve mostrar o nome das seções anterior e posterior a seção em que o aluno se encontra | [OP15](./observacao_etnografia.md#OP15) |
| RF51 | O sistema deve mostrar o índice do curso completo | [OP16](./observacao_etnografia.md#OP16) |
| RF52 | O sistema deve deixar claro quando o aluno estiver saindo do aplicativo para acessar uma URL no navegador | [OP26](./observacao_etnografia.md#OP26) |
| RF53 | O aluno deve poder arquivar um curso | [OP31](./observacao_etnografia.md#OP31) |
| RF54 | O aluno deve ser capaz de fazer o download de um curso | [OP22](./observacao_etnografia.md#OP32) |
| RF55 | O aluno deve poder ver os próximos eventos de um curso | [OP27](./observacao_etnografia.md#OP27), [ST09](./storytelling.md#ST09) |
| RF56 | O aluno deve poder ver informações gerais sobre o curso | [OP33](./observacao_etnografia.md#OP33) |
| RF57 | O aluno deve poder favoritar um curso | [OP30](./observacao_etnografia.md#OP30) |
| RF58 | O professor deve ser capaz de criar restrições de tempo para as atividades | [ST19](./storytelling.md#ST19) |
| RF59 | O sistema deve mostrar os cursos mais recentes primeiro | [ST05](./storytelling.md#ST05) |
| RF60 | O aluno deve ser capaz de fazer a revisão da atividade finalizada | [ST24](./storytelling.md#ST24) |
| RF61 | O professor deve ser capaz de disponibilizar materiais(arquivos) no curso | [ST06](./storytelling.md#ST06) |
| RF62 | O professor deve ser capaz de cadastrar alunos na disciplina | [ST12](./storytelling.md#ST12) |
| RF63 | O professor deve ser capaz de organizar o curso em módulos | [ST08](./storytelling.md#ST08) |
| RF64 | O aluno deve ser capaz de configurar as preferências do aplicativo | [ST26](./storytelling.md#ST26) |
<figcaption align='center'>
    <b>Tabela de Requisitos Funcionais</b>
        <br><small>Autor: Marcos Vinícius e Pablo Christianno</small>
</figcaption>

### 3.3 Requisitos Não-Funcionais

| ID | Descrição | Origem |
|:--:|:---------:|:------:|
| RNF01 | O app deve ter suporte para aparelhos com sistema IOS e Android | [IT33](./introspeccao.md#I33), [ST22](./storytelling.md#ST22) |
| RNF02 | O app deve ser eficiente | [IT34](./introspeccao.md#I34) |
| RNF03 | O sistema deve estar disponível para uso do aluno a qualquer momento | [IT35](./introspeccao.md#I35) |
| RNF04 | O sistema deve manter todos os dados fornecidos pela instituição e pelo professor seguros | [IT36](./introspeccao.md#I36) |
| RNF05 | O sistema deve oferecer uma interface intuitiva e adaptável para o usuário. | [IT37](./introspeccao.md#I37) |
| RNF06 | O sistema deve apresentar as mesmas telas disponíveis no Aprender3 | [IT38](./introspeccao.md#I38) |
| RNF07 | O aluno somente poderá vincular o sistema com sua instituição de ensino através de um endereço eletrônico | [OP01](./observacao_etnografia.md#OP01) |
| RNF08 | O aluno deve permanecer logado no app até fazer logout | [ST25](./storytelling.md#ST25) |
<figcaption align='center'>
    <b>Tabela de Requisitos Não Funcionais</b>
        <br><small>Autor: Marcos Vinícius e Pablo Christianno</small>
</figcaption>

## 4. Referências

- [Documento de Requisitos Elicitados grupo Duolingo](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/RequisitosElicitados/)

## 5. Histórico de Versionamento

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 28/12/2022 | 01/01/2023 | Criação da página, introdução, metodologia e tabelas | Marcos e Pablo | - |
