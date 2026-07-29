# 👥 Dashboard Analítico de RH com Power BI

## 📌 Sobre o Projeto
Este projeto foi desenvolvido utilizando **Microsoft Power BI** com o objetivo de analisar dados de Recursos Humanos de uma empresa, permitindo acompanhar o perfil dos colaboradores, indicadores de diversidade, remuneração, engajamento e disponibilidade para hora extra.

O dashboard reúne cartões de indicadores, filtros interativos e gráficos que facilitam a tomada de decisão estratégica pela área de RH, oferecendo uma visão clara sobre o quadro de funcionários da organização.

---

## 📊 Funcionalidades do Dashboard
O dashboard possui os seguintes recursos:

- 👥 Total de funcionários da empresa
- ⚧ Distribuição por gênero (feminino e masculino), em valor absoluto e percentual
- 🎂 Filtro por faixa etária (idade)
- 💰 Salário médio dos colaboradores
- ⏳ Experiência média (em anos) do quadro de funcionários
- 📊 Total de funcionários por função (Cientista de Dados, Analista de Dados, Engenheiro de IA, Arquiteto de Dados, Engenheiro de Dados, Engenheiro Analítico)
- 🕒 Percentual de funcionários disponíveis para hora extra
- 🔥 Nível de envolvimento no trabalho (Médio, Baixo, Alto, Ruim)

---

## 🗂 Modelagem dos Dados
O projeto utiliza uma base de dados de RH (**DatasetRH**) contendo informações cadastrais e de desempenho dos funcionários, além de uma tabela de **medidas** desenvolvida em DAX para os cálculos exibidos no dashboard.

### Campos utilizados (DatasetRH)
- Id_Funcionario
- Genero
- Departamento
- Funcao
- Estado Civil
- Anos_Experiencia
- Anos_na_Empresa
- Anos_Funcao_Atual
- Anos_com_Gerente_Atual
- Anos_Desde_Ultima_Promocao
- Aval_Performance
- Envolvimento_trabalho
- Disponivel_Hora_Extra

### Medidas (DAX)
- % Feminino
- % Masculino
- % Promover
- % NaoPromover
- Salário médio
- Total_func
- Total_feminino
- Total_masculino
- Total_func_promover
- Total_func_Naopromover

A modelagem foi estruturada separando os dados brutos (DatasetRH) das medidas calculadas (medidas), facilitando a manutenção e a organização do modelo em DAX.

---

## 🛠 Tecnologias Utilizadas
- Microsoft Power BI
- Power Query
- DAX
- Modelagem de Dados
- Visualizações Interativas
- Análise de Dados de RH (People Analytics)

---

## 📈 Principais Análises
Com este dashboard é possível:

- Conhecer o perfil demográfico da empresa (gênero e idade);
- Avaliar a distribuição de funcionários entre as diferentes funções;
- Analisar o salário médio e a experiência média do quadro de colaboradores;
- Identificar o percentual de funcionários disponíveis para hora extra;
- Avaliar o nível de envolvimento dos colaboradores no trabalho;
- Filtrar os resultados por faixa etária para análises mais específicas.

---

## 📷 Prévia do Dashboard

### Dashboard Principal
![dashboard](imagens/dashboard.png)

### Modelo de Dados
![modelagem](imagens/modelagem.png)

---

## 🎯 Competências Demonstradas
Este projeto demonstra conhecimentos em:

- Modelagem de Dados
- Power Query
- DAX
- Inteligência de Negócios (Business Intelligence)
- People Analytics / Análise de RH
- Construção de Indicadores (KPIs)
- Storytelling com Dados
- Desenvolvimento de Dashboards Interativos

---

## 📁 Estrutura do Repositório
```
📂 HR-Analytics-Dashboard
│
├── Dashboard.pbix
├── README.md
├── imagens
│   ├── dashboard.png
│   └── modelagem.png
└── dataset
```

---

## 🚀 Como visualizar
1. Faça o download do arquivo `.pbix`.
2. Abra utilizando o **Power BI Desktop**.
3. Navegue entre as páginas do relatório.

---

## 👨‍💻 Autor
**José Rafael Santos Pereira**

Desenvolvendo projetos práticos | Power BI | SQL | Python | Business Intelligence


GitHub: https://github.com/ZeRafaSp/

LinkedIn: https://www.linkedin.com/in/rafaelsantospereirarsp/
