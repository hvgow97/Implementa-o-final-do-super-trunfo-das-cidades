# Projeto: Super Trunfo das Cidades – Nível Aventureiro

## Desenvolvido por:
Hugo Nascimento | Matrícula: 202505245409 | Curso: Análise e Desenvolvimento de Sistemas - Estácio

## Sobre o Projeto

Este projeto é uma continuação do desafio anterior (Nível Básico) do curso de Análise e Desenvolvimento de Sistemas.

O objetivo é criar um programa em **linguagem C** que cadastre informações de duas cidades e calcule:

- **Densidade Populacional** → População ÷ Área da cidade.
- **PIB per Capita** → PIB Total ÷ População.

O programa também exibe todas as informações de cada cidade, junto com os cálculos.

---

## Funcionalidades

✅ Leitura dos dados de cada cidade:  
- Estado (caractere)  
- Código da carta (string)  
- Nome da cidade (string)  
- População (inteiro)  
- Área (float - km²)  
- PIB (float - em bilhões de reais)  
- Número de pontos turísticos (inteiro)

✅ Cálculo da **Densidade Populacional**

✅ Cálculo do **PIB per Capita**

✅ Exibição formatada de todos os dados, incluindo os novos cálculos

✅ Manutenção das regras do desafio:  
- Sem uso de **laços de repetição (for, while)**  
- Sem uso de **condicionais (if, else)**

## Observações
Este projeto segue todas as regras solicitadas no desafio Nível Aventureiro.

Não foram usados loops nem estruturas de decisão, conforme as instruções.

O programa foi testado localmente e está funcionando corretamente.

O código está devidamente comentado para facilitar o entendimento.

## Licença
Este projeto está sob a Licença MIT.

---

## Como Compilar e Executar

Se estiver usando o **GCC** (ou outro compilador C):

```bash
gcc super_trunfo.c -o super_trunfo
./super_trunfo
