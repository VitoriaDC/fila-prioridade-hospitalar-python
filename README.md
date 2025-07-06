# Sistema de Triagem Hospitalar com Fila de Prioridade em Python

Este projeto consiste na implementação de um sistema de triagem hospitalar utilizando uma **Fila de Prioridade** baseada em **Lista Encadeada Simples** em Python. Desenvolvido como parte do curso de Estruturas de Dados em Análise e Desenvolvimento de Sistemas (UNINTER), o sistema simula o atendimento de pacientes com diferentes níveis de urgência, aplicando regras específicas para a ordem de atendimento.

## 💡 Propósito do Projeto

O objetivo principal foi criar uma solução que pudesse gerenciar eficientemente uma fila de pacientes em um ambiente hospitalar, priorizando casos mais urgentes e garantindo que a ordem de atendimento siga critérios bem definidos. Este projeto demonstra a aplicação prática de estruturas de dados para resolver um problema de gestão de fluxo do mundo real, com foco na **lógica de priorização** e na **integridade da ordem dos dados**.

## 🚀 Funcionalidades

O sistema oferece as seguintes funcionalidades principais através de um menu interativo:

1.  **Adicionar Paciente à Fila:**
    * Permite ao usuário informar a cor do cartão (Amarelo 'A' para alta prioridade, Verde 'V' para baixa prioridade).
    * Atribui automaticamente um número sequencial ao paciente (Verde inicia em 1, Amarelo inicia em 201).
    * Insere o paciente na fila de acordo com as regras de prioridade.
2.  **Mostrar Pacientes na Fila:**
    * Exibe a lista completa de pacientes atualmente na fila, respeitando a ordem de atendimento.
3.  **Chamar Paciente:**
    * Remove o primeiro paciente da fila e exibe uma mensagem chamando-o para atendimento.
4.  **Sair:**
    * Encerra o programa.

## 📋 Regras de Prioridade e Ordenação

O sistema segue as seguintes regras de prioridade para o atendimento:

* Pacientes com cartão **Amarelo ('A')** são chamados antes dos pacientes com cartão **Verde ('V')**.
* Entre pacientes com a **mesma cor de cartão**, aqueles com o **menor número** são atendidos primeiro.

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Estruturas de Dados:** Implementação de Lista Encadeada Simples para a base da fila de prioridade.

## 📊 Exemplo de Saída no Console

Abaixo está um exemplo de interação com o sistema, demonstrando as inserções, exibição da fila e atendimento de pacientes: 

![image](https://github.com/user-attachments/assets/91144af9-a454-4a4e-98ed-b4d7bcfdf915)
![image](https://github.com/user-attachments/assets/39df294f-c9e8-48f7-8aef-a132416c61d4)
![image](https://github.com/user-attachments/assets/6f2f9795-a81a-41d5-8da0-d4fc9558df88)


