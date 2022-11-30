# First Things First

## 1. Introdução

Priorização de requisitos é um processo realizado após elicitar os requisitos, com o intuito de organizar o escopo do projeto e definir um ponto de partida de forma a gerar valor ao cliente desde o inicio do desenvolvimento.
Nessa seção vai ser apresentado a técnica First Thing First de priorização de requisitos.

## 2. Metodologia
O metodo First Thing First tem como objetivo equilibrar os benefícios de cada função contra seus custos, definir as implicações que serão acarretadas na arquitetura, alinhar requisitos e regras de negócio,
estabelecer risco técnico e dificuldades associadas a um requsitos e, estabelecer a granularidade na qual priorizar os requsitos.

Esse processo é realizado através de 7 passos descritos a seguir:

***Passo 1***: Fazer uma lista dos requisitos, colocando apenas os principais, caso haja requisitos que são logicamente ligados, isto é, se um requisito B só é implementado caso A também seja, então somente A aparece na lista.

***Passo 2***: Com a participação do cliente, estimar o benefício relativo para cada um dos requisitos, em uma escala de 1 a 9.

***Passo 3***: Estimar, também com o cliente, na escala de 1 a 9, a penalidade/desvantagem de não aplicar o requisito.

***Passo 4***: Criar a coluna Valor Total, sendo esse Valor a soma entre a multiplicação do benefício relativo com peso relativo e a multiplicação da penalidade relativa com o peso relativo. A princípio, os pesos podem ser iguais.

***Passo 5***: Estimar o custo relativo para implementar o requisito na escala de 1 a 9. Feita pelos desenvolvedores.

***Passo 6***: Estimar o risco relativo de um requisito na escala de 1 a 9. Basicamente, quanto mais a escala, mais esforço, disponibilidade e uso de ferramentas ainda desconhecidas serão usados.

***Passo 7***: Calcular a prioridade para cada requisito usando a fórmula: ***valor% / (custo% * pesoCusto + riscos% * pesoRisco)***

## 3. First Thing First

## 4. Referências

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2307479/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf Acesso em: 30 nov. 2022.
## 5. Versionamento

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 30/11/2022 | 30/11/2022 | Criando arquivo da técnica FTF de priorização de requisitos | Artur Vinicius | Rodolfo Cabral |
