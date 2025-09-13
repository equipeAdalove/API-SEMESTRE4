# API 4º Semestre ADS

# TecSys - AdaTech

<p align="center">
      <img src="docs/Img/logo-BuzzTech.png" alt="logo da Buzz Tech" width="200">
      <h2 align="center"> Buzz Tech</h2>
</p>

<p align="center">
  | <a href ="#desafio"> Desafio</a>  |
  <a href ="#mvp"> Solução</a>  |   
  <a href ="#backlog"> Backlog do Produto</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#sprint"> Cronograma de Sprints</a>  |
  <a href ="#tecnologias">Tecnologias</a> |
  <a href ="#manual">Manual de Instalação</a>  | 
  <a href ="#equipe"> Equipe</a> |
</p>

<h1 align="center">

<div style="display: inline_block"><br>
<img align="center" alt="Raphs-Jira" height="50" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg">

<img align="center" alt="Raphs-HTML" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />

<img align="center" alt="Raphs-CSS" height="40" width="60" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">

<img align="center" alt="Raphs-TypeScript" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg">

<img align="center" alt="Raphs-React" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg">

<img align="center" alt="Raphs-Vite" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitejs/vitejs-original.svg">

<img align="center" alt="Raphs-Node" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg">
          
<img align="center" alt="Raphs-NestJS" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nestjs/nestjs-original.svg">

<img align="center" alt="Raphs-Python" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">

<img align="center" alt="Raphs-Colab" height="60" width="60" src="https://colab.research.google.com/img/colab_favicon_256px.png">

<img align="center" alt="Raphs-Postgre" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-plain.svg">

<img align="center" alt="Raphs-Figma" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg">

<img align="center" alt="Raphs-Git" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg">

<img align="center" alt="Raphs-VsCode" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg">

<img align="center" alt="Raphs-Figma" height="40" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg">

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

<!---
## 📋 Backlog do Produto <a id="backlog"></a>

| Rank | Prioridade | User Story                                                                                                                                                                                                     | Story Points | Sprint | Requisito do Cliente | Status |
| :--: | :--------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------: | :----: | :------------------: | :----: |
|  1   |    Alta    | Como usuário, quero uma interface para inserir um prompt, para que eu possa enviá-lo às LLMs e obter suas respostas                                                                                            |      14      |   1    |         R02          |   ✅   |
|  2   |    Alta    | Como usuário, eu quero enviar um prompt para dois modelos de IA simultaneamente, para que eu possa avaliar suas respostas posteriormente.                                                                      |      47      |   1    |       R01/R09        |   ✅   |
|  3   |    Alta    | Como usuário, eu quero visualizar as respostas das LLMs de forma clara e acessível, para que eu possa analisá-las em critérios.                                                                                |      28      |   1    |         R03          |   ✅   |
|  4   |    Alta    | Como usuário, eu quero uma interface para poder avaliar cada resposta individualmente através de critérios definidos, para que eu possa analisar a qualidade das respostas geradas                             |      22      |   1    |         R03          |   ✅   |
|  5   |    Alta    | Como usuário, eu quero uma interface para poder escolher a melhor resposta entre as duas geradas pelas LLMs, para que o sistema registre minha decisão e justificativa.                                        |      29      |   1    |         R04          |   ✅   |
|  6   |    Alta    | Como Administrador, eu quero que as avaliações dos usuários sobre as LLMs sejam armazenadas em um BD, para que possam ser utilizadas em processos de fine-tunning futuramente.                                 |      41      |   1    |         R05          |   ✅   |
|  7   |    Alta    | Como usuário, eu quero ser alertado caso minha escolha entre LLM1 e LLM2 não esteja coerente com minha avaliação, para que eu possa revisar minha decisão antes de finalizar.                                  |      3       |   2    |         R04          |   ✅   |
|  8   |    Alta    | Como usuário, eu quero que as respostas das LLMs sejam enriquecidas com informações relevantes da base de dados (vetorizada), para que sejam mais precisas                                                     |      5       |   2    |         R07          |   ✅   |
|  10  |    Alta    | Como Administrador, eu gostaria de ser o primeiro usuário do sistema, já devidamente pré inserido no banco de dados, para que possa acessar a aplicação.                                                       |      44      |   1    |         R06          |   ✅   |
|  11  |   Média    | Como Administrador, eu quero cadastrar novos usuários na plataforma, para que somente pessoas autorizadas possam acessá-la.                                                                                    |      17      |   3    |         R06          |   ✅   |
|  12  |   Média    | Como usuário, eu quero acessar a aplicação através de uma interface de login, para que somente usuários autorizados possam utilizar o sistema.                                                                 |      13      |   3    |         R06          |   ✅   |
|  13  |   Média    | Como usuário autorizado, eu quero acessar o sistema através de um login, para utilizar a aplicação.                                                                                                            |      23      |   3    |         R06          |   ✅   |
|  14  |   Média    | Como usuário autenticado, eu quero poder fazer o logout da aplicação de forma segura, para que meus dados não fiquem acessíveis a terceiros.                                                                   |      18      |   3    |         R06          |   ✅   |
|  15  |   Média    | Como usuário, eu quero poder revisar minha escolha antes de submetê-la, para que eu tenha certeza de que minha decisão está correta.                                                                           |      2       |   2    |         R04          |   ✅   |
|  16  |   Média    | Como Administrador, eu quero visualizar a lista de usuários cadastrados, para que eu possa gerenciar quem tem acesso ao sistema.                                                                               |      20      |   3    |         R06          |   ✅   |
|  17  |   Média    | Como Administrador, eu quero redefinir a senha de um usuário, para que eu possa ajudá-lo caso ele não consiga acessar a conta.                                                                                 |      18      |   3    |         R06          |   ✅   |
|  18  |   Média    | Como Administrador, eu quero excluir usuários do sistema, para que possa revogar o acesso de usuários a aplicação.                                                                                             |      13      |   3    |         R06          |   ✅   |
|  19  |   Baixa    | Como usuário, eu quero ser informado com mensagens de erro caso ocorra demora excessiva no envio do prompt ou na resposta das LLMs, ou outros erros, para que eu possa entender o problema e tentar novamente. |      2       |   2    |         R03          |   ✅   |
|  21  |   Baixa    | Como usuário, eu quero poder receber mensagens claras sobre o status das avaliações, para ter certeza de que minha avaliação foi registrada corretamente.                                                      |      2       |   2    |         R03          |   ✅   |
|  22  |   Baixa    | Como usuário, eu quero poder voltar para telas anteriores durante o processo de avaliação, para que eu possa corrigir informações antes de enviar a decisão final.                                             |      1       |   2    |       R03/R04        |   ✅   |
|  24  |   Baixa    | Como usuário, eu quero editar meus dados pessoais, para que eu possa manter minhas informações atualizadas.                                                                                                    |      16      |   3    |         R06          |   ✅   |

---

## 🏃‍ DoR - Definition of Ready <a id="dor"></a>

- User Stories com **Critérios de Aceitação**
- Subtarefas divididas **a partir das US**
- Design no **Figma**
- Modelagem do **Banco de Dados**
- Diagrama de **Rotas**
- Banco de Dados **Vetorizado** do Cliente

## 🏆 DoD - Definition of Done <a id="dod"></a>

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

<a id="equipe"></a>

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

</div>
