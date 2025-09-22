<h1 align="center"> API ADS 4º Semestre </h1>

<div align="center">
      <img src="docs/assets/Banner - projeto.png" alt="AdaTech" width="900">
<h2 align="center"> 🐙 Equipe Adalove </h2>
</div>

<div align="center">

|
<a href ="#desafio"> Desafio</a> |
<a href ="#mvp"> Solução</a> |
<a href ="#backlog"> Backlog do Produto</a> |
<a href ="#sprint"> Cronograma de Sprints</a> |
<a href ="#tecnologias"> Tecnologias </a> |

<!---a href ="#estrutura"> Estrutura do Projeto </a> |---->

<a href ="#dor"> DoR</a> |
<a href ="#dod"> DoD</a> |
<a href ="#manual"> Guia de Documentações</a> |
<a href ="#adateam"> Equipe </a>
|

</div>

<div align="center">
      <h3 align="center"> Status do Projeto: Em andamento! ⌛ </h2>
</div>

## 🏁 Desafio: <a id="desafio"></a>

O desafio consiste em criar um **agente de Inteligência Artificial** inovador capaz de automatizar a elaboração da instrução de registro aduaneiro, incorporando de forma inteligente dados críticos como Part-Number, classificação fiscal, fabricante, origem e endereço do fabricante. <br>
O processo manual de elaboração dessas instruções, frequentemente sujeito a erros humanos e retrabalho pode gerar riscos, além de consumir tempo da equipe responsável. <br>
A solução visa eliminar essas ineficiências, garantindo que a descrição do material seja precisa, sem ambiguidades, e em total conformidade com as exigências legais. <br>
Dessa forma, a Receita Federal terá uma compreensão clara do produto, evitando questionamentos, penalidades ou multas.

## 🫧 MVP (Minimal Viable Product) <a id="mvp"></a>

A solução para esse desafio é <b>AdaTech</b>, uma plataforma inovadora que automatiza a criação da instrução de registro aduaneiro, proporcionando uma experiência sem fricções e com precisão. <br>
o sistema integra, de forma eficiente, dados essenciais como Part-Number, classificação fiscal, fabricante e origem para gerar automaticamente uma descrição do produto que seja tanto clara quanto legalmente compatível.<br>
O que antes demandava tempo, foco e o risco de erros de interpretação, agora é feito de forma rápida, e com conformidade. <br>
Isso não apenas minimiza os riscos de penalidades, mas também libera a equipe para se concentrar em tarefas de maior valor agregado, acelerando o processo e aumentando a segurança nas transações aduaneiras.

## 🐙 Backlog do Produto

<a id="backlog"></a>

| Rank | Prioridade |                                                                            User Story                                                                            | Story Points | Sprint | Status |
| :--: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------: | :----: | :----: |
|  1   |    Alta    |        Como usuário final, quero fazer o upload de um PDF de um pedido de compra, para que o sistema extraia todos os Part-Numbers (P/Ns) contidos nele.         |      -       |   1    |   ⌛   |
|  2   |    Alta    |              Como analista de importação, quero que o sistema utilize uma IA, para sugerir o NCM e a descrição de cada item, exibindo o resultado.               |      -       |   1    |   ⌛   |
|  3   |    Alta    |                            Como contratante, quero poder gerar um arquivo Excel com os dados finais, para submeter à receita federal.                            |      -       |   1    |   ⌛   |
|  4   |    Alta    |            Como operador do sistema, quero ter um formulário, para revisar e corrigir as informações extraídas pela IA antes de finalizar o processo.            |      -       |   2    |   🔒   |
|  5   |    Alta    |                         Como desenvolvedor, quero substituir a IA externa por um agente local para garantir o controle sobre o processo.                         |      -       |   2    |   🔒   |
|  6   |   Média    |                      Como contratante, quero acessar o sistema através de uma tela de login para garantir a segurança dos dados da empresa.                      |      -       |   2    |   🔒   |
|  7   |   Média    | Como um analista de importação, quero ter acesso a um histórico que liste os PDFs já processados, para que eu possa consultar rapidamente resultados anteriores. |      -       |   3    |   🔒   |
|  8   |   Baixa    |                   Como desenvolvedor, quero produzir a documentação completa do sistema para facilitar o uso e possíveis manutenções futuras.                    |      -       |   3    |   🔒   |

## 🚣 DoR - Definition of Ready <a id="dor"></a>

**1. Critérios de Negócio:**

- A história escrita no formato padrão: "Como <tipo de usuário>, quero <objetivo>, para que
  <benefício>".
- O valor para o negócio está claro e foi compreendido pela equipe de desenvolvimento.
- A história foi priorizada pelo Product Owner (PO).

**2. Critérios de Funcionalidade e Design:**

- Os Critérios de Aceite estão definidos, são claros, concisos e testáveis.
- Para histórias que envolvem interface de usuário (como a tela de upload ), os wireframes ou
  mockups necessários foram apresentados à equipe.
- Quaisquer regras de negócio, lógicas ou cálculos específicos foram esclarecidos (ex: o formato
  esperado para a submissão à Receita Federal).

**3. Critérios Técnicos:**

- As dependências técnicas (externas ou internas, como APIs de terceiros para o Web Scraping)
  foram identificadas.
