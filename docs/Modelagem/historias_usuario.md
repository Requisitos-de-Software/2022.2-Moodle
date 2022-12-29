# Histórias de usuário

## 1. Introdução

<p align = "justify"> &emsp;&emsp; Uma história do usuário é uma explicação informal e geral sobre um recurso de software escrita a partir da perspectiva do usuário final. Seu objetivo é articular como um recurso de software pode gerar valor para o cliente.</p>


## 2. Metodologia

&emsp;&emsp; De forma a manter um formato padronizado, a estrutura das histórias de usuário seguirá um padrão conhecido como "expressão da história do usuário" ou "voz do usuário" ou "cartão (card)".

| ID | HUYY  |
|-----|--------|
| Nome | Nome da história. |
| Descrição | Descrição da História de Usuário no formato: "Eu, como [usuário] quero [objetivo] para [finalidade]. |
| Critérios de Aceitação | Critérios complementares que servirão como suporte em uma futura validação da história.|
| Rastreabilidade | Quais [requisitos](../Elicitacao/requisitos.md#requisitos) deram origem para a história.| 

&emsp;&emsp; Para a validação das Histórias de Usuário, foi realizada uma reunião com um usuário real. </p>

## 3. Épicos

<b>Legenda:</b>

- E: Épico.

| Épico | Descrição | Funcionalidades |
| ------| --------- | -------- |
| E01 - Login | Engloba toda as funcionalidades ligadas a login e logout | -> Login <br/> -> Logout  |
| E02 - Perfil | Abrange toda a parte de informações do usuário e configurações da aplicação. | -> Perfil <br/> -> [Preferências](../Modelagem/lexicos.md#preferencias)  | 
| E03 - Disciplina | Inclui todas as funcionalidades ligadas à disciplina. | -> Gerenciar  <br/> -> Atividade <br/> Evento |
| E04 - Mensagens | Reúne todas as funcionalidades relacionadas à mensagens. | -> Mensagem <br/> -> Fórum <br/> -> Notificações |

## 4. Funcionalidades

### Funcionalidade 01 - Login

| ID | HU01  |
|-----|--------|
| Nome | Fazer login. |
| Descrição | Eu, como aluno, desejo fazer login para ter acesso às funcionalidades completas do aplicativo. |
| Critérios de Aceitação |  -> Entrada da identificação/email e senha <br/> -> Opção para logar com QR code <br/> -> Apresentar uma mensagem de erro caso os dados esejam incorretos |
| Rastreabilidade | RF31 |
<figcaption align='center'>
    <b>Tabela história de usuário 01</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU02  |
|-----|--------|
| Nome | Esqueceu a senha. |
| Descrição | Eu, como aluno, desejo conseguir redefinir a senha para que não tenha problemas caso esqueça. |
| Critérios de Aceitação |  -> Opção "esqueci a senha" <br/> -> Campo de entrada para o usuário preencher com o email <br/> -> Apresentar uma mensagem de erro caso o email esteja incorreto |
| Rastreabilidade | RF34 e RF35 |
<figcaption align='center'>
    <b>Tabela história de usuário 02</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

### Funcionalidade 02 - Logout

| ID | HU03  |
|-----|--------|
| Nome | Fazer logout. |
| Descrição | Eu, como aluno, desejo fazer logout do aplicativo para meus dados não estejam mais vinculados no dispositivo. |
| Critérios de Aceitação |  -> Opção para deslogar da conta no aplicativo <br/> -> Dados do usuário não aparecerem mais no aplicativo após o logout  |
| Rastreabilidade | RF32 |
<figcaption align='center'>
    <b>Tabela história de usuário 03</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

### Funcionalidade 03 - Perfil

| ID | HU04  |
|-----|--------|
| Nome | Mudar imagem de perfil |
| Descrição | Eu, como aluno, desejo alterar minha imagem de perfil para que meus professores me reconheçam mais facilmente. |
| Critérios de Aceitação |  -> Opção para alterar a imagem de perfil <br/> -> Aceitar somente imagens .png e .jpg |
| Rastreabilidade | RF37 |
<figcaption align='center'>
    <b>Tabela história de usuário 05</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU05  |
|-----|--------|
| Nome | Visualizar dados pessoais |
| Descrição | Eu, como aluno, desejo visualizar os meus dados pessoais para checar se está tudo em ordem. |
| Critérios de Aceitação |  -> Opção para visualizar os dados do perfil <br/> -> Apresentar todas as informações do perfil do usuário |
| Rastreabilidade | RF36 |
<figcaption align='center'>
    <b>Tabela história de usuário 05</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU06  |
|-----|--------|
| Nome | Alterar dados pessoais |
| Descrição | Eu, como aluno, desejo alterar meus dados pessoais para manter meu perfil sempre atualizado. |
| Critérios de Aceitação |  -> Ser possível alterar todas informações pessoais  |
| Rastreabilidade | RF28 |
<figcaption align='center'>
    <b>Tabela história de usuário 06</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

### Funcionalidade 04 - Preferências

| ID | HU07  |
|-----|--------|
| Nome | Alterar as [preferências](../Modelagem/lexicos.md#preferencias) |
| Descrição | Eu, como aluno, desejo alterar minhas [preferências](../Modelagem/lexicos.md#preferencias) para que o aplicativo esteja de acordo com meus gostos. |
| Critérios de Aceitação |  -> Ser possível configurar as notificações <br/> -> Ser possível configurar as mensagens <br/> -> Ser possível gerenciar dowloads |
| Rastreabilidade | RF64 |
<figcaption align='center'>
    <b>Tabela história de usuário 07</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

### Funcionalidade 05 - Gerenciamento Disciplina

| ID | HU08  |
|-----|--------|
| Nome | Cadastrar disciplina |
| Descrição | Eu, como professor, desejo cadastrar minha disciplina para facilitar a organização. |
| Critérios de Aceitação |  -> Ser possível cadastrar a disciplina desejada <br/> -> Ser possível cadastrar uma chave de acesso para a disciplina |
| Rastreabilidade | RF03 e RF40 |
<figcaption align='center'>
    <b>Tabela história de usuário 08</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU09  |
|-----|--------|
| Nome | Visualizar disciplinas cadastradas |
| Descrição | Eu, como aluno, desejo conseguir visualizar todas as disciplinas cadastradas para ter uma noção do tamanho da minha universidade. |
| Critérios de Aceitação |  -> Ser possível visualizar uma lista de todas as disciplinas cadastradas pelos professores |
| Rastreabilidade | RF07 e RF25 |
<figcaption align='center'>
    <b>Tabela história de usuário 09</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU10  |
|-----|--------|
| Nome | Cadastrar aluno na disciplina |
| Descrição | Eu, como professor, desejo cadastrar alunos na minha disciplina para facilitar o planejamento do meu curso. |
| Critérios de Aceitação |  -> Ser possível cadastrar um aluno na disciplina pelo nome <br/> -> Ser possível cadastrar um aluno na disciplina pela matrícula |
| Rastreabilidade | RF62 |
<figcaption align='center'>
    <b>Tabela história de usuário 10</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU11  |
|-----|--------|
| Nome | Pesquisar disciplina |
| Descrição | Eu, como aluno, desejo pesquisar por uma disciplina específica pelo nome dela ou do professor para facilitar encontrar a mesma. |
| Critérios de Aceitação |  -> Ser possível buscar uma disciplina pelo nome dela <br/> -> Ser possível buscar uma disciplina pelo nome do professor responsável pela mesma |
| Rastreabilidade | RF08 e RF09 |
<figcaption align='center'>
    <b>Tabela história de usuário 11</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU12  |
|-----|--------|
| Nome | Controlar o que os alunos podem fazer na disciplina |
| Descrição | Eu, como professor, desejo controlar as permissões que os alunos tem na minha disciplina para não ter nenhum problema. |
| Critérios de Aceitação |  -> Ser possível retirar um aluno da disciplina <br/> -> Ser possível alterar o cargo de um aluno na disciplina <br/> -> Ser possível listar as disciplinas que um aluno se cadastrou |
| Rastreabilidade | RF13, RF24 e RF25 |
<figcaption align='center'>
    <b>Tabela história de usuário 12</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

### Funcionalidade 06 - Atividades

| ID | HU13  |
|-----|--------|
| Nome | Cadastrar atividade |
| Descrição | Eu, como professor, cadastrar atividades para avaliar meus alunos de alguma maneira. |
| Critérios de Aceitação |  -> Ser possível criar restrições de acesso <br/> -> Ser possível criar limite de tentativa <br/> -> Ser possível criar limite de data de envio |
| Rastreabilidade | RF05, RF14, RF15, RF16 |
<figcaption align='center'>
    <b>Tabela história de usuário 13</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU14  |
|-----|--------|
| Nome | Consultar nota da atividade |
| Descrição | Eu, como aluno, desejo visualizar as notas das atividades para ter noção do meu desempenho. |
| Critérios de Aceitação |  -> Ser possível visualizar a nota da atividade  |
| Rastreabilidade | RF11 |
<figcaption align='center'>
    <b>Tabela história de usuário 14</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU15  |
|-----|--------|
| Nome | Enviar arquivos na atividade |
| Descrição | Eu, como aluno, desejo enviar arquivos em diversos formatos nas atividades para ter mais conforto ao responder as questões. |
| Critérios de Aceitação |  -> Ser possível enviar arquivos nos seguintes formatos: <br/>  .png <br/>  .pdf <br/> .doc <br/> .jpg |
| Rastreabilidade | RF12 |
<figcaption align='center'>
    <b>Tabela história de usuário 15</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU16  |
|-----|--------|
| Nome | Marcar atividade como concluída |
| Descrição | Eu, como aluno, desejo conseguir marcar atividades como concluídas para ter mais controle sobre as atividades que já fiz. |
| Critérios de Aceitação |  -> Ser possível marcar uma atividade como concluída |
| Rastreabilidade | RF45 |
<figcaption align='center'>
    <b>Tabela história de usuário 16</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption> 

| ID | HU17  |
|-----|--------|
| Nome | Fazer revisão de uma atividade |
| Descrição | Eu, como aluno, desejo conseguir revisar as minhas respostas após serem corrigidas para saber onde errei nas atividades. |
| Critérios de Aceitação |  -> Ser possível visualizar todas as questões com a correção das mesmas |
| Rastreabilidade | RF60 |
<figcaption align='center'>
    <b>Tabela história de usuário 17</b>
        <br><small>Autor: Marcos Vinícius</small>
</figcaption>

### Funcionalidade 07 - Mensagem

| ID | HU18  |
|-----|--------|
| Nome | Enviar mensagem direta |
| Descrição | Eu, como aluno/professor, desejo enviar mensagem direta a outro usuário, para poder me comunicar de forma privada dentro do aplicativo. |
| Critérios de Aceitação |  -> Ser possível enviar mensagem para qualquer usuário acessível |
| Rastreabilidade | RF30 |
<figcaption align='center'>
    <b>Tabela história de usuário 18</b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

### Funcionalidade 08 - Evento

| ID | HU24  |
|-----|--------|
| Nome | Visualizar próximos eventos de um curso |
| Descrição | Eu, como aluno, desejo visualizar próximos eventos de um curso, para estar ciente e me preparar para os mesmos. |
| Critérios de Aceitação |  -> visualizar todos os próximos eventos de um curso <br/> -> Visualizar a data de cada evento, se houver |
| Rastreabilidade | RF55 |
<figcaption align='center'>
    <b>Tabela história de usuário 24 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

### Funcionalidade 09 - Fórum

| ID | HU19  |
|-----|--------|
| Nome | Criar Fórum |
| Descrição | Eu, como professor, desejo criar um fórum, para que os alunos possam contribuir em dúvidas de outros alunos. |
| Critérios de Aceitação |  -> Ser possível criar um fórum dentro do ambiente de um curso |
| Rastreabilidade | RF17 |
<figcaption align='center'>
    <b>Tabela história de usuário 17 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

| ID | HU20  |
|-----|--------|
| Nome | Cadastrar pergunta no Fórum |
| Descrição | Eu, como aluno/professor, desejo cadastrar uma pergunta no fórum, para que outros usuários possa respondê-la. |
| Critérios de Aceitação |  -> Ser possível adicionar um tópico de discussão <br/> -> Existir um campo para cadastrar o título da pergunta  |
| Rastreabilidade | RF18 |
<figcaption align='center'>
    <b>Tabela história de usuário 20 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

| ID | HU21  |
|-----|--------|
| Nome | Responder pergunta no fórum |
| Descrição | Eu, como aluno/professor, desejo responder uma pergunta no fórum, para auxiliar o usuário que a enviou. |
| Critérios de Aceitação |  -> Ser escolher uma pergunta específica <br/> -> ser possível editar minha mensagem antes de enviá-la <br/> -> ser possível inerir um arquivo na resposta |
| Rastreabilidade | RF20, RF21 |
<figcaption align='center'>
    <b>Tabela história de usuário 21 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

### Funcionalidade 10 - Notificações

| ID | HU22  |
|-----|--------|
| Nome | Receber notificação de perguntas cadastradas em um fórum |
| Descrição | Eu, como aluno/professor, desejo receber notificação quando uma nova pergunta for cadastrada em um fórum, para saber rapidamente que há uma nova pergunta no fórum. |
| Critérios de Aceitação |  -> Notificação ser recebida <br/> -> Ser possível saber o que está sendo notificado |
| Rastreabilidade | RF27 |
<figcaption align='center'>
    <b>Tabela história de usuário 22 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>

| ID | HU23  |
|-----|--------|
| Nome | Receber notificação de atividades próximas ao prazo de vencimento |
| Descrição | Eu, como aluno, desejo receber notificação quando uma atividade estiver próxima do seu prazo de vencimento, para relembrar de enviar a atividade. |
| Critérios de Aceitação |  -> Notificação ser recebida <br/> -> Ser possível saber o que está sendo notificado |
| Rastreabilidade | RF43 |
<figcaption align='center'>
    <b>Tabela história de usuário 23 </b>
        <br><small>Autor: Pablo Christianno</small>
</figcaption>


## 5. Referências

- https://aprender3.unb.br/pluginfile.php/2307525/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf

- https://www.atlassian.com/br/agile/project-management/user-stories

## 6.Histórico de versão

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 27/12/2022 | 01/01/2023 | Criação da página e adição da introdução | Marcos Vinícius | Pablo Christianno |
| 1.1    | 28/12/2022 | 01/01/2023 | Adição dos épicos e estrutura das histórias | Marcos Vinícius | Pablo Christianno |
| 1.2    | 28/12/2022 | 01/01/2023 | Adição de 17 histórias de usuário | Marcos Vinícius | Pablo Christianno |
| 1.3    | 29/12/2022 | 01/01/2023 | Adição de 7 histórias de usuário | Pablo Christianno | Marcos Vinícius |
