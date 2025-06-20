# 🚀 Proposito do Projeto

O projeto desenvolvido pelos alunos do 2ºDSM da Fatec Jacareí, visando criar uma aplicação web que permite aos usuários acessar informações sobre áreas queimadas, riscos de incêndio e focos de calor, utilizando dados do Programa Queimadas do INPE. A ferramenta busca facilitar o acesso a esses importantes dados ambientais, contribuindo para o monitoramento e prevenção de incêndios no território brasileiro.

## 🌟 Visão Geral do Projeto
 
Este repositório visa **centralizar e organizar a documentação do time** para garantir a transparência, a comunicação e o alinhamento contínuo durante o ciclo de vida do projeto. Os documentos são **atualizados regularmente** para refletir as mudanças no escopo, nas metas de desenvolvimento e nas sprints.
 
 
🔍 **Aqui você encontrará:**
- Visão geral do projeto.
- Detalhamento das funcionalidades.
- Planejamento e progresso das sprints.
 
## 📂 Índice
 
1. [Product Backlog](Backlog/BackLog%20-%20V2.docx)
2. [Visual](Visual/)
3. [Uml](Uml/)
4. [Reunião](Reunião/)
5. [Burndown](Burndown/)
5. [Documentação de Teste](Documentacao/)  

## ⚠ Observação 