- A equipe de desenvolvimento realizou uma análise técnica inicial e não identificou impedimentos que
  bloqueiem o início do trabalho.
- As necessidades de dados para desenvolvimento e teste foram identificadas (ex: exemplos de PDFs
  de pedidos de compra para treinar ou validar a extração de P/Ns).

**4. Critérios de Processo:**

- As histórias foram discutidas e entendidas por toda a equipe de desenvolvimento.
- As histórias foram estimadas pela equipe de desenvolvimento.
- O tamanho estimado da história permite que ela seja concluída dentro de uma única Sprint.

## 🏝️ DoD - Definition of Done <a id="dod"></a>

- Criar tela de upload de PDF com drag-and-drop;
- Implementar extração do PartNumber;
- Avaliação de Modelos de IA para Extrair P/Ns;
- Web Scrapping do sistema funcionando;
- Possuir a sigestão de NCM;
- Gerar planilha Excel com dados extraídos.

---

## 📅 Cronograma de Sprints <a id="sprint"></a>

| Sprint          |    Período    | Relatório          |
| --------------- | :-----------: | ------------------ |
| ⌛ **SPRINT 1** | 08/09 - 28/09 | Em progresso       |
| 🔒 **SPRINT 2** | 06/10 - 26/10 | Ainda não iniciada |
| 🔒 **SPRINT 3** | 03/11 - 23/11 | Ainda não iniciada |

## ✨ Protótipo da Aplicação <a id="prototipo"></a>

<div align="center">
<table>
  <tr>
      <th> <img src="docs/assets/telas-figma/light-mode/Inicio%20-%20Light%20mode.png"> </th>
      <th> <img src = "docs/assets/telas-figma/light-mode/Criar%20conta-%20Light%20mode.png"> </th>
      <th> <img src = "docs/assets/telas-figma/light-mode/Tela%20Principal%20-%20Light%20mode.png"> </th>
      <th> <img src = "docs/assets/telas-figma/light-mode/Perfil%20-%20Light%20mode.png"> </th>
  </tr>
  <tr>
      <td> <img src="docs/assets/telas-figma/dark-mode/Inicio%20-%20Dark%20mode.png"></td>
      <td> <img src ="docs/assets/telas-figma/dark-mode/Criar%20conta%20-%20Dark%20mode.png"> </td>
      <td> <img src ="docs/assets/telas-figma/dark-mode/Tela%20Principal%20-%20%20Dark%20mode.png"> </td>
      <td> <img src ="docs/assets/telas-figma/dark-mode/Perfil%20-%20%20Dark%20mode.png"> </td>
  </tr>
</table>
</div>

## 🎥 Demonstração

<a id="demo"></a>

### Sprint 1:

https://github.com/user-attachments/assets/d0400ddc-ffbd-4138-b4df-976e3ecbf18e

---

## 🚢 Tecnologias

<a id="tecnologias"></a>

<div align="center">

![Ollama](https://img.shields.io/badge/-Ollama-0D1117?style=for-the-badge&logo=ollama&logoColor=white)
![DuckDuckGo](https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</h4>

</div>

## 📖 Guia de Documentações <a id="manual"></a>

[Guias do Usuário (Manual de Instalação e Utilização do AdaTech)](docs/manuais)

[Documentação Técnica](docs/documentacao)

## 🫧 AdaTeam

<a id="adateam"></a>

<div align="center">

|        Membro         |    Função     |                                                                          Github                                                                          |                                                                                         Linkedin                                                                                          |
| :-------------------: | :-----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Raphaela Monteiro   | Scrum Master  | <a href="https://github.com/raphaelamonteiro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |          <a href="https://www.linkedin.com/in/raphaelamonteiro/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>           |
|   Angelina Borroni    | Product Owner |    <a href="https://github.com/borroniff"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>     | <a href="https://www.linkedin.com/in/angelina-borroni-ferreira-833a4b301/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Matheus Germano    |   Dev Team    |    <a href="https://github.com/m-germano"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>     |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |
| Maria Fernanda Hansen |   Dev Team    |     <a href="https://github.com/Madhs31"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>      |   <a href="https://www.linkedin.com/in/maria-fernanda-diniz-0724122ba/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>    |
| Ramon Amorim da Silva |   Dev Team    |    <a href="https://github.com/ramonads42"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                   <a href="https://www.linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                   |
|     Renan Tomasi      |   Dev Team    |    <a href="https://github.com/renan21-tg"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |
|     Vitor Ribeiro     |   Dev Team    |  <a href="https://github.com/ribeirovitor04"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |

</div>

## ⚓ Cliente:

<a id="cliente"></a>

<div align="center">

|     Cliente      |                                                       |
| :--------------: | :---------------------------------------------------: |
| Creonice Honório | <a href='https://www.tecsysbrasil.com.br'>TecSys </a> |

</div>

## 🌊 Docentes:

<a id="docentes"></a>

<div align="center">

|                                   P²                                   |                                   M²                                   |
| :--------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| <a href='http://lattes.cnpq.br/1506784529918492'>Juliana Pasquini </a> | <a href='http://lattes.cnpq.br/4377240827813491'>Giuliano Bertoti </a> |

</div>
