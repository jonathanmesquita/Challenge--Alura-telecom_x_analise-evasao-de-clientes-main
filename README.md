<p align="center">
  <img alt="Logo do Projeto" src="./_docs/logo.png" />
</p>

# 📉 Análise de Churn — Telecom X  
**Autor:** [Jonathan Mesquita](https://github.com/jonathanmesquita)

---

## 📌 Visão Geral

Este projeto analisa **os fatores que influenciam a evasão de clientes (churn)** na **Telecom X**, uma empresa de telecomunicações com alta taxa de cancelamento.  
A análise foi conduzida com **Python** e bibliotecas como **Pandas, Seaborn e Matplotlib**, visando gerar **insights práticos** para apoiar estratégias de retenção.

---

## 📂 Estrutura do Projeto

- `notebook.ipynb` — Notebook principal com todo o fluxo da análise, desde limpeza dos dados até visualização e interpretação dos resultados.  
- `data/` — Pasta com os arquivos CSV contendo os dados brutos utilizados.  
- `README.md` — Documentação do projeto (este arquivo).

---

## 🛠 Pré-requisitos

- Python 3.7 ou superior  
- Jupyter Notebook ou Google Colab  
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 📚 Bibliotecas Utilizadas

✅ pandas  
✅ numpy  
✅ matplotlib.pyplot  
✅ seaborn  
✅ requests  

---

## 🔍 Escopo da Análise

A investigação abrangeu:

- 📅 Perfil do churn com base no **tempo de permanência** (*tenure*)  
- 📄 Impacto do **tipo de contrato** na evasão  
- 👨‍👩‍👧‍👦 Influência do **perfil familiar** (parceiro e dependentes)  
- 🛠 Relação entre **serviços contratados** e churn  
- 💳 Efeito da **forma de pagamento** e uso da **fatura digital**

Principais conclusões e recomendações estão documentadas no notebook e resumidas abaixo.

---

## 📊 Insights Principais

### **Panorama Geral**  
Embora a maioria dos clientes mantenha seus contratos ativos, o churn é mais intenso em determinados perfis e contextos, revelando **áreas críticas para retenção**.

### **Principais Fatores de Risco**
- **Tempo de contrato:** Clientes recentes (tenure baixo) têm risco maior de cancelamento.  
- **Tipo de contrato:** Mensais apresentam churn elevado; anuais/bienais funcionam como barreiras naturais.  
- **Contexto familiar:** Presença de parceiro(a) e dependentes reduz churn.  
- **Uso dos serviços:** Falta de serviços adicionais aumenta propensão ao cancelamento.  
- **Método de pagamento:** Fatura digital e cheque eletrônico associados a churn mais alto.

---

## 🎯 Oportunidades para Redução do Churn

- 🚀 **Onboarding estratégico:** Programas focados nos 3 primeiros meses para educar e engajar novos clientes.  
- 💰 **Promoção de planos longos:** Incentivar anuais e bienais com descontos e benefícios.  
- 🛒 **Cross-selling inteligente:** Ofertas personalizadas de serviços complementares.  
- 📢 **Campanhas segmentadas:** Abordagens específicas para perfis de pagamento com maior churn.

---

## 📌 Considerações Finais

O combate ao churn deve ser **multidimensional**, combinando:
- Ações preventivas nos primeiros meses.  
- Incentivos para maior engajamento.  
- Contratos mais longos.  
- Uso estratégico de dados para segmentação.  

**Jonathan Mesquita**  
📧 jonathan.mesquita@ph3a.com.br  
🔗 [GitHub](https://github.com/jonathanmesquita)

---

## 📄 Licença
[MIT License](./LICENSE.md) © [Jonathan Mesquita]
