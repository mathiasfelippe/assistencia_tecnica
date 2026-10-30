# 🔧 Sistema de Assistência Técnica

Sistema de gerenciamento para uma assistência técnica de dispositivos eletrônicos, desenvolvido com o objetivo de organizar informações de clientes, aparelhos, serviços e agendamentos de manutenção.

O projeto busca centralizar os processos de atendimento, facilitando o controle dos equipamentos recebidos, dos serviços solicitados e do andamento dos reparos.

## 🎯 Objetivo

Desenvolver uma solução para otimizar a gestão de uma assistência técnica, tornando o gerenciamento de clientes, dispositivos e serviços mais organizado, prático e eficiente.

## ⚙️ Funcionalidades

- **Gerenciamento de usuários:** cadastro e identificação de usuários do sistema.
- **Cadastro de clientes:** armazenamento de informações pessoais e de contato.
- **Controle de aparelhos:** registro de dispositivos, incluindo marca, modelo, IMEI e defeito relatado.
- **Gerenciamento de serviços:** cadastro de serviços oferecidos e seus respectivos valores.
- **Agendamento de atendimentos:** organização dos serviços conforme data e horário.
- **Controle de status:** acompanhamento das etapas do atendimento.

### 📌 Status dos atendimentos

| Status | Descrição |
|---|---|
| AGENDADO | Atendimento programado |
| EM_ANDAMENTO | Serviço em execução |
| CONCLUIDO | Serviço finalizado |
| CANCELADO | Atendimento cancelado |

## 🗄️ Banco de Dados

O projeto utiliza MySQL para armazenar e organizar as informações.

O banco de dados é estruturado nas seguintes tabelas:

- `usuarios` — dados de acesso dos usuários.
- `clientes` — informações dos clientes.
- `aparelhos` — dispositivos cadastrados para manutenção.
- `servicos` — serviços disponíveis e seus valores.
- `agendamentos` — registros dos atendimentos.

## 🛠️ Tecnologias

- MySQL 8+
- SQL
- Modelagem de banco de dados relacional

## 🚀 Como executar

**1. Clone o repositório**

```bash
git clone https://github.com/mathiasfelippe/assistencia_tecnica.git
```

**2. Acesse a pasta do projeto**

```bash
cd assistencia_tecnica
```

**3. Importe o banco de dados**

Com o MySQL instalado e configurado, execute:

```bash
mysql -u root -p < assistencia_db.sql
```

Esse comando cria o banco `assistencia_db`, suas tabelas e insere registros de demonstração.

**4. Consulte a documentação**

O repositório disponibiliza materiais complementares para entender a estrutura e a utilização do projeto:

- `GUIA.pdf` — guia de utilização.
- `documentacao.pdf` — documentação do sistema.
- `der.pdf` — diagrama entidade-relacionamento.

## 📚 Documentação

O projeto também conta com documentação técnica e representação visual da estrutura do banco de dados, facilitando a compreensão de sua organização e funcionamento.


<sub>Projeto desenvolvido com finalidade acadêmica e prática, aplicando conceitos de desenvolvimento de sistemas, modelagem de dados e gerenciamento de informações.</sub>
