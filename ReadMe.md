# Sistema de Ponto Eletrônico

## Sumário

1. [Descrição do Projeto](#descrição-do-projeto)
2. [Histórias de Usuário](#histórias-de-usuário)
3. [Funcionalidades](#funcionalidades)
   - [Frontend](#frontend)
   - [Backend](#backend)
4. [Backlog](#backlog)
5. [Requisitos](#requisitos)
   - [Requisitos Funcionais](#requisitos-funcionais)
   - [Requisitos Não Funcionais](#requisitos-não-funcionais)


## Descrição do Projeto

O Sistema de Ponto Eletrônico é uma aplicação web que permite aos funcionários registrar seus horários de entrada e saída, e aos administradores monitorar e gerenciar esses registros. O sistema oferece funcionalidades como cálculo de horas trabalhadas, geração de relatórios e notificações automáticas.

## Histórias de Usuário

### 1. Funcionário

- **Como um funcionário, quero poder registrar meu horário de entrada e saída, para que meu tempo de trabalho seja monitorado.**
- **Como um funcionário, quero visualizar meu histórico de registros de ponto, para acompanhar minhas horas trabalhadas.**
- **Como um funcionário, quero receber notificações de atrasos e horas extras, para estar ciente do meu desempenho.**

### 2. Administrador

- **Como um administrador, quero visualizar os registros de ponto de todos os funcionários, para monitorar a frequência e pontualidade.**
- **Como um administrador, quero gerar relatórios de horas trabalhadas, para facilitar o cálculo da folha de pagamento.**
- **Como um administrador, quero configurar notificações automáticas, para alertar funcionários sobre atrasos e horas extras.**

## Funcionalidades

### Frontend

- **Página de Login:** Autenticação de usuários (funcionários e administradores).
- **Dashboard do Funcionário:** Registro de ponto, visualização de histórico e notificações.
- **Dashboard do Administrador:** Visualização de registros de ponto, geração de relatórios e configuração de notificações.
- **Responsividade:** Design adaptável para dispositivos móveis e desktops.

### Backend

- **API de Autenticação:** Endpoints para login e gerenciamento de sessões.
- **API de Registro de Ponto:** Endpoints para registro de entrada e saída, e consulta de histórico.
- **API de Relatórios:** Endpoints para geração de relatórios de horas trabalhadas.
- **Notificações Automáticas:** Sistema de envio de e-mails e alertas no dashboard.

## Backlog

### Funcionalidades Prioritárias

1. **Autenticação de Usuários**
2. **Registro de Ponto**
3. **Visualização de Histórico de Ponto**
4. **Geração de Relatórios**
5. **Notificações Automáticas**

### Funcionalidades Futuras

1. **Integração com Sistemas de Folha de Pagamento**
2. **Reconhecimento Facial para Registro de Ponto**
3. **Geolocalização para Registro de Ponto**
4. **Exportação de Relatórios em Diferentes Formatos (PDF, Excel)**

## Requisitos

### Requisitos Funcionais

1. O sistema deve permitir o registro de ponto (entrada e saída) pelos funcionários.
2. O sistema deve permitir a visualização do histórico de registros de ponto pelos funcionários.
3. O sistema deve permitir a visualização dos registros de ponto de todos os funcionários pelos administradores.
4. O sistema deve gerar relatórios de horas trabalhadas.
5. O sistema deve enviar notificações automáticas sobre atrasos e horas extras.

### Requisitos Não Funcionais

1. O sistema deve ser responsivo e funcionar em dispositivos móveis e desktops.
2. O sistema deve garantir a segurança dos dados dos usuários.
3. O sistema deve ser escalável para suportar um grande número de usuários.
4. O sistema deve ter alta disponibilidade e ser resiliente a falhas.

