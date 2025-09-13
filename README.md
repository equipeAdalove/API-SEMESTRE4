<h1 align="center"> API ADS 4º Semestre </h1>

<div align="center">
      <img src="docs/assets/Banner - projeto.png" alt="AdaTech" width="900">
<h2 align="center"> 🐙 Adalove </h2>
</div>

<div align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#mvp"> Solução</a>  |   
  <a href ="#backlog"> Backlog do Produto</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#sprint"> Cronograma de Sprints</a>  |
  <a href ="#tecnologias">Tecnologias</a> |
  <!---a href ="#manual">Manual de Instalação</a>  | --->
  <a href ="#adateam"> Equipe </a> |
</div>


<h1 align="center">

<div style="display: inline_block"><br>
  
<img align="center" alt="Raphs-Jira" height="50" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg">

<img align="center" alt="Raphs-Slack" height="50" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/slack/slack-original.svg">

<img align="center" alt="Raphs-HTML" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />

<img align="center" alt="Raphs-CSS" height="40" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">

<img align="center" alt="Raphs-TypeScript" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg">

<img align="center" alt="Raphs-React" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg">

<img align="center" alt="Raphs-Vite" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitejs/vitejs-original.svg">

<img align="center" alt="Raphs-Node" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg">
          
<img align="center" alt="Raphs-Python" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">

<img align="center" alt="Raphs-Ollama" height="40" width="40" src="https://github.com/ollama/ollama/assets/3325447/0d0b44e2-8f4a-4e99-9b52-a5c1c741c8f7">

<img align="center" alt="Raphs-Git" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg">

<img align="center" alt="Raphs-VsCode" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg">

<img align="center" alt="Raphs-Figma" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg">

</h1>

</div>

> Status do Projeto: Em andamento! ⌛
>
> Diretório de Documentação: [Link](docs) 📄

## 🏁 Desafio: <a id="desafio"></a>

O desafio proposto aos alunos da Fatec consiste no desenvolvimento de um agente de Inteligência
Artificial capaz de elaborar a instrução de registro aduaneiro com as informações pertinentes do
material que relacione: Part-Number, classificação fiscal, fabricante, origem do fabricante com
endereço completo, gerando a informação da descrição do material, de forma que permita a receita
federal entender o que é o produto e não gere dúvidas sobre o item o e não acarrete penalidades
e/ou multas sobre o material declarado.

## 🫧 MVP (Minimal Viable Product) <a id="mvp"></a>

<b> 💜 AdaTech </b> tem como objetivo automatizar a criação da instrução de registro aduaneiro, garantindo que ela seja clara, completa e em conformidade com as exigências legais.

---

<br>

## ✨ Protótipo da Aplicação

<a id="prototipo"></a>

<div align="center">
<table>
  <tr>
    <th> <img src = "https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Dark/Final%20-%20Dashboard%20(Dark).png"> </th>
    <th> <img src = "https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Dark/Final%20-%20Dashboard%20(Dark)%20(1).png"> </th>
    <th> <img src = "https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Dark/Final%20-%20NCM%20(Dark).png"> </th>
  </tr>
  <tr>
    <td> <img src ="https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Light/Final%20-%20Dashboard%20(Light).png"> </td>
    <td> <img src ="https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Light/Final%20-%20Dashboard%20(Light)%20(1).png"> </td>
    <td> <img src ="https://github.com/equipeAdalove/Front-API-SEMESTRE3/blob/Sprint-1/Prot%C3%B3tipo/Light/Final%20-%20NCM%20(Light).png"> </td>
  </tr>
</table>
</div>


## 🐙 Backlog do Produto
<a id="backlog"></a>


| Rank | Prioridade | User Story | Story Points | Sprint | Status |
| :--: | :-------: |  :------------------------------------------------------------------:  | :-------: | :----: | :----: | 
| 1 | Alta | Como usuário final, quero fazer o upload de um PDF de um pedido de compra, para que o sistema extraia todos os Part-Numbers (P/Ns) contidos nele. |  -  | 1 | ⌛ |
| 2 | Alta | Como analista de importação, quero que o sistema utilize uma IA, para sugerir o NCM e a descrição de cada item, exibindo o resultado. |  -  | 1 | ⌛ |
| 3 | Alta | Como contratante, quero poder gerar um arquivo Excel com os dados finais, para submeter à receita federal. |  -  | 1 | ⌛ |
| 4 | Alta | Como operador do sistema, quero ter um formulário, para revisar e corrigir as informações extraídas pela IA antes de finalizar o processo. |  -  | 2 | 🔒 |
| 5 | Alta | Como desenvolvedor, quero substituir a IA externa por um agente local para garantir o controle sobre o processo. |  -  | 2 | 🔒 |
| 6 | Média | Como contratante, quero acessar o sistema através de uma tela de login para garantir a segurança dos dados da empresa. |  -  | 2 | 🔒 |
| 7 | Média | Como um analista de importação, quero ter acesso a um histórico que liste os PDFs já processados, para que eu possa consultar rapidamente resultados anteriores. |  -  | 3 | 🔒 |
| 8 | Baixa | Como desenvolvedor, quero produzir a documentação completa do sistema para facilitar o uso e possíveis manutenções futuras. |  -  | 3 | 🔒 |



