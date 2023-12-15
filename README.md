# Projeto de EAE1106 Métodos Computacionais para Economistas

O objetivo do projeto é investigar a base de dados Global Data Sustainable Energy


Documentos
- *archive(1).zp* refere-se ao arquivo baixado original, contém a base de dados em formato `.zip`
- *global-data-on-sustainable-energy (1).csv* é o arquivo com a base de dados em `.csv`
- *sustainable_energy.ipynb* é o arquivo que trabalharemos, é um arquivo jupyter, portanto, `.ipynb`

Temas propostos
## Exploração Econômica utilizando a Base de Dados de Sustentabilidade Energética

### Introdução

Este repositório visa explorar diversas hipóteses econômicas utilizando a base de dados de sustentabilidade energética disponível. Cada hipótese é acompanhada por um modelo formal, proporcionando uma estrutura analítica para investigar as relações econômicas subjacentes.

### Hipóteses e Modelos Formais

1. **Investimento em Pesquisa e Desenvolvimento (P&D) em Energia Sustentável e Crescimento do PIB**
   - **Modelo Formal:** `GDP_growth ∼ Investment_in_R&D_for_sustainable_energy`
   - **Justificação:** Modelo de Crescimento Endógeno, onde o investimento em P&D impulsiona o crescimento econômico ao melhorar a eficiência e inovação.

2. **Eficiência Energética e Taxa de Crescimento do PIB**
   - **Modelo Formal:** `GDP_growth ∼ Energy_intensity_level_of_primary_energy`
   - **Justificação:** Modelo de Crescimento Econômico Sustentável, onde a eficiência energética contribui para um crescimento mais equilibrado.

3. **Participação de Energias Renováveis e PIB Per Capita**
   - **Modelo Formal:** `GDP_per_capita ∼ Renewable_energy_share_in_total_final_energy_consumption`
   - **Justificação:** Modelo de Crescimento Econômico com Externalidades Positivas, onde a transição para energias renováveis contribui para o desenvolvimento econômico.

4. **Distribuição do Consumo de Energia e Renda Per Capita**
   - **Modelo Formal:** `Primary_energy_consumption ∼ GDP_per_capita`
   - **Justificação:** Modelo de Demanda por Energia, onde a renda é um determinante crucial do consumo de energia.

5. **Ajuda Financeira Externa e Participação de Energias Renováveis**
   - **Modelo Formal:** `Financial_flows_to_developing_countries ∼ Renewable_energy_share_in_total_final_energy_consumption`
   - **Justificação:** Modelo de Financiamento para Energias Renováveis, onde a autonomia financeira está relacionada à autossuficiência energética.

6. **Acesso à Eletricidade e Crescimento do PIB**
   - **Modelo Formal:** `GDP_growth ∼ Access_to_electricity`
   - **Justificação:** Modelo de Capital Humano, onde o acesso à eletricidade contribui para a produtividade e, consequentemente, para o crescimento econômico.

7. **Participação de Energias Renováveis e Índice de Desenvolvimento Humano (IDH)**
   - **Modelo Formal:** `IDH ∼ Renewable_energy_share_in_total_final_energy_consumption`
   - **Justificação:** Modelo de Desenvolvimento Sustentável, onde a adoção de fontes de energia limpa contribui para o bem-estar social.

8. **Volatilidade no Crescimento do PIB e Participação de Energias Renováveis**
   - **Modelo Formal:** `GDP_growth_volatility ∼ Renewable_energy_share_in_total_final_energy_consumption`
   - **Justificação:** Modelo de Estabilidade Econômica, onde a diversificação da matriz energética contribui para a estabilidade econômica.

9. **Participação de Energias Renováveis e Redução da Desigualdade de Renda**
   - **Modelo Formal:** `Income_inequality ∼ Renewable_energy_share_in_total_final_energy_consumption`
   - **Justificação:** Modelo de Equidade Econômica, onde a transição para energias renováveis pode ter efeitos redistributivos.

10. **Dependência de Eletricidade de Fontes Fósseis e Crescimento do PIB**
    - **Modelo Formal:** `GDP_growth ∼ Electricity_from_fossil_fuels`
    - **Justificação:** Modelo de Impacto Ambiental, onde a redução da dependência de combustíveis fósseis contribui para o crescimento econômico sustentável.

11. **Participação de Energias Renováveis e Menor Inflação**
    - **Modelo Formal:** `Inflation_rate ∼ Renewable_energy_share_in_total_final_energy_consumption`
    - **Justificação:** Modelo de Inflação e Sustentabilidade, onde a transição para energias renováveis pode impactar os custos de produção e, consequentemente, a inflação.

12. **Crescimento do PIB e Acesso a Fontes Limpas para Cozinhar**
    - **Modelo Formal:** `GDP_growth ∼ Access_to_clean_fuels_for_cooking`
    - **Justificação:** Modelo de Desenvolvimento Humano, onde condições de vida melhoradas impactam positivamente o crescimento econômico.

13. **Atratividade de Investimentos e Participação de Energias Renováveis**
    - **Modelo Formal:** `Foreign_direct_investment ∼ Renewable_energy_share_in_total_final_energy_consumption`
    - **Justificação:** Modelo de Atratividade de Investimentos, onde a sustentabilidade pode atrair investidores internacionais.

14. **Participação de Energias Renováveis e Menor Dependência de Importações de Combustíveis Fósseis**
    - **Modelo Formal:** `Fossil_fuels_imports ∼ Renewable_energy_share_in_total_final_energy_consumption`
    - **Justificação:** Modelo de Balança Comercial, onde a redução das importações de combustíveis fósseis pode influenciar positivamente a balança comercial.

15. **Competitividade Econômica e Investimento em Infraestrutura de Energias Renováveis**
    - **Modelo Formal:** `Competitiveness_index ∼ Investment_in_renewable_energy_infrastructure`
    - **Justificação:** Modelo de Competitividade, onde a infraestrutura de energia é um fator determinante para a competitividade econômica.

Essas hipóteses foram formuladas com base em modelos econômicos conhecidos e podem servir como ponto de partida para análises mais detalhadas usando a base de dados fornecida. A interpretação dos resultados deve considerar a natureza específica das relações propostas por cada hipótese.
