# 🎓 Projeto de Modelagem Dimensional com MySQL - Klabin | DIO

Este projeto faz parte do curso **Excel e Power BI Dashboards**, promovido pela **Klabin em parceria com a DIO**.

---

## 🧠 Desafio Proposto

Criar um modelo dimensional (Esquema Estrela) com foco na **análise dos professores** de uma universidade, utilizando o **MySQL** como banco de dados.

---

## 📊 Objetivo

- Estruturar um **modelo dimensional** para armazenar e consultar dados relacionados a professores, cursos, disciplinas e departamentos.
- Preparar a base para possíveis análises futuras com **Power BI ou Excel**.

---

## 📐 Modelagem Dimensional

O modelo foi construído em formato **Star Schema**, com a **tabela fato** centralizando as métricas e várias **tabelas dimensão** para os detalhes descritivos.

### 🔸 Tabela Fato: `FatoProfessor`

Contém os dados relacionados às turmas ministradas por professores:

- `id_professor`
- `id_disciplina`
- `id_curso`
- `id_departamento`
- `id_data_oferta`
- `quantidade_turmas`
- `carga_total`

### 🔹 Tabelas Dimensão

- `Professor` – dados dos professores
- `Disciplina` – informações das disciplinas
- `Curso` – cursos oferecidos
- `Departamento` – departamentos da universidade
- `Tempo` – dimensão de data com granularidade em semestre, mês e trimestre

---

## 🧰 Ferramentas Utilizadas

- **MySQL Workbench** (modelagem e execução de queries)
- **MySQL Server** (banco de dados)

---