## ⚓ DoR - Definition of Ready <a id="dor"></a>

<!---
- User Stories com **Critérios de Aceitação**
- Subtarefas divididas **a partir das US**
- Design no **Figma**
- Modelagem do **Banco de Dados**
- Diagrama de **Rotas**
- Banco de Dados **Vetorizado** do Cliente
----->

## ⛵ DoD - Definition of Done <a id="dod"></a>
<!---
- Manual de Usuário
- Manual da Aplicação
- Documentação da API (Application Programming Interface)
- Código completo
- Vídeos de cada etapa de entrega

--->

---

## 📅 Cronograma de Sprints <a id="sprint"></a>

| Sprint          |    Período    | Relatório          |
| --------------- | :-----------: | ------------------ |
| ⌛ **SPRINT 1** | 08/09 - 28/09 | Em progresso       |
| 🔒 **SPRINT 2** | 06/10 - 26/10 | Ainda não iniciada |
| 🔒 **SPRINT 3** | 03/11 - 23/11 | Ainda não iniciada |

<!---[Sprint 1 Docs](./docs/processo/sprints/sprint-1/README.md)-->

## 🎥 Demonstração

<a id="demo"></a>

### 📂 Sprint 1:

https://github.com/user-attachments/assets/d0400ddc-ffbd-4138-b4df-976e3ecbf18e

---

<br>

<!----
## 📖 Manual de Instalação <a id="manual"></a>

### 🛠 Pré-requisitos

- Git ([Download](https://git-scm.com/downloads))

- Python 3.9+ ([Download](https://www.python.org/downloads/))

- Node.js 16+ ([Download](https://nodejs.org/en/download))

- Poetry (opcional para o backend) ([Download](https://python-poetry.org/))

---

### 1. Clonar o Repositório Principal

```bash
git clone --recurse-submodules https://github.com/BuzzTech-API/API_ADS_6SEMESTE_2025.1.git
cd API_ADS_6SEMESTE_2025.1
```

> **Observação:** Se já tiver clonado sem os submódulos, execute:

```
git submodule update --init --recursive
```

---

### 2. Configuração do Backend (auxia-backend)

**1° Adicione as variáveis no .env**

**2° Inicialize o Banco de dados MongoDB no localhost:**

**3° Coloque a base de dados vetorizada ./client dentro da raíz do backen:**

**4° Instale e Inicie a aplicação:**

**Opção A: Com Poetry**

```bash
cd ./auxia-backend
poetry shell
poetry install
make run
```

**Opção B: Com Ambiente Virtual Python**

```bash
cd ./auxia-backend
python3 -m venv venv
source venv/bin/activate # se você usa linux
venv/Scripts/activate 	 # se você usa windows
pip install -r requirements.txt
fastapi dev ./auxia/main.py
```

**Saída Esperada:**
<br>
Servidor rodando em `http://localhost:8000` (acesse `http://localhost:8000/docs` para a UI do Swagger).

---

### 3. Configuração do Frontend (auxia-frontend)

```bash
cd ../auxia-frontend/auxia
npm install
npm run dev
```

**Saída Esperada:**
<br>
Frontend rodando em `http://localhost:5173`.
------>

## 🫧 AdaTeam

<a id="adateam"></a>


|        Membro         |    Função     |                                                                          Github                                                                          |                                                                                         Linkedin                                                                                          |
| :-------------------: | :-----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   Raphaela Monteiro   | Scrum Master  | <a href="https://github.com/raphaelamonteiro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> |          <a href="https://www.linkedin.com/in/raphaelamonteiro/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>           |
|   Angelina Borroni    | Product Owner |    <a href="https://github.com/borroniff"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>     | <a href="https://www.linkedin.com/in/angelina-borroni-ferreira-833a4b301/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
|    Matheus Germano    |   Dev Team    |    <a href="https://github.com/m-germano"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>     |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |
| Maria Fernanda Hansen |   Dev Team    |     <a href="https://github.com/Madhs31"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>      |   <a href="https://www.linkedin.com/in/maria-fernanda-diniz-0724122ba/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>    |
| Ramon Amorim da Silva |   Dev Team    |    <a href="https://github.com/ramonads42"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                   <a href="https://www.linkedin.com/in/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                   |
|     Renan Tomasi      |   Dev Team    |    <a href="https://github.com/renan21-tg"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>    |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |
|     Vitor Ribeiro     |   Dev Team    |  <a href="https://github.com/ribeirovitor04"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  |                                 <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>                                 |

<br>


## 🐬 Cliente: 
<a id="cliente"></a>

| Cliente              |        |
| :-------------------: | :-----------: |
| Creonice Honório | <a href='https://www.tecsysbrasil.com.br'>TecSys </a> |


## 🌊 Docentes: 
<a id="docentes"></a>

| P²              | M²       |
| :-------------------: | :-----------: |
| <a href='http://lattes.cnpq.br/1506784529918492'>Juliana Pasquini </a> | <a href='http://lattes.cnpq.br/4377240827813491'>Giuliano Bertoti </a> |



</div>
