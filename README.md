# 🌐 Sistema de Gestão de Chamados


## 1. Objetivo do Projeto

O objetivo deste projeto é desenvolver um Sistema de Gestão de Chamados/Demandas para uma equipe de tecnologia, com o intuito de centralizar, organizar e automatizar o processo de recebimento, acompanhamento e resolução de solicitações feitas por clientes internos ou externos.

O sistema proporcionará maior controle operacional, transparência, produtividade e acompanhamento de indicadores, contribuindo para a eficiência e qualidade do atendimento prestado pela equipe.

#

## 2. Requisitos do Sistema

* **✅ Requisitos Funcionais**

    * Cadastro de chamados com campos como: título, descrição, categoria, urgência, solicitante, anexos.

    * Atribuição de responsáveis e controle de status.

    * Visualização de chamados em lista ou kanban com filtros avançados.

    * Controle de SLA e prazos.

    * Notificações automáticas (e-mail/sistema).

    * Relatórios e dashboards com indicadores de desempenho.

    * Cadastro de usuários com diferentes perfis: solicitante, técnico, gestor.

* **🚫 Requisitos Não Funcionais**

    * Interface responsiva e amigável (desktop e mobile).

    * Sistema com autenticação e controle de permissões.

    * Alta disponibilidade e desempenho estável.

    * Backup periódico e recuperação de dados.

    * Segurança dos dados trafegados e armazenados.

#

## **🛠 3. Tecnologias Utilizadas** 

A seguir estão as principais tecnologias, frameworks e bibliotecas utilizadas no desenvolvimento de sistema:

| Camada         | Tecnologia       |                                  
|------------------|----------------
| Back - end               | Django e Python    
| Front - End            | HTML, CSS, Java Script e Bootstrap           
| Banco de Dados        | SQLite               
| Versionamento     | Git e GitHub         
| Documentação   | Markdown 

#

## **✍🏽 4. System Design**

### **4.1 Arquitetura do Sistema**
A arquitetura MVC (Model-View-Controller) separa o sistema em três camadas principais:

* **Model:** gerencia os dados e regras de negócio, conectando-se ao banco de dados.

* **View:** é a interface visual que o usuário interage (frontend).

* **Controller:** atua como intermediário entre a View e o Model, recebendo as requisições do usuário, processando e retornando respostas.
  
<img src="Arquitetura%20Sistema%20%28System%20Design%29.png" alt="Funcionalidades" width="600"/>


### **4.2 Funcionalidades do Sistema**

<img src="Funcionalidade%20do%20Sistema%20fundo.png" alt="Funcionalidades" width="600"/>

