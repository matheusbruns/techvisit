# TechVisit - Software de Gestão de Visitas Técnicas

## Descrição

**TechVisit** é um sistema SaaS focado em gerenciar todas as etapas de visitas técnicas residenciais, ideal para empresas que oferecem serviços de instalação, manutenção e inspeções técnicas. Desde o agendamento inicial até o fechamento do serviço e o acompanhamento do uso de materiais, TechVisit é uma solução integrada que traz eficiência e controle ao processo.

O sistema permite gerenciar clientes, técnicos, e visitas de forma centralizada, facilitando o acompanhamento de múltiplos agendamentos, otimizando a logística de visitas e melhorando a comunicação com os clientes.

## Autor
- **Matheus Bruns** - [@matheusbruns](https://github.com/matheusbruns)  

## Tecnologias Utilizadas

- **Frontend**: React com TypeScript, Material UI para componentes e SCSS para estilização.
- **Backend**: Java (Spring Boot) e JPA para gestão de dados.
- **Banco de Dados**: PostgreSQL.

## Funcionalidades Principais

- **Gerenciamento de Visitas**: Registro completo das visitas com dados dos técnicos, clientes, e agendamento.
- **Painel de Acompanhamento**: Visão geral de todas as visitas agendadas em períodos específicos.
- **Perfis Personalizados**: Técnicos, administradores e clientes com permissões diferenciadas.
- **Controle de Materiais**: Controle de equipamentos e materiais utilizados durante a visita.
- **Integração com Google Maps**: Direcionamento para o endereço da visita através do Google Maps.
- **Próximas visitas**: Registro completo das próximas visitas para o técnico que vai realizar o serviço.

## Diagrama de caso de uso
![techvisit_casos_de_uso](https://github.com/user-attachments/assets/be42207f-cea1-4b5d-8925-63b23bfbe74b)

## Links Importantes

- **Aplicação**: [TechVisit](https://techvisit.tech)
- **Repositórios de Código**:
  - [Front-end](https://github.com/matheusbruns/techvisit-front)
  - [Back-end](https://github.com/matheusbruns/techvisit-back)
- **Sonar Cloud**:
  - [Front-end](https://sonarcloud.io/summary/overall?id=matheusbruns_techvisit-front)
  - [Back-end](https://sonarcloud.io/summary/overall?id=matheusbruns_techvisit-back)
- **Design no Figma**: [TechVisit Design](https://www.figma.com/design/lZ4HjgSyZsHrtx2dtEJwjS/TECHVISIT?node-id=0-1&node-type=CANVAS&t=P3WGQfd1JX6dZ9vb-0)
- **Jira para Gerenciamento de Projetos**: [TechVisit no Jira](https://matheusbruns.atlassian.net/jira/software/projects/TECH/list)
- **Documentação da api**: [swagger](https://techvisit.tech/api/swagger-ui/index.html).
- **Monitoramento com Grafana**:
  - URL: [Grafana](http://3.23.158.137:3000)
  - Usuário: `admin`
  - Senha: `techvisit`

## Estrutura de Projeto

### Frontend

- **Bibliotecas**: React, Material UI, Axios para requisições HTTP.
- **Componentização**: Uso de componentes reutilizáveis com alta modularidade, com atenção especial para o estilo responsivo.

### Backend

- **Framework**: Spring Boot com Spring MVC para criação de APIs RESTful.
- **Autenticação**: JWT para autenticação e autorização, com verificação de permissões personalizadas para cada perfil.
- **Persistência**: JPA e Hibernate para persistência de dados com PostgreSQL, configurado para alta performance e escalabilidade.
- **Logs e Monitoramento**: Integração com SonarCloud para análise de código e Grafana para monitoramento do desempenho da aplicação.