Este repositório tem como objetivo documentar todo o nosso projeto em desenvolvimento. Caso você queira acompanhar o progresso do nosso sistema, acesse o [repositório aqui](https://github.com/CodeGators/CodeGators---Front-Server). Lá estão disponíveis todos os arquivos do servidor.
 
 
 # 🛠 PRODUCT BACKLOG: 

<h2>REQUISITOS FUNCIONAIS</h2>
<table>
    <tr>
        <th>REQUISITO FUNCIONAL</th>
        <th>USER STORIES</th> 
    </tr>
    <tr>
        <td>RF.01</td>
        <td>Como usuário do site quero poder ter acesso ao banco de dados, para que eu possa visualizar o histórico das queimadas em determinados períodos de tempo;</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>Como professor de eng. de software, gostaria de visualizar os diagramas uml a fim de entender a modelagem do projeto;</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>Como usuário, eu gostaria de saber o foco de calor por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.04</td>
        <td>Como usuário do site, eu gostaria de saber o foco de calor por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.05</td>
        <td>Como usuário do site, eu gostaria de saber o risco de fogo por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.06</td>
        <td>Como usuário do site, eu gostaria de saber o risco de fogo por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.07</td>
        <td>Como usuário do site, eu gostaria de saber sobre as áreas queimadas por estado para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.08</td>
        <td> Como usuário do site, eu gostaria de saber sobre as áreas queimadas por bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.09</td>
        <td>Como usuário do site, eu gostaria de poder ver gráficos de foco de calor por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.10</td>
        <td>Como usuário do site, eu gostaria de poder ver gráficos de fogo por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.11</td>
        <td>Como usuário do site, eu gostaria de poder ver gráficos de área queimada por estado e bioma para fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.12</td>
        <td>Como usuário do site quero poder fazer consultas por intervalor de tempo a fins de pesquisa;</td>
    </tr>
    <tr>
        <td>RF.13</td>
        <td>Como usuário do site quero interagir com o site, respondendo a duas perguntas para fins de conhecimento; </td>
    </tr>
     <tr>
        <td>RF.14</td>
        <td>Criação da documentação do caso de testes; </td>
    </tr>
    </tr>
</table>


<h2>Equipe</h2>

<table>
    <tr>
        <th>Função</th>
        <th>Nome</th>
        <th>Github</th>
    </tr>
    <tr>
        <td>Scrum Master</td>
        <td>Stefan Souza Cruz</td>
        <td><a href=https://github.com/Stefan0212><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
    <tr>
        <td>Product Owner</td>
        <td>Arthur Augusto Da Silva Cunha</td> 
        <td><a href=https://github.com/ArthurAugusto10><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Gustavo Reis</td>
        <td><a href=https://github.com/GustavoReis-xml><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Filippe Gonçalves Marchezoni</td>
        <td><a href=https://github.com/FilippeGM><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Anderson Fontes</td>
        <td><a href=https://github.com/Anderson-Fontes><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
    <tr>
        <td>Developer</td>
        <td>Rafael Shinji Tomokame</td>
        <td><a href=https://github.com/RafaelShinjiTomokame><img src="imagens/github-logo.png" style="height:20px; width:20px;"></a></td>
    </tr>
</table>

# SPRINT 1 

Na primeira sprint, nosso principal objetivo foi criar o banco de dados do nosso site e o modelo visual utilizando a ferramenta Figma. Para alcançar esse objetivo, dividimos a nossa equipe de acordo com o nível de prioridade de cada tarefa e entendemos como equipe que a maior prioridade era deixar o ambiente do banco de dados pronto. O Scrum Master monitorou periodicamente o gráfico de burndown e, durante as reuniões diárias, verificou juntamente com a equipe como estava o andamento das tarefas. Buscamos atender a todos os requisitos que o Product Owner havia levantado, passando por sua validação.


<h2>SPRINT BACKLOG</h2>
<table>
    <tr>
        <th>REFERENCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSAVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>Criar ambiente do banco de dados</td>
        <td>Stefan,Anderson,Arthur</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>Criar os diagrams solicitados pelo professor</td>
        <td>Arthur</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>Fazer a consulta geoespacial</td>
        <td>Gustavo,Anderson</td>
        <td>✔</td>
    </tr>
    </tr>
</table>


# BURNDOWN

![Anotação 2024-10-03 221449](https://github.com/CodeGators/CodeGators---Documentacao/blob/main/imagens/sprint1.png)

# SPRINT RETROSPECTIVE

Nessa primeira sprint, percebemos algumas dificuldades no caminho, como a divisão de tarefas, atribuição de responsabilidades e desafios técnicos relacionados ao uso das ferramentas de trabalho (PostGIS, pgAdmin).
Entre os pontos positivos, destacamos a comunicação eficiente e o excelente entrosamento da nossa equipe, o que proporcionou um ambiente de trabalho mais tranquilo e com maior produtividade. Uma iniciativa que implementamos no projeto foi a realização de reuniões além do horário acadêmico, permitindo melhor organização e alinhamento entre os membros.

# SPRINT 2

Durante a segunda sprint, aprimoramos a estrutura do banco de dados e otimizamos a conexão com o backend, garantindo maior eficiência nas consultas. O frontend foi refinado, com melhorias visuais e de usabilidade. Implementamos a visualização de focos de calor diretamente no mapa, facilitando a análise espacial dos dados. Adicionamos também um gráfico interativo que exibe os focos de calor por estado. Esses avanços fortaleceram a integração entre as camadas do sistema e ampliaram a funcionalidade da aplicação.

<h2>SPRINT BACKLOG</h2>
<table>
    <tr>
        <th>REFERENCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSAVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>FAZER A CRIAÇÃO DO SISTEMA</td>
        <td>Stefan,Anderson</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>CONEXÃO COM O BANCO DE DADOS</td>
        <td>Arthur,Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>DIAGRAMA DE SEQUÊNCIA</td>
        <td>Rafael</td>
        <td>✔</td>
    </tr>
    </tr>
</table>

# BURNDOWN

![sprint2](https://github.com/user-attachments/assets/46ec3eb0-d596-4818-825f-bdc2f0d1f46e)



# SPRINT RETROSPECTIVE

Nesta segunda sprint, tivemos um desempenho bastante satisfatório em comparação com a anterior. Conseguimos evoluir significativamente na organização e na gestão do projeto, com avanços notáveis na definição de tarefas e na priorização das entregas. Durante o período, enfrentamos alguns desafios relacionados ao relacionamento entre membros da equipe. No entanto, conseguimos resolvê-los de maneira eficaz, sem que isso afetasse negativamente o progresso do desenvolvimento.

# SPRINT 3

Nesta última sprint, nosso foco foi implementar as funcionalidades de área queimada e focos de calor, além de estruturar o campo onde os gráficos são gerados. Trabalhamos para garantir que os dados apresentados estejam coerentes com as informações exibidas no mapa, validando as entradas e saídas do sistema. Também dedicamos atenção à melhoria visual da interface, buscando torná-la mais intuitiva, e realizamos ajustes de desempenho para tornar o sistema mais ágil e eficiente.

<h2>SPRINT BACKLOG</h2>
<table>
    <tr>
        <th>REFERENCIA</th>
        <th>REQUISITO DA SPRINT</th>
        <th>RESPONSAVEL</th>
        <th>CONCLUÍDA</th>
    </tr>
    <tr>
        <td>RF.01</td>
        <td>ALGORITMO  RECURSIVO</td>
        <td>Anderson, Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.02</td>
        <td>APLICAR OS DADOS</td>
        <td>Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.03</td>
        <td>ESTILIZAR INTERFACE</td>
        <td>Anderson</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.04</td>
        <td>ROTAS</td>
        <td>Gustavo</td>
        <td>✔</td>
    </tr>
    <tr>
        <td>RF.05</td>
        <td>CRIAR GRAFICOS</td>
        <td>Anderson, Gustavo</td>
        <td>✔</td>
    </tr>
    </tr>
</table>


# BURNDOWN

![Anotação 2024-10-03 221449](https://github.com/CodeGators/CodeGators---Documentacao/blob/main/imagens/sprint3.png)

# SPRINT RETROSPECTIVE

A sprint foi, de forma geral, bastante produtiva. A equipe demonstrou proatividade, boa comunicação e cooperação, o que facilitou o cumprimento das atividades e fortaleceu o trabalho em equipe. As reuniões de alinhamento contribuíram para uma gestão de tarefas mais clara, e o comprometimento da maioria dos integrantes possibilitou um bom ritmo de desenvolvimento e aprendizado coletivo. No entanto, também enfrentamos alguns pontos a melhorar, como a falta de comprometimento por parte de alguns membros, o não cumprimento de prazos e certa dificuldade de direcionamento em momentos-chave do projeto. Esses desafios mostraram a importância de manter todos alinhados desde o início da sprint e reforçar a responsabilidade individual para que os próximos ciclos sejam ainda mais eficientes.
