# Casos de Uso

## 1. Introdução 
<p aling = justify> &emsp; &emsp;
    Caso de uso é uma técnica de modelagem de requisitos funcionais, através dela é capaz de representar  um conjunto de sequências de ações
    que o usuário é capaz de realizar no sistema seguindo um fluxo de eventos possíveis para atingir um determinado objetivo. Comumente 
    representado por um diagrama UML aonde se expõe seus elementos: atores, sistema, casos de uso e relacionamento. Entretanto é importante
    fazer uso de especificações de casos de uso, uma descrição complementar ao diagrama que trás mais detalhes sobre os casos de uso do 
    diagrama.
</p>

## 2. Participantes
*    Arthur Vinicius
*    Pablo Christianno

## 3. Diagrama UML de Casos de Uso

![imagem](../Assets/modelagem/Use_case.jpeg)

<center>
<h6 aling = 'center'>Figura 1: Diagrama de Caso de Uso</h6>
<h6 aling = 'center'>Fonte: Elaboração Própria</h6>
</center>

## 4. Especificação dos Casos de Uso

#### UC01 

| <b>UC01</b> | <b>Informações</b> |
|:---------------------:|----------------------------|
| Descrição         | O <b>Aluno</b> deve ser capaz de sincronizar o app com sua plataforma de ensino |
| Ator              | <b>Aluno</b> |
| Pré-condições     | Acesso à internet |
| frequência de uso | Eventual |
| Ação              | O <b>Aluno</b> acessar sua plataforma de ensino |
| Fluxo Principal   | <b>FP01</b>: Fluxo para fazer a Sincronização com o app</br>1. O ator entra no aplicativo.</br>2. Sistema exibe um campo para inserir endereço eletrônico e uma opção para sincronizar por QrCode.</br>3. Ator insere endereço eletrônico de sua plataforma de ensino.<br>4. Sistema faz a sincronização entre o app e a plataforma.  |
| Fluxo Alternativo | <b>FA01</b>: Fluxo para fazer a Sincronização com o app</br>1. O ator entra no aplicativo.</br>2. Sistema exibe um campo para inserir endereço eletrônico e uma opção para sincronizar por QrCode.</br>1. Ator escolhe sincronizar por QrCode.<br>4. Sistema abre o scaner de QrCode.</br>5. Ator aponta a camera do aparelho para o QrCode.</br>6. Sistema faz a sincronização entre o app e a plataforma. |
| Pós-Condição      | O Ator poderá acessar opção de login |
| Data de Criação   | 10/12/2022 |

<center>
<h6 aling = 'center'>tabela 1: Especificação de sincronização</h6>
<h6 aling = 'center'>Fonte: Elaboração Própria</h6>
</center>

#### UC02 

| <b>UC02</b> | <b>Informações</b> |
|:---------------------:|----------------------------|
| Descrição         | O <b>Aluno</b> realiza login |
| Ator              | <b>Aluno</b> |
| Pré-condições     | Acesso à internet, app está sincronizado e possuir conta |
| frequência de uso | Eventual |
| Ação              | O <b>Aluno</b> entrar na sua conta |
| Fluxo Principal   | <b>FP01</b>: Fluxo para fazer login</br>1. O ator entra no aplicativo.</br>2. O ator sincroniza o app com sua plataforma de ensino.</br>3. Sistema exibe dois campos, um de identificação e outro de senha.<br>4. Ator insere seus dados de login.</br>5. Ator aperta no botão de entrar.</br>5. Sistema Verifica dados. |
| Fluxo Alternativo | <b>FA01</b>: Fluxo para fazer login</br>1. O ator entra no aplicativo.</br>2. O ator sincroniza o app com sua plataforma de ensino.</br>3. Sistema exibe dois campos, um de identificação e outro de senha.<br>4. Ator insere seus dados de login errôneos.</br>5. Ator aperta no botão de entrar.</br>6. Sistema Verifica dados.</br>7. Sistema apresenta erro de login. |
| Pós-Condição      | O Ator terá acesso as funcionalidades de um usuário logado no sistema |
| Data de Criação   | 10/12/2022 |

<center>
<h6 aling = 'center'>tabela 2: Especificação de Login</h6>
<h6 aling = 'center'>Fonte: Elaboração Própria</h6>
</center>

#### UC03 

| <b>UC03</b> | <b>Informações</b> |
|:---------------------:|----------------------------|
| Descrição         | O <b>Aluno</b> pode se cadastrar em um curso |
| Ator              | <b>Aluno</b> |
| Pré-condições     | Acesso à internet e está logado |
| frequência de uso | Eventual |
| Ação              | O <b>Aluno</b> fazer cadastro em curso |
| Fluxo Principal   | <b>FP01</b>: Fluxo para fazer cadastro em um curso</br>1. Ator clica na ícone de lupa na parte superior direita.</br>2. O ator digita o nome do curso que deseja se cadastrar.</br>3. Sistema exibe o curso pesquisado.<br>4. Ator confere informações do curso.</br>5. Ator insere chave de acesso.</br>5. Sistema Verifica chave de acesso. |
| Fluxo Alternativo | <b>FA01</b>: Fluxo para fazer cadastro em um curso</br>1. Ator clica na ícone de lupa na parte superior direita.</br>2. O ator digita o nome do curso que deseja se cadastrar.</br>3. Sistema exibe o curso pesquisado.<br>4. Ator confere informações do curso.</br>5. Ator insere chave de acesso errada.</br>5. Sistema Verifica chave de acesso.<br>6. Sistema apresenta erro |
| Pós-Condição      | O Ator terá como acessar o ambiente virtual do curso no app|
| Data de Criação   | 10/12/2022 |

<center>
<h6 aling = 'center'>tabela 3: Especificação de Cadastro em Curso</h6>
<h6 aling = 'center'>Fonte: Elaboração Própria</h6>
</center>
 
## 5. Referências
https://www.devmedia.com.br/especificacao-de-casos-de-uso-na-pratica/18427
https://edisciplinas.usp.br/pluginfile.php/3720765/course/section/857581/Aula02_CasosDeUso.pdf

## 6. Histórico de Versionamento

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 10/12/2022 | 10/12/2022 | Estruturação e criação da página | Pablo Christianno e Arthur Vinicius | Delziron Braz |