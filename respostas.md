## 📊 Dashboard – Análise de Canais de Aquisição (Looker Studio + GA4)



Este dashboard foi desenvolvido no Looker Studio, conectado diretamente ao Google Analytics 4 (conta demo da Google Merchandise Store).

O objetivo deste painel é analisar a aquisição de usuários do site, respondendo à seguinte pergunta:

**"Quais canais de marketing estão trazendo mais usuários para o site?"**

### 🔍 Visões apresentadas:
- **KPI Cards:** Total de Usuários, Sessões e Novos Usuários.
- **Gráfico de Barras:** Distribuição de usuários por canal de aquisição (Direct, Organic Search, Paid Search, Referral, Email, etc.).
- **Gráfico de Pizza:** Participação percentual dos usuários por canal.
- **Gráfico de Linha (Série Temporal):** Evolução dos usuários ao longo dos dias, permitindo observar padrões de picos ou quedas no tráfego.

### 🔗 Link do Dashboard:
[→ Acesse o dashboard no Looker Studio] (https://lookerstudio.google.com/s/sUyFs9onQVU)


### ⚙️ Observações Técnicas:
- A conexão entre GA4 e Looker Studio apresenta limitações em algumas métricas, portanto, a análise focou em **Total de Usuários**, que representa de forma clara a distribuição do tráfego por canal.
- Outras métricas e análises mais avançadas serão realizadas na etapa com SQL via BigQuery, que permite acesso completo e granular aos dados do GA4.

