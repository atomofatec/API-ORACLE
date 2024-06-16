# API-ORACLE

<h1 align="center">API 5º Semestre 2024-1 - Equipe Átomo</h1>

<p align="center">
  <a href ="#projeto"> Projeto </a>  •
  <a href ="#proposta"> Proposta </a>  • 
  <a href ="#prototipo"> Protótipo </a>  • 
  <a href ="#backlogs"> Backlogs </a> • 
<!--   <a href ="#backlog-das-sprints"> Backlog das Sprints </a> • 
  <a href ="#cronograma-das-sprints"> Cronograma das Sprints </a> -->
  <a href ="#stories"> User Stories </a>  •
  <a href ="#bpmn"> BPMN </a>  
  <br>
  <a href ="#modelagem-banco"> Modelagem do Banco de Dados </a>  •
  <a href ="#documentos"> Documentação do Projeto </a>  •
  <a href ="#review">Sprint Reviews</a>  •
  <a href ="#equipe">Equipe</a>
</p>

<br>

<span id="projeto">
  
## :clipboard: O Projeto

> **Status do Projeto: Concluído**

- Desenvolver um sistema de gestão de parceiros para a Oracle. Este sistema será responsável por cadastrar novos parceiros, gerenciar atualizações de informações, acompanhar o desenvolvimento de conhecimento dos parceiros e fornecer relatórios relevantes – em plataforma mobile.

<br>

<span id="proposta">
  
## :dart: Proposta

> **Requisitos Funcionais**
- Desenvolver uma interface de cadastro de parceiros
- Desenvolver uma interface de desenvolvimento de parceiros
- Desenvolver um Dashboard de indicadores de desempenho de parceiros
- Desenvolver um Relatório Analítico de parceiros por produto implementado.

<br>
 
> **Requisitos Não Funcionais**
- Manual do Usuário
- Documentação técnica da estruturação do sistema
- Documentação API – Application Programming Interface
- Modelagem de Banco de Dados ou Arquivo de dados

<br>

<span id="prototipo">
  
## :bulb: Protótipo

