# PROJETO-PROJETO-E-DESENVOLVIMENTO-DE-SISTEMA-DE-BANCO-DE-DADOS-RELACIONAL

---

# MedClin - Sistema Integrado de Gestão para Clínicas Médicas

## Visão Geral

**MedClin** é um Sistema Integrado de Gestão (SIG) desenvolvido para clínicas médicas, permitindo o agendamento online de consultas, a gestão de pacientes, e a integração de informações médicas, como exames e diagnósticos. O sistema visa melhorar a organização e a eficiência das clínicas ao centralizar todos os processos em um único ambiente digital.

## Funcionalidades

- **Agendamento de Consultas Online:** Pacientes podem agendar consultas com médicos disponíveis, visualizando horários e especialidades.
- **Gestão de Pacientes:** Cadastro completo dos pacientes, incluindo dados pessoais, históricos de consultas, diagnósticos e exames.
- **Gestão de Médicos:** Cadastro de médicos com informações detalhadas, como especialidade, contato e histórico de consultas realizadas.
- **Administração Centralizada:** Administradores podem gerenciar informações de pacientes, médicos e consultas, além de atualizar dados no sistema.

## Justificativa

O MedClin facilita o processo de agendamento de consultas, melhora a organização e integração de informações e apoia na tomada de decisões de forma mais rápida e precisa. O sistema é escalável e pode ser adaptado para diferentes segmentos que utilizam o agendamento de serviços.

## Estrutura do Banco de Dados

### Principais Tabelas

- **Medico:** Contém CRM, CPF, nome, especialidade e contato.
- **Paciente:** Contém CPF, nome, dados pessoais, e histórico médico.
- **Consulta:** Contém data, ID, custo, médico responsável, e hora.
- **Diagnóstico:** Contém ID e resultados vinculados a consultas.
- **Exames:** Contém ID, tipo, e resultados.

## Tecnologias Utilizadas

- **SQL Server**
- **MySQL Workbench**
- **Azure Data Studio**

## Contribuidores

- **Andressa Cristina Chaves de Oliveira**
- **Henrique Antunes Fonseca**
- **Iolanda Benfica Blaso de Souza**

---

Este README fornece uma visão geral do propósito, funcionalidades, e a estrutura técnica do projeto MedClin, garantindo que outros desenvolvedores e usuários possam entender e contribuir para o sistema.
