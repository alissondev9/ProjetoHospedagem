# 🏨 Sistema de Hospedagem

Este repositório contém a solução do desafio de projeto do módulo de "Explorando a linguagem C#", integrante da trilha .NET da [DIO](https://www.dio.me/). O objetivo é criar um sistema de reserva de hotel que gerencia hóspedes, suítes e realiza cálculos de estadia com regras de negócio específicas.

## 🎯 Objetivo do Projeto
Construir um sistema robusto que relacione hóspedes (Pessoa) a acomodações (Suíte) através de uma Reserva, aplicando validações de capacidade e lógica de descontos.

## ⚙️ Regras de Negócio e Funcionalidades
- **Capacidade Máxima:** O sistema impede reservas onde o número de hóspedes excede a capacidade da suíte, lançando uma `Exception`.
- **Cálculo de Diária:** O valor total é calculado multiplicando os dias de reserva pelo valor da diária da suíte.
- **Desconto de Fidelidade:** Reservas iguais ou superiores a **10 dias** recebem automaticamente um **desconto de 10%** no valor total.
- **Contagem de Hóspedes:** Método dedicado para retornar o total de pessoas vinculadas a uma reserva.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** C#
* **Plataforma:** .NET 6.0 (ou superior)
* **Paradigma:** Programação Orientada a Objetos (POO)