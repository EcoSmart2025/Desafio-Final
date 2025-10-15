# Desafio-Final
MVP (Curso I2A2) de Automação Inteligente de NFs. O projeto foca na integração de dados fiscais (SEFAZ ↔ ERPs de PMEs) usando Python, LangChain e MySQL. O MVP simula a extração de NFs (CSV/XML) para o MySQL e utiliza um Agente LLM (Gemini 2.5 Flash) para facilitar a análise e o gerenciamento eficiente dos dados fiscais.

## 🤖 EcoSmart: Automação Inteligente da Emissão e Análise de Notas Fiscais (NFs)

[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-v0.1.0%2B-green?logo=chainlink&logoColor=white)](https://www.langchain.com/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Google Gemini](https://img.shields.io/badge/Google_Gemini-2.5_Flash-4285F4?logo=google&logoColor=white)](https://ai.google.dev/gemini)

Este projeto foi desenvolvido pela equipe **EcoSmart** como o MVP (Produto Mínimo Viável) final do **Curso Agentes Autônomos com Redes Generativas** (I2A2).

---

### 💡 Ideia do Projeto (O Desafio)

O projeto visa criar um protótipo de solução para **automatizar a integração de dados fiscais (Notas Fiscais - NFs)** entre as Secretarias da Fazenda (SEFAZ) e os ERPs de pequenas e médias empresas. O principal objetivo é facilitar a **análise e o gerenciamento eficiente** dos dados de NFs, liberando profissionais de tarefas rotineiras e complexas através da automação inteligente.

### 🎯 Tema do Projeto Final (Curso I2A2)

O trabalho final aborda a criação de **Ferramentas Gerenciais** com foco nos seguintes tópicos, diretamente endereçados pela arquitetura do nosso MVP:

#### 1. Relatórios Personalizados
**Geração de relatórios personalizados:** Possibilidade de criar relatórios com informações relevantes para o setor.
**Utilizar informações internas:** Análise baseada nos dados de NFs coletadas e emitidas e armazenados no MySQL.
**Agregar informações externas relevantes:** Novos módulos (ex: análise de conformidade, geração de relatórios personalizados) podem ser facilmente integrados.
**Análises preditivas e simulações de cenários:** O armazenamento seguro e estruturado no MySQL permite análises gerenciais e auditorias eficientes.

#### 2. Assistente Consultor Especializado
**Suporte para dúvidas e decisões estratégicas:** O **Agente Especialista de Dados Fiscais** atua como um consultor virtual, processando solicitações de emissão e validação de NFs e interagindo com sistemas externos automaticamente.
**Informações sobre contabilidade e tributação:** O LLM (`gemini-2.5-flash`) é orquestrado pela LangChain para processar e responder com informações sobre as regras brasileiras e linguagem fiscal.

#### 3. Desafios Abordados
**Qualidade das Informações:** Garantida pela validação automatizada de informações nos pipelines de processamento e pelos testes de validação dos agentes LLM.
**Experiência do Usuário:** Maximizada pelo uso de agentes autônomos que interpretam instruções em linguagem natural.

### 🏗️ Arquitetura e Tecnologias

A arquitetura do projeto é modular e utiliza ferramentas de ponta para a orquestração de IA Generativa:

| Componente | Tecnologia | Função no Projeto |
| :--- | :--- | :--- |
| **Orquestração Principal** | **Python** | Linguagem principal para arquitetar a lógica, conectar LLMs, bancos de dados e APIs. Facilita a automação de *pipelines*. |
| **Framework LLM** | **LangChain** | Atua como interface genérica para LLMs, orquestrando agentes virtuais e facilitando a integração com APIs e bancos de dados. |
| **Modelo de Linguagem** | **Gemini 2.5 Flash** | Modelo que impulsiona o Agente Especialista de Dados Fiscais, ideal para raciocínio e casos de uso de agentes (mencionado no prompt do usuário). |
| **Persistência de Dados** | **MySQL** | Banco de dados relacional que garante a **segurança, integridade e escalabilidade** para armazenar todas as informações fiscais, logs e interações. |

---

### 👥 Equipe EcoSmart

| Nome | E-mail | Telefone |
| :--- | :--- | :--- |
| Alex | alexkamp@gmail.com | +5551999828211 |
| Jair | jjuniorlopes@gmail.com | +5571992888890 |
| Rogério | rogerio.batista.teixeira@gmail.com | +5561991810140 |
| Emanuel | ferreirajesus@cdciber.eb.mil.br | +5521996696180 |
| Mariana | contato.marianamoraless@gmail.com | +5511986448332 |
| Gustavo | gustavo.giro.resende@gmail.com | +5511920183412 |
| Elton | elmendir014@gmail.com | +5567991371742 |
| Javan | javanoalmeida@gmail.com | +5574991415181 |

---

### 📜 Licença

Este projeto está licenciado sob a **Licença MIT** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
