# Exercícios-de-Pesquisa-Operacional

A Esportes Radicais S.A. produz paraquedas e asas-delta em duas linhas de montagem. A primeira linha tem 100 horas semanais disponíveis para a fabricação dos produtos, e a segunda linha tem um limite de 42 horas semanais. 
Cada um dos produtos requer 10 horas de processamento na linha 1, enquanto na linha 2 o paraquedas requer 3 horas e a asa-delta, 7 horas. 
Sabendo que o mercado está disposto a comprar toda a produção da empresa e que o lucro unitário do paraquedas é de R$ 60,00 e o da asa-delta é de R$ 40,00, encontre a programação de produção que maximize o lucro da Esportes Radicais S.A. 
(Resolva pela análise gráfica.)

1 Linha - 100h / semana  -
Paraquedas - R$ 60,00 de lucro p/ unidade
Asas-delta - R$ 40,00 de lucro p/ unidade   

       - Paraquedas - 10h de Processamento - 
       - Asas-delta - 10h de processamento

2 Linha  - 42h / semana
       - Paraquedas - 3h de Processamento
       - Asas-delta - 7h de processamento


-------------------------------------------------
1 Passo - Definir as variáveis
      - Xp - quantidades de paraquedas produzida por semana
      - Xa - quantidades de asas-delta produzida pro semana
 ----------------------------------------     
2 Passo - Definir o objetivo
       Lucor total: 60x1 + 40x2
--------------------------------------
3 Passo - Definir as restrições
  Linha 1: 10Xp + 10Xa ≤ 100
  Linha 2: 3Xp + 7Xa ≤ 42
  -----------------------------  
4 Passo - Definir a não negatividade
Xp ≥ 0
Xa ≥ 0
----------------------------
RESUMO
Max = 60 x1 + 40 x2

10Xp + 10Xa ≤ 100 
  3Xp +   7Xa ≤ 42
    Xp                ≥ 0
                  Xa  ≥ 0


<img width="380" height="146" alt="PO" src="https://github.com/user-attachments/assets/616867d9-ef5a-40ac-baff-1012c3d6cb5e" />

