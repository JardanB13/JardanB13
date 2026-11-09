# Olá! 👋

Trabalho com **análise de dados e automação** na área de logística e estoque.
Transformo planilhas exportadas de sistemas internos em **pipelines de tratamento** e **dashboards interativos** que a equipe usa no dia a dia.

**Ferramentas:** Python · pandas · Streamlit · Plotly · JavaScript · Vue 3 · MapLibre · HTML/CSS · Excel · Git

---

## 📂 Projetos

> Os repositórios são **privados** porque usam dados internos da empresa.
> Abaixo está o que cada um faz. Posso apresentar os projetos em uma conversa.

### 🔧 Controle de Ferramental
Pipeline em Python que junta as exportações de requisições e devoluções de ferramentas de vários contratos, limpa os dados e gera uma base única com um log do que foi removido e por quê.
Dashboard em **Streamlit + Plotly** com:
- indicadores de requisição, devolução e saldo em campo, com tendência semanal;
- **Curva ABC** das ferramentas por valor;
- taxa de devolução por contrato;
- **mapa** dos almoxarifados com as cidades atendidas e um mapa de calor da demanda;
- detalhamento com exportação em CSV.

### 🗺️ Cobertura de Estoque por Região
Dashboard web (**Vue 3 + MapLibre**) que mostra no mapa a área de cobertura de cada almoxarifado e, por cidade, os equipamentos **novos, reaproveitados e retirados**.
Scripts em Python atualizam os dados todo mês e publicam **só totais agregados**, sem dados de clientes.

### 📦 Painel de Estoque de Materiais
Dashboards em Python para acompanhar o estoque e a movimentação de materiais por região e por categoria.
