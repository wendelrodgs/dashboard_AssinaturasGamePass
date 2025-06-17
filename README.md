![image](https://github.com/user-attachments/assets/a7cfef60-97f9-496f-9241-90badcc07f05)# dashboard_AssinaturasGamePass

# Projeto realizado com a DIO: Dashboard de vendas de assinaturas do Xbox

## Descrição
Esta planilha foi desenvolvida em um curso da DIO em parceria com o Santander. O projeto é um simulador de uma tabela que retorna os valores de vendas de assinaturas do Xbox.
 
## Sheet 1

### 1. BASE
**Finalidade:** Tabela que recebe a base de dados da planilha.

**Campos:**
- **Subscriber ID**
- **Name**
- **Plan**
- **Start Date**
- **Auto Renewal** 
- **Subscription Price** 
- **Subscription Type** 
- **EA Play Season Pass** 
- **EA Play Season Pass Price** 
- **Minecraft Season Pass** 
- **Minecraft Season Pass Price**
- **Coupon Value**
- **Total Value**

## Sheet 2

### 2. DASHBOARD
**Finalidade:** Retorna os valores selecionados na segmentação dinâmica, é possível selecionar apenas UM de cada tipo.

**Campos:**
- **Subscription Type:** Retorna os valores de acordo com o tipo de assinatura (Anual, Mensal ou Quardrimestral).
- **Plan:** Retorna os valores de acordo com o plano selecionado (Core, Standard, Ultimate).

**Valores Retornados:**
- **Total Subscriptions GAME PASS:** Retorna a soma total da coluna **Subscription Price**.
- **Total Subscriptions EA Play Season Pass:** Retorna a soma total da coluna **EA Play Season Pass Price**.
- **Total Subscriptions Minecraft Season Pass:** Retorna a soma total da coluna **Minecraft Season Pass Price**.

**Tabela**
- **Total Subscriptions XBOX GAME PASS - Auto Renewal**: Retorna a soma total das **Assinaturas com renovação** e das **Assinatural sem renovação**; Também retorna a soma total das assinaturas já descontado cupons.
