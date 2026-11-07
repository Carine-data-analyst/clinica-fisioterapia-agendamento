# Sistema de Gerenciamento de Agendamentos para Clínica de Fisioterapia

Projeto desenvolvido para digitalizar e organizar o processo de agendamento de uma clínica de fisioterapia.

## Sobre o projeto

A clínica realiza o controle dos agendamentos manualmente em uma agenda física. O fisioterapeuta e a secretária compartilham as informações por meio de fotografias enviadas em um grupo no WhatsApp.

Além disso, grande parte dos pacientes é idosa, o que torna inadequada uma solução que dependa da instalação e utilização de um aplicativo próprio.

O projeto propõe um sistema para centralizar o gerenciamento dos pacientes e atendimentos, mantendo o WhatsApp como futuro canal de interação com os pacientes.

## Funcionalidades implementadas

Atualmente, o sistema permite:

- Cadastrar e listar pacientes;
- Evitar cadastros duplicados;
- Pesquisar pacientes pelo nome;
- Configurar datas e horários de atendimento;
- Consultar horários disponíveis;
- Criar agendamentos;
- Listar agendamentos;
- Cancelar agendamentos;
- Reagendar atendimentos;
- Confirmar agendamentos;
- Registrar atendimentos realizados;
- Registrar faltas;
- Registrar pós-atendimento;
- Consultar pós-atendimentos por paciente;
- Consultar pós-atendimentos por avaliação;
- Identificar pacientes que precisam de atenção;
- Registrar quando o retorno ao paciente foi realizado.

## Tecnologias utilizadas

- Python
- SQLite
- HTML
- CSS
- Visual Studio Code

## Estrutura atual

```text
clinica-agendamento/
│
├── agenda.py
├── banco.py
├── horarios.py
├── pacientes.py
├── pos_atendimento.py
└── index.html
```

## Fluxo do atendimento

```text
Paciente
   ↓
Agendamento
   ↓
Agendado
   ↓
Confirmado
   ↓
Realizado
   ↓
Pós-atendimento
   ↓
Avaliação do paciente
```

O sistema também permite registrar cancelamentos, reagendamentos e faltas.

No pós-atendimento, respostas que indiquem aumento da dor ou solicitação de contato podem ser identificadas para acompanhamento do fisioterapeuta.

## Etapas:

- Integração com o WhatsApp Business;
- Automatização de confirmações e lembretes;
- Envio do pós-atendimento pelo WhatsApp;
- Desenvolvimento do backend para disponibilização do sistema;
- Desenvolvimento de uma interface para uso da clínica;
- Avaliação de integração com o Google Calendar.

## Portfólio

O arquivo `index.html` contém uma página de portfólio responsiva apresentando o problema, a solução desenvolvida, as ferramentas utilizadas e os resultados atuais do projeto.

## Autora

**Carine Lopes Elias**  
Curso: Ciência de Dados  
Faculdade de Tecnologia FATEC Adamantina
