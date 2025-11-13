# Desafio Company DIO
Desafio Criação de Dashboard corporativo com integração MySQL e Azure

<img width="1260" height="708" alt="image" src="https://github.com/user-attachments/assets/8345cbf7-2ff8-450a-bb2d-a20e67aabf4a" />

**Resumo do Projeto – Dashboard Corporativo (MySQL + Power BI)**

O projeto tem como objetivo criar um **dashboard corporativo** utilizando **MySQL** como banco de dados e **Power BI** para análise e visualização, demonstrando o processo completo de **ETL (Extract, Transform, Load)**.

---

### 🎯 **Objetivo**

Desenvolver um banco de dados corporativo, extrair e transformar os dados no Power BI para criação de relatórios e dashboards interativos.

---

### 🛠️ **Tecnologias**

* **MySQL** – Banco de dados relacional
* **Power BI** – Ferramenta de Business Intelligence
* **SQL** – Linguagem de consulta estruturada
* **Azure** – Plataforma de computação em nuvem **>>>Realizado somente localmente, não sendo possível carregar em Nuvem da Azure, devido conta grátis não ter este suporte<<<**
---

### 🔄 **Processo**

As principais **transformações de dados no Power BI** incluíram:

**1.** Ajuste de cabeçalhos e tipos de dados.
**2.** Conversão de valores monetários para tipo **Double Preciso**.
**3.** Verificação de valores nulos e exclusão de colunas desnecessárias.
**4.** Divisão da coluna **address** em **number**, **street**, **city** e **state**.
**5.** **Mescla** das tabelas *employee* e *department* (Inner Join).
**6.** Auto-mescla para associar colaboradores aos seus **gerentes**.
**7.** União dos nomes **Fname + Lname** → **Name**.
**8.** Consolidação de **departamentos e localizações**.
**9.** Agrupamento de colaboradores por gerente para métricas organizacionais.

---

### 🚀 **Execução**

**1.** Executar scripts SQL no MySQL local.
**2.** Conectar o Power BI ao banco de dados.
**3.** Aplicar as transformações descritas.

---

### 📈 **Resultados do Dashboard**

* **01 -** Data com barra de rolagem do período analisado
* **02 -** Qtde. de Departamentos
* **03 -** Qtde. de Funcionários
* **04 -** Média Salarial
* **05 -** Qtde. de Gerentes
* **06 -** Seleção de funcionários
* **07 -** Qtde. de dependentes
* **08 -** Qtde. dependentes por funcionários e **%**
* **09 -** Qtde. de funcionários por Sexo
* **10 -** Média Salarial por nome
* **11 -** Qtde. de funcionários por Cidade
* **12 -** Qtde. de projetos por Setor
* **13 -** Horas dedicadas por projetos
* **14 -** Nome do Projeto e seu Status
    
---

### 🎯 **Conclusões**

O projeto demonstra o ciclo completo de:

* Extração de dados MySQL
* Transformação no Power BI
* Criação de visualizações interativas
* Apoio à tomada de decisão empresarial

---

### 📚 **Aprendizados**

* Importância da limpeza e modelagem de dados
* Uso de mescla e consolidação de tabelas
* Criação de hierarquias organizacionais
* Boas práticas de BI

---
### 🛜 **Projeto Publicado no Power BI online**

<img width="1918" height="970" alt="image" src="https://github.com/user-attachments/assets/20876eb5-6904-490b-8fd7-509a1c667b4e" />



👨‍💻 **Autor:** *Valdery Silva*
📍 Telêmaco Borba, 13 de Novembro de 2025
**Bootcamp DIO Klabin**
