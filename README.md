# **RecomendaIAgro | CultivAI**

### *Global Solution – 2º Semestre (FIAP)*

Plataforma inteligente para apoiar pequenos e médios produtores rurais com recomendações personalizadas, insights agronômicos e visão 360° do cliente.
Combinando **IA Colaborativa**, **Apriori**, **Data Lakehouse**, **Engenharia de Dados** e **Dashboard MVP**, o projeto une tecnologia, impacto e estratégia — como apresentado no pitch oficial .

---

# **Visão Geral do Projeto**

O agronegócio vive uma transformação digital. Contudo, como mostrado nas páginas 2 e 3 do pitch, ainda há desafios críticos :

* Comunicação comercial guiada por intuição
* Dados dispersos em sistemas diferentes
* Falta de personalização no atendimento
* Rejeição a interações automatizadas
* Ausência de visão integrada do cliente

O **RecomendaIAgro** surge para resolver esse cenário com **IA colaborativa**, apoiando o humano — sem substituí-lo.

### **Objetivo da solução**

Apoiar o vendedor com inteligência, não automatizar o relacionamento.
Levar dados, padrões, histórico e recomendações para um **painel único**, intuitivo e estratégico.

---

# **IA Colaborativa – O Futuro do Agro**

A solução se baseia em:

* automação inteligente
* decisões orientadas por dados
* profissional mais consultivo
* relações mais humanas apoiadas por insights
* menos tarefas operacionais, mais estratégia

A plataforma agrega informação, gera contexto e permite ações rápidas, aumentando eficiência e qualidade do atendimento.

---

# **3. A Solução: RecomendaIAgro**

A solução é composta por cinco pilares:

### **✓ Visão 360° do cliente**

Histórico, perfil, compras, categoria mais consumida, ticket médio.

### **✓ Recomendações Inteligentes (Apriori)**

Algoritmo baseado em:

* suporte
* confiança
* lift

### **✓ Histórico Comercial Unificado**

Visualização financeira completa e evolução das compras.

### **✓ Ações Rápidas**

Ligar, enviar WhatsApp, agendar retorno.

### **✓ Insights Agronômicos**

Práticas, sazonalidade e indicações estratégicas.

---

# **Arquitetura da Solução**

A arquitetura mostra uma visão completa e escalável da solução :

```
1. Ingestão
   - Dados de ERP, CRM e catálogos → AWS Transfer Family

2. Processamento
   - Armazenamento no S3 (Raw)
   - Transformações e extração de regras via AWS Glue

3. Governança
   - Catálogo central no AWS Glue Data Catalog

4. Query e Lakehouse
   - Athena para leitura rápida e consultas SQL

5. Consumo em Tempo Real
   - API REST via API Gateway
   - Painel Web (Streamlit)
   - Recomendações sob demanda
```

Essa arquitetura garante:
✔ escalabilidade
✔ armazenamento estruturado
✔ uso em tempo real
✔ governança
✔ integração contínua

---

# **Base de Dados**

### **• Produtos**

Categoria, composição, atributos → alimenta Apriori.

### **• Clientes**

Localização, histórico, segmento, perfil comercial → Visão 360°.

### **• Cestas de Compra**

Base transacional que sustenta o Apriori.

### **• Regras Apriori**

Extraídas para alimentar o motor de recomendação.

---

# **Resultados do Modelo (Apriori)**

Os resultados incluem: 

* Regras com suporte, confiança e lift
* Distribuição por categoria (fungicida, herbicida, inseticida)
* Análise exclusiva por cliente
* Recomendações personalizadas e justificadas

---

# **MVP – Dashboard (Streamlit)**

### **✓ Seção 1 – Informações do Cliente + Sidebar**

Contexto humano + agronômico.

### **✓ Seção 2 – Perfil Comercial**

* Curva ABC
* Evolução de compras
* Ticket médio
* Categoria predominante

### **✓ Seção 3 – Comportamento Agronômico**

### **✓ Seção 4 – Recomendações IA (Apriori)**

O coração da solução.

### **✓ Seção 5 – Próximas Ações**

Um cockpit operacional para o representante comercial.

---

# **Conexão com os ODS**

A seguir as evidencia os impactos nos ODS 8, 9, 10 e 12:

* Trabalho decente e crescimento econômico
* Inovação e infraestrutura
* Redução das desigualdades
* Consumo responsável

---

# **Equipe**

*Carlos Vinícius Rodrigues Silva*
*Gabriela Sena da Silva*
*Gustavo Almeira Scardini*
*Tatiana Espinola*
*Vitor Fernandes Antunes*

---

# 📩 **Contato**

**Gabriela Sena da Silva**

🔗 [https://www.linkedin.com/in/gabrielasena](https://www.linkedin.com/in/gabrielasena)

📧 [gabisena@outlook.com](mailto:gabisena@outlook.com)