**:link: Clique no link abaixo para visualizar o modelo do projeto.**  
> [Protótipo do Projeto](https://www.figma.com/file/b7VEZbtTCFxI08IDgGwxoZ/Prot%C3%B3tipo---Oracle?type=design&node-id=0%3A1&mode=design&t=DYwEVPxpygYslksZ-1)

<br>

<span id="backlogs">
  
## 🗓️ Backlogs

<span id="backlog-do-produto">

<details>
  <summary><strong>:calendar: Backlog do Produto</strong></summary>

| Tarefa | Descrição | Prioridade | Status | User Stories |
| --- | --- | --- | --- | --- |
| Login | Sistema de login de usuários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#login'> User Story 1 </a> |
| Painel Inicial (Dashboard) | Visualização gráfica de dados relevantes e indicadores chave de desempenho | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#dashboard'> User Story 3 </a> |
| Acompanhamento de Desenvolvimento de Conhecimento | Tela para monitorar o conhecimento dos parceiros registrados e visualizar gráficos ou relatórios sobre o progresso | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#acomp_conhec'> User Story 6 </a> |
| Administração do Sistema | Tela para gerenciar administradores ou funcionários do sistema (cadastro, edição, exclusão) | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Cadastro de Parceiros | Usuário ‘Funcionário’ cadastra usuário ‘Parceiro’ | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#cad_parc'> User Story 4 </a> |
| Atualização de Parceiros | Usuário ‘Funcionário’ gerencia conta do usuário ‘Parceiro’ | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#updt_parc'> User Story 5 </a> |
| Visualizar e assinar Program Tracks | Usuário ‘Parceiro’ visualiza e assina melhor opção dentro das Program Tracks | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#program_tracks'> User Story 9 </a> |
| Provas de conhecimento | Usuário ‘Parceiro’ realiza provas de conhecimento | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#provas'> User Story 10 </a> |
| Visualização de dados pessoais | Usuário pode visualizar e editar seus dados pessoais | 🟩 | ✅ Finalizada | 🔴 <a href='#view_dados'> User Story 8 </a> |
| Recuperação de Senha | Sistema para recuperar sua senha | 🟩 | ✅ Finalizada | 🔴 <a href='#senha'> User Story 2 </a> |
| Mensagens e Notificações | Mensagens e notificações do sistema | 🟩 | ✅ Finalizada | 🔴 <a href='#notificacoes'> User Story 11 </a> |
| Ajuda e Suporte | Tela de ajuda e suporte | 🟩 | ✅ Finalizada | 🔴 <a href='#suporte'> User Story 12 </a> |
| Telas de Erro | Telas de erro do sistema | 🟩 | ✅ Finalizada | 🔴 <a href='#erro'> User Story 13 </a> |

</details>

<br>

<span id="backlog-das-sprints">

<details>
  <summary><strong>:calendar: Backlog das Sprints</strong></summary>

| Tarefa | Usuário | Descrição | Prioridade | Status | User Stories |
| --- | --- | --- | --- | --- | --- |
| Interface de Login | Geral | Interface para login de usuários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#login'> User Story 1 </a> |
| Sistema de Login | Geral | Sistema que realiza o login de usuários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#login'> User Story 1 </a> |
| Interface de cadastro de Administradores/Funcionários | Administrador | Interface onde o Administrador consiga cadastrar um novo Administrador ou Funcionário | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Sistema de cadastro de Administradores/Funcionários  | Administrador | Sistema de cadastro de Administrador ou Funcionário | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Interface de listagem de Administradores e Funcionários cadastrados | Administrador | Lista onde o Administrador verá todos os Administradores e Funcionários cadastrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Sistema de listagem de Administradores e Funcionários cadastrados | Administrador | Sistema para listar todos os Administradores e Funcionários cadastrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Interface de edição e exclusão de Administradores/Funcionários | Administrador | Interface onde o Administrador irá editar ou excluir Administradores ou Funcionários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Sistema de edição de Administradores/Funcionários  | Administrador | Sistema de edição de Administradores e Funcionários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Sistema de exclusão de Administradores/Funcionários  | Administrador | Sistema de exclusão de Administradores e Funcionários | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#adm'> User Story 7 </a> |
| Interface de Cadastro de Parceiros  | Funcionário Oracle | Interface onde o Funcionário irá cadastrar um Parceiro | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#cad_parc'> User Story 4 </a> |
| Sistema de Cadastro de Parceiros  | Funcionário Oracle | Sistema de cadastro de Parceiros | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#cad_parc'> User Story 4 </a> |
| Interface de Atualização e Exclusão de Parceiros  | Funcionário Oracle | Interface onde o Funcionário irá editar ou excluir Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#updt_parc'> User Story 5 </a> |
| Sistema de Atualização de Parceiros  | Funcionário Oracle | Sistema para atualização de Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#updt_parc'> User Story 5 </a> |
| Sistema de Exclusão de Parceiros | Funcionário Oracle | Sistema para exclusão de Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#updt_parc'> User Story 5 </a> |
| Interface para monitorar o desenvolvimento de conhecimento dos parceiros  | Funcionário Oracle | Interface onde o Funcionário poderá acompanhar o progresso de conhecimento dos Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#acomp_conhec'> User Story 6 </a> |
| Sistema para monitorar o desenvolvimento de conhecimento dos parceiros  | Funcionário Oracle | Sistema que retorna os dados de desenvolvimento de conhecimento dos Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#acomp_conhec'> User Story 6 </a> |
| Sistema para retorno de dados para gráficos ou relatórios que mostram o progresso  | Funcionário Oracle | Sistema que retorna dados dos Parceiros Registrados para elaboração de gráficos e relatórios | 🟥🟥🟥 | ✅ Finalizada | 🔴 <a href='#acomp_conhec'> User Story 6 </a> |
| Interface para visualização de progresso de desenvolvimento  | Parceiro Registrado | Interface onde o Parceiro poderá visualizar seu progresso | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#dashboard'> User Story 3 </a> |
| Sistema de amostra de dados de progresso de desenvolvimento  | Parceiro Registrado | Sistema que coleta os dados de progresso do Parceiro | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#dashboard'> User Story 3 </a> |
| Interface para visualização e seleção de Program Tasks  | Parceiro Registrado | Interface para visualização e seleção de planos | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#program_tracks'> User Story 9 </a> |
| Sistema para seleção de Program Tasks  | Parceiro Registrado | Sistema para seleção de planos | 🟨🟨 | ✅ Finalizada | 🔴 <a href='#program_tracks'> User Story 9 </a> |
| Interface de Recuperação de Senha | Geral | Interface para recuperação de senha de usuário | 🟩 | ✅ Finalizada | 🔴 <a href='#senha'> User Story 2 </a> |
| Sistema de Recuperação de Senha | Geral | Sistema de recuperação de senha do usuário | 🟩 | ✅ Finalizada | 🔴 <a href='#senha'> User Story 2 </a> |
| Interface de Visualização e Edição de Dados Pessoais | Geral | Interface onde o usuário poderá editar seus dados pessoais básicos | 🟩 | ✅ Finalizada | 🔴 <a href='#view_dados'> User Story 8 </a> |
| Sistema de Visualização e Edição de Dados Pessoais | Geral | Sistema para editar dados pessoais básicos do usuário | 🟩 | ✅ Finalizada | 🔴 <a href='#view_dados'> User Story 8 </a> |
| Mensagens e Notificações | Geral | Sistema de mensagens e notificações | 🟩 | ✅ Finalizada | 🔴 <a href='#notificacoes'> User Story 11 </a> |
| Ajuda e Suporte | Geral | Interface de Ajuda e Suporte | 🟩 | ✅ Finalizada | 🔴 <a href='#suporte'> User Story 12 </a> |
| Telas de Erro | Geral | Interfaces de erros do sistema | 🟩 | ✅ Finalizada | 🔴 <a href='#erro'> User Story 13 </a> |
| Interface para realização de provas de conhecimento  | Parceiro Registrado | Interface onde o Parceiro Registrado irá realizar testes de conhecimento | 🟩 | ✅ Finalizada | 🔴 <a href='#provas'> User Story 10 </a> |
| Sistema para medição de conhecimento através de provas  | Parceiro Registrado | Sistema que irá medir o conhecimento do parceiro a partir dos testes realizados | 🟩 | ✅ Finalizada | 🔴 <a href='#provas'> User Story 10 </a> |

</details>

<br>

<span id="cronograma-das-sprints">

<details>
  <summary><strong>:calendar: Cronograma das Sprints</strong></summary>

<h3>1ª Sprint</h3>

| Tarefa | Usuário | Descrição | Prioridade | Status |
| --- | --- | --- | --- | --- |
| Interface de Login | Geral | Interface para login de usuários | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de Login | Geral | Sistema que realiza o login de usuários | 🟥🟥🟥 | ✅ Finalizada |
| Interface de cadastro de Administradores/Funcionários | Administrador | Interface onde o Administrador consiga cadastrar um novo Administrador ou Funcionário | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de cadastro de Administradores/Funcionários  | Administrador | Sistema de cadastro de Administrador ou Funcionário | 🟥🟥🟥 | ✅ Finalizada |
| Interface de listagem de Administradores e Funcionários cadastrados | Administrador | Lista onde o Administrador verá todos os Administradores e Funcionários cadastrados | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de listagem de Administradores e Funcionários cadastrados | Administrador | Sistema para listar todos os Administradores e Funcionários cadastrados | 🟥🟥🟥 | ✅ Finalizada |
| Interface de Cadastro de Parceiros  | Funcionário Oracle | Interface onde o Funcionário irá cadastrar um Parceiro | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de Cadastro de Parceiros  | Funcionário Oracle | Sistema de cadastro de Parceiros | 🟥🟥🟥 | ✅ Finalizada |

<h1> </h1>

<h3>2ª Sprint</h3>

| Tarefa | Usuário | Descrição | Prioridade | Status |
| --- | --- | --- | --- | --- |
| Interface para monitorar o desenvolvimento de conhecimento dos parceiros  | Funcionário Oracle | Interface onde o Funcionário poderá acompanhar o progresso de conhecimento dos Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada |
| Sistema para retorno de dados para gráficos ou relatórios que mostram o progresso  | Funcionário Oracle | Sistema que retorna dados dos Parceiros Registrados para elaboração de gráficos e relatórios | 🟥🟥🟥 | ✅ Finalizada |
| Interface de Atualização e Exclusão de Parceiros  | Funcionário Oracle | Interface onde o Funcionário irá editar ou excluir Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de Atualização de Parceiros  | Funcionário Oracle | Sistema para atualização de Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de Exclusão de Parceiros  | Funcionário Oracle | Sistema para exclusão de Parceiros Registrados | 🟥🟥🟥 | ✅ Finalizada |
| Interface para realização de provas de conhecimento  | Parceiro Registrado | Interface onde o Parceiro Registrado irá realizar testes de conhecimento | 🟨🟨 | ✅ Finalizada |
| Sistema para medição de conhecimento através de provas  | Parceiro Registrado | Sistema que irá medir o conhecimento do parceiro a partir dos testes realizados | 🟨🟨 | ✅ Finalizada |

<h1> </h1>

<h3>3ª Sprint</h3>

| Tarefa | Usuário | Descrição | Prioridade | Status |
| --- | --- | --- | --- | --- |
| Interface de edição e exclusão de Administradores/Consultores | Administrador | Interface onde o Administrador irá editar ou excluir Administradores ou Consultores | 🟥🟥🟥 | ✅ Finalizada |
| Sistema de edição e exclusão de Administradores/Consultores | Administrador | Sistema de edição e exclusão de Administradores e Consultores | 🟥🟥🟥 | ✅ Finalizada |
| Sistema para retorno de dados para gráficos ou relatórios que mostram o progresso  | Consultor de Aliança | Sistema que retorna dados dos Parceiros Registrados para elaboração de gráficos e relatórios | 🟥🟥🟥 | ✅ Finalizada |
| Interface para visualização de Program Tracks  | Consultor de Aliança | Interface para visualização do desenvolvimento de planos | 🟨🟨 | ✅ Finalizada |
| Sistema para visualização de Program Tracks  | Consultor de Aliança | Sistema para visualização do desenvolvimento de planos | 🟨🟨 | ✅ Finalizada |
| Interface para visualização de expertises dos parceiros | Consultor de Aliança | Interface para visualização do desenvolvimento de expertises dos Parceiros | 🟨🟨 | ✅ Finalizada |
| Sistema para visualização de expertises dos parceiros | Consultor de Aliança | Sistema que retorna os dados de desenvolvimento de expertises dos Parceiros | 🟨🟨 | ✅ Finalizada |
| Interface para seleção de qualificações dos parceiros | Consultor de Aliança | Interface para visualização dos qualificadores de especialização | 🟨🟨 | ✅ Finalizada |
| Sistema de seleção de qualificações dos parceiros | Consultor de Aliança | Sistema para seleção dos qualificadores de especialização | 🟨🟨 | ✅ Finalizada |

<h1> </h1>

<h3>4ª Sprint</h3>

| Tarefa | Usuário | Descrição | Prioridade | Status |
| --- | --- | --- | --- | --- |
| Interface para visualização de progresso de desenvolvimento  | Parceiro Registrado | Interface onde o Parceiro poderá visualizar seu progresso | 🟨🟨 | ✅ Finalizada |
| Sistema de amostra de dados de progresso de desenvolvimento  | Parceiro Registrado | Sistema que coleta os dados de progresso do Parceiro | 🟨🟨 | ✅ Finalizada |
| Interface de Recuperação de Senha | Geral | Interface para recuperação de senha de usuário | 🟩 | ✅ Finalizada |
| Sistema de Recuperação de Senha | Geral | Sistema de recuperação de senha do usuário | 🟩 | ✅ Finalizada |
| Mensagens e Notificações | Geral | Sistema de mensagens e notificações | 🟩 | ✅ Finalizada |
| Ajuda e Suporte | Geral | Interface de Ajuda e Suporte | 🟩 | ✅ Finalizada |
| Telas de Erro | Geral |  | 🟩 | ✅ Finalizada |

<h1> </h1>

</details>

<br>

<span id="stories">

## 📖 User Stories

|          Função           |                     User Story                      |
| :-------------------: | :----------------------------------------------------------: |
| Login<a id='login'></a> |Como usuário, quero poder acessar o sistema usando meu nome de usuário e senha para iniciar minha sessão.|
| Recuperação de senha<a id='senha'></a> |Como usuário, esqueci minha senha e quero receber um link seguro por e-mail para recuperar minha senha.|
| Dashboard<a id='dashboard'></a> |Como funcionário da Oracle, quero ver um resumo visual dos indicadores-chave de desempenho assim que faço login.|
| Dashboard |Como funcionário da Oracle, quero interagir com gráficos para obter mais detalhes sobre o desempenho.|
| Cadastro de Parceiros<a id='cad_parc'></a> |Como funcionário da Oracle, quero poder cadastrar um novo parceiro, inserindo informações detalhadas, como nome, tipo, expertise, etc.|
| Atualização de Parceiros<a id='updt_parc'></a> |Como funcionário da Oracle, quero poder atualizar informações de um parceiro existente para manter os dados precisos.| 
| Acompanhamento de Desenvolvimento de Conhecimento<a id='acomp_conhec'></a> |Como funcionário da Oracle, quero registrar o desenvolvimento de conhecimento de um parceiro, indicando as áreas específicas.| 
| Acompanhamento de Desenvolvimento de Conhecimento |Como funcionário da Oracle, quero visualizar o progresso de desenvolvimento de conhecimento de um parceiro por meio de gráficos ou relatórios.| 
| Administração do Sistema<a id='adm'></a> |Como administrador do sistema, quero cadastrar um novo administrador do sistema ou funcionário.|
| Administração do Sistema |Como administrador do sistema, quero editar as informações de outro administrador ou funcionário, caso haja alterações necessárias.|
| Administração do Sistema |Como administrador do sistema, quero excluir um administrador ou funcionário do sistema que não é mais necessário. |
| Visualização de Dados Pessoais<a id="view_dados"></a> |Como usuário, quero visualizar e editar minhas informações pessoais.|
| Visualizar e assinar Program Tracks<a id='program_tracks'></a> |Como parceiro, quero visualizar as tarefas do programa disponíveis para mim e ser capaz de assiná-las conforme necessário.|
| Provas de conhecimento<a id='provas'></a> |Como parceiro, quero acessar uma tela para realizar provas de conhecimento relacionadas ao programa.|
| Mensagens e Notificações<a id='notificacoes'></a> |Como usuário, quero receber notificações sobre atualizações importantes no sistema, como novos parceiros cadastrados ou alterações de status.
| Ajuda e Suporte<a id='suporte'></a> |Como usuário, quero acessar uma base de conhecimento para encontrar respostas para perguntas frequentes.|
| Telas de Erro<a id='erro'></a> |Como usuário, quero ver mensagens claras e informativas em caso de erros, indicando o problema e possíveis soluções.|

<span id="bpmn">
  
## 📊 Business Process Model and Notation - BPMN

<h1 align="center"><img src="https://github.com/atomofatec/API-ORACLE/blob/main/images/bpmn_gestao_parceiros.jpeg" alt="BPMN"/></h1> 

<br>

<span id="modelagem-banco">

## :cd: Modelagem do Banco de Dados

<h1 align="center"><img src="https://github.com/atomofatec/API-ORACLE/blob/main/images/modelagem-banco-oracle.png" /></h1> 

<br>

<span id="documentos">

## 📑 Documentação do Projeto

**:link: Clique no link abaixo para acessar e baixar as documentações do projeto.**
> [Documentação](https://github.com/atomofatec/API-ORACLE/tree/main/docs)

<span id="review">

## :camera_flash: Sprint Reviews

<h3>Video Sprint Review 1</h3>

**:link: Clique no link abaixo para assistir ao vídeo da Sprint Review 1.**
> [Sprint Review 1](https://youtu.be/E-qonM5LjsU)

<h3>Video Sprint Review 2</h3>

**:link: Clique no link abaixo para assistir ao vídeo da Sprint Review 2.**  
> [Sprint Review 2](https://youtu.be/7yYgfctTehE?si=xYAm-Pi1il6MXkVW)

<h3>Video Sprint Review 3</h3>

**:link: Clique no link abaixo para assistir ao vídeo da Sprint Review 3.**  
> [Sprint Review 3](https://youtu.be/tCLMGbH-DMo)

<h3>Video Sprint Review 4</h3>

**:link: Clique no link abaixo para assistir ao vídeo da Sprint Review 4.**  
> [Sprint Review 4](https://youtu.be/Vhah6CHn2F0)

<!-- //
<span id="produto">

## :package: Produto

<h3>1ª Sprint - 13/03 a 02/04</h3>

<!-- //

<br>

<h3>2ª Sprint - 03/04 a 23/04</h3>

//
  
<br>

<h3>3ª Sprint - 24/04 a 14/05</h3>

//
  
<br>

<h3>4ª Sprint - 15/05 a 04/06</h3>

// -->
  
<br>

<span id="equipe">
  
  ## :clipboard: Equipe

<br>

|Nome|Função|GitHub|
| -------- |-------- |-------- |
|**Rebeca Gama**|Product Owner|[![](https://bit.ly/3f9Xo0P)](https://github.com/RebecaGama)|
|**João Gabriel**|Scrum Master|[![](https://bit.ly/3f9Xo0P)](https://github.com/JoaoGRMira)|
|**Diane Alves**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/Diane-Moreno)|
|**Elisa Carvalho**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/elisadsc)|
|**Rita Hecht**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/ritahecht)|
|**Nicholas Guilherme**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/NicholasGui29)|
|**Thiago Bueno**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/TjBueno)|
|**Víctor Henrique**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/ViktorHenrique)|
