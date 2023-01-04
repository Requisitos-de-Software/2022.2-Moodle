# NFR Framework

## 1. Introdução
<p align = "justify">&emsp;&emsp; O NFR Framework é uma abordagem para representar e analisar Requisitos Não-Funcionais. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão. Tais características incluem Requisitos Não-funcionais, Requisitos funcionais, prioridades e carga de trabalho.
O funcionamento do NFR framework pode ser visualizado em termos da construção, elaboração, análise e revisão incremental e interativa de um gráfico de interdependência de softgoalconhecido como "Softgoal Interdependency Graph (SIG)". </p>

## 2. Metodologia

### 2.1 Softgoals
<p align = "justify">&emsp;&emsp;Os softgoals são utilizados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de um softgoal em outro. O Framework também possui um método de análise qualitativa para decidir os status dossoftgoals, dado que outros softgoals relacionados foram ou não satisfeitos.</p>

 * Softgoals NFR: Representam requisitos não funcionais
 * Softgoals de Operacionalização: Representam soluções de implementação para satisfazer softgoals NFR ou outras softgoals de operacionalização
 * Softgoals de Afirmação: Justificativas para apioar ou negar a forma como softgoals são priorizados

<center>
![Softgoals](https://user-images.githubusercontent.com/79341819/210648823-5255ce23-972f-4db4-a982-92f49f3188b2.png)
</center>

<figcaption align='center'>
    <b>Figura 1: Representação gráfica softgoals</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

### 2.2 Interdepêndencias

<p align = "justify">&emsp;&emsp; As interdependências definem as relações entre os softgoals. Os tipos de interdependências utilizadas pelo framework são os refinamentos e as contribuições.</p>

#### 2.2.1 Refinamento
<p align = "justify">&emsp;&emsp; Os refinamentos definem um tipo de interdependência que ocorre de cima para baixo (TOP-DOWN), onde um softgoal ascendente (pai) produz um ou mais softgoals descendentes (filhos) e estes se relacionam com o ascendente. Os tipos de refinamento são: decomposição, operacionalização e afirmação. </p>
<p align = "justify">&emsp;&emsp;As decomposições têm o objetivo de refinar softgoals para obter softgoals mais especializados e estes possam auxiliar na construção do projeto. Os quatro tipos de decomposições utilizadas pelo NFR Framework são descritos a seguir: </p>

 * Decomposição de Softgoal NFR
 * Decomposição de Operacionalização
 * Decomposição de Afirmação (Claims)
 * Priorização

<center>
![decomposições](https://user-images.githubusercontent.com/79341819/210650078-e8bffa80-e5c7-4131-bf4b-6787101713a5.png)
</center>

<figcaption align='center'>
    <b>Figura 2: Representação gráfica tipos de decomposição</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

#### 2.2.2 Contribuições
  
<p align = "justify">&emsp;&emsp; No NFR framework é possível a utilização de diversos tipos de contribuições que descrevem como a satisfação ou não de um softgoal descendente contribui para a satisfação do softgoal ascendente. A seguir apresentamos os tipos de contribuição utilizadas pelo framework: </p>

* **AND**: Caso os softgoals descendentes sejam satisfeitos, serão também os ascendentes.
* **OR**: Caso algum softgoal descendentes seja satisfeitos, será também os ascendente.
* **MAKE (++)**: Caso o softgoal descendente for suficientemente satisfeito, será também o
ascendente, porém, a contribuição é fornecida como suficientemente positiva concebida no
nível mais alto de satisfação.
* **HELP (+)**: Caso o softgoal descendente seja parcialmente satisfeito, será parcialmente
satisfeito o ascendente.
* **HURT (-)**: Caso o softgoal descendente seja satisfeito, o softgoal ascendente será
parcialmente negado.
* **UNKOWNN(?)**: Fornece uma contribuição desconhecida entre um softgoal descendente e um softgoal ascendente, podendo ser tanto positiva quanto negativa.
* **BREAK(--)**: Fornece uma contribuição suficientemente negativa (BREAK) entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de negação. Portanto, ao utilizar BREAK, se o softgoal descendente for suficientemente satisfeito o softgoal pai será negado, ou seja não será satisfeito.
* **EQUALS**: Determina que o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito e que softgoal descendente será negado se o softgoal ascendente for negado.
* **SOME** É utilizada quando o sinal da contribuição é conhecido (positivo ou negativo), mas a extensão (parcial ou total) não é. Nesses casos, quando há alguma incerteza em se utilizar HELP ou MAKE deve-se utilizar o tipo de contribuição SOME +. Da mesma forma quando não há certeza em se utilizar HURT ou BREAK deve-se utilizar SOME -.

### 2.3 Rótulos
<p>&emsp;&emsp;Os rótulos são graus de satisfação, determinados a partir de um processo de avaliação.</p>


<center>
![Screenshot_3](https://user-images.githubusercontent.com/79341819/210652899-5fb0d146-fc9a-43d2-b51b-1b83fe9f77d1.png)
</center>

<figcaption align='center'>
    <b>Figura 3: Representação gráfica rótulos</b>
    <br><small>Fonte: (CHUNG et al., 2000)</small>
</figcaption>

## 3. Gráficos de Interdependência de Softgoals (SIG)
&emsp;&emsp; Os gráficos a seguir foram dispostos conforme a metodologia FURPS+ definida na [Especificação Suplementar](./suplementar.md), como podemos ver abaixo:


### 3.1 SIG de Usabilidade

<center>
![Diagrama em branco](https://user-images.githubusercontent.com/79341819/210658717-73887e97-1f57-40a5-95dc-9f41e8aac278.png)
</center>

<figcaption align='center'>
    <b>Figura 4: SIG de Usabilidade</b>
    <br><small>Fonte: Elaboração Própria (Davi Lima)</small>
</figcaption>

### 3.1.1 SIG de Usabilidade com propagação

<center>
![Screenshot_5](https://user-images.githubusercontent.com/79341819/210659515-ec6f092f-2bf4-4041-9625-518a8bb21cff.png)
</center>

<figcaption align='center'>
    <b>Figura 5: SIG de Usabilidade com propagação</b>
    <br><small>Fonte: Elaboração Própria (Davi Lima)</small>
</figcaption>

### 3.2 SIG de Confiabilidade

<center>
![Diagrama em branco (1)](https://user-images.githubusercontent.com/79341819/210661837-f0def9e4-7eaf-430e-b3a3-78118620fdcc.png)
</center>

<figcaption align='center'>
    <b>Figura 6: SIG de confiabilidade</b>
    <br><small>Fonte: Elaboração Própria (Davi Lima)</small>
</figcaption>

### 3.2.1 SIG de Confiabilidade com propagação

<center>
![Screenshot_6](https://user-images.githubusercontent.com/79341819/210665731-fe0978a6-cb34-454c-b362-89bfca2ae95b.png)
</center>

<figcaption align='center'>
    <b>Figura 7: SIG de confiabilidade com propagação</b>
    <br><small>Fonte: Elaboração Própria (Davi Lima)</small>
</figcaption>

### 3.3 SIG de Desempenho

<center>
![Diagrama em branco (2)](https://user-images.githubusercontent.com/79341819/210663331-18a8d95c-d2cd-4b6e-aaa6-17415c039a60.png)
</center>

<figcaption align='center'>
    <b>Figura 8: SIG de Desempenho</b>
    <br><small>Fonte: Elaboração Própria (Delziron Braz)</small>
</figcaption>

### 3.3.1 SIG de Desempenho com propagação

<center>
![Screenshot_7](https://user-images.githubusercontent.com/79341819/210666104-c1fd2fb2-3682-4051-ad03-59dad15a68d3.png)
</center>

<figcaption align='center'>
    <b>Figura 9: SIG de Desempenho com propagação</b>
    <br><small>Fonte: Elaboração Própria (Delziron Braz)</small>
</figcaption>

### 3.3 SIG de Suportabilidade

<center>
![Diagrama em branco (3)](https://user-images.githubusercontent.com/79341819/210665127-d4b007db-a08a-4f60-b32d-915f123b4f4d.png)
</center>

<figcaption align='center'>
    <b>Figura 10: SIG de Suportabilidade</b>
    <br><small>Fonte: Elaboração Própria (Delziron Braz)</small>
</figcaption>

### 3.3.1 SIG de Suportabilidade com propagação

<center>
![Screenshot_8](https://user-images.githubusercontent.com/79341819/210666361-5b89d67c-2c6f-4467-bc1a-a580ee8edfa3.png)
</center>

<figcaption align='center'>
    <b>Figura 11: SIG de Suportabilidade com propagação (Delziron Braz)</b>
    <br><small>Fonte: Elaboração Própria</small>
</figcaption>


## 4 Referências
- NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados [Reinaldo Antônio da Silva; Universidade Federal de Pernambuco; 2019]

## 5 Histórico de Versão

| Versão | Data da realização | Data prevista revisão | Descrição | Autor | Revisor |
|--------|------|------|-----------|-------|---------|
| 1.0    | 04/01/2023 | 04/01/2023 | Criação do documento | Davi Lima | Delziron Braz |
| 1.1    | 04/01/2023 | 04/01/2023 | Adição dos tópicos, referencias e  versionamento  | Davi Lima | Delziron Braz |
