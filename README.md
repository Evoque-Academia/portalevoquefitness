# Portal Evoque Fitness

![Status](https://img.shields.io/badge/status-production-green)
![Stack](https://img.shields.io/badge/stack-react%20%7C%20python%20%7C%20sql-blue)
![Auth](https://img.shields.io/badge/auth-Auth0-orange)
![License](https://img.shields.io/badge/license-internal-red)

Plataforma corporativa desenvolvida para centralizar operações de tecnologia, ferramentas internas e visualização de dados estratégicos da **Evoque Fitness**.

O sistema funciona como um **hub tecnológico corporativo**, reunindo aplicações operacionais, dashboards e integrações empresariais em um único ambiente seguro.

---

# Visão Geral

O Portal Evoque Fitness foi criado para consolidar diferentes ferramentas internas utilizadas pela organização, permitindo que áreas administrativas, técnicas e estratégicas utilizem uma única plataforma para suas atividades.

A aplicação centraliza:

• ferramentas internas de TI  
• dashboards de indicadores estratégicos  
• integrações com serviços corporativos  
• automações operacionais  
• acesso administrativo a recursos da empresa  

Essa abordagem reduz a fragmentação de sistemas e melhora a gestão tecnológica da organização.

---

# Arquitetura da Plataforma

A aplicação segue uma arquitetura **full stack moderna**, separando interface, lógica de negócio e dados.


Interface Web
↓
API Backend
↓
Camada de Dados
↓
Integrações Corporativas


Essa arquitetura permite:

- maior escalabilidade
- separação clara de responsabilidades
- facilidade de manutenção
- evolução modular da plataforma

---

# Tecnologias Utilizadas

## Frontend

Interface web moderna construída utilizando:

- React
- Vite
- TailwindCSS
- SPA (Single Page Application)

Responsável por toda a experiência do usuário, incluindo navegação, dashboards e ferramentas administrativas.

---

## Backend

API desenvolvida em **Python**, responsável por:

- lógica de negócio
- autenticação e autorização
- processamento de dados
- integração com serviços externos
- comunicação com banco de dados

A API fornece endpoints utilizados pela interface web para execução das operações do sistema.

---

# Sistema de Autenticação

A autenticação da plataforma utiliza **Auth0**, garantindo um sistema seguro de identidade.

Tecnologias utilizadas:

- OAuth2
- OpenID Connect
- JWT (JSON Web Tokens)

Fluxo de autenticação:


Usuário realiza login
↓
Auth0 valida credenciais
↓
Token JWT é emitido
↓
Backend valida token
↓
Acesso liberado à aplicação


Benefícios dessa abordagem:

- autenticação segura
- gerenciamento centralizado de identidade
- suporte a SSO
- controle de sessão

---

# Banco de Dados

A plataforma utiliza banco de dados relacional para armazenamento de dados operacionais e estratégicos.

O acesso aos dados é realizado através de um **ORM**, que fornece abstração segura da comunicação com o banco.

Os dados armazenados incluem:

- métricas operacionais
- indicadores estratégicos
- registros administrativos
- informações utilizadas pelos dashboards

---

# Portal de TI

O portal inclui um módulo dedicado à equipe de tecnologia da informação.

Esse módulo permite centralizar ferramentas utilizadas para operações técnicas e administrativas.

Entre os objetivos desse módulo estão:

- apoiar operações de suporte técnico
- centralizar ferramentas administrativas
- acompanhar métricas operacionais
- automatizar processos internos

---

# Portal de Business Intelligence

A plataforma inclui um módulo de **Business Intelligence (BI)** responsável pela visualização de dados estratégicos da organização.

Esse módulo permite:

- visualização de dashboards
- análise de indicadores
- acompanhamento de métricas operacionais
- apoio à tomada de decisão

Os dados apresentados são processados pelo backend e exibidos através da interface web.

---

# Integrações

A plataforma integra diferentes serviços corporativos.

## Auth0

Responsável pela autenticação e gerenciamento de identidade dos usuários.

---

## Microsoft Graph

Utilizado para integração com serviços do ecossistema Microsoft.

Possíveis funcionalidades incluem:

- envio de comunicações por e-mail
- automações corporativas
- integração com serviços da Microsoft

---

## APIs Corporativas

A aplicação também utiliza APIs internas para comunicação entre diferentes sistemas da organização.

Essas integrações permitem a troca de dados entre módulos da plataforma e serviços externos.

---

# Atualizações em Tempo Real

A plataforma possui suporte para atualização dinâmica de informações, permitindo que dados importantes sejam atualizados em tempo real na interface.

Esse mecanismo pode ser utilizado para:

- notificações
- atualizações operacionais
- eventos administrativos

---

# Segurança

A segurança da aplicação foi projetada desde o início do desenvolvimento.

Entre os mecanismos utilizados estão:

- autenticação baseada em tokens
- validação de sessão no backend
- controle de acesso a recursos
- separação entre camadas da aplicação

Essas medidas garantem que apenas usuários autorizados tenham acesso ao sistema.

---

# Objetivo da Plataforma

O Portal Evoque Fitness foi desenvolvido para ser a **plataforma central de tecnologia da empresa**, consolidando ferramentas, dados e integrações em um único ambiente.

A solução busca:

- melhorar a eficiência operacional
- centralizar ferramentas corporativas
- facilitar o acesso a dados estratégicos
- apoiar processos internos da organização

A plataforma continua evoluindo conforme novas necessidades surgem dentro da empresa.

---

# Uso

Sistema desenvolvido para uso interno da organização.

---

© Evoque Fitness
