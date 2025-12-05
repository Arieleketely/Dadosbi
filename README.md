# Projeto 1 - Controle de saúde na pasta banco de dados:

## 📌 Descrição
Sistema de Gestão de Saúde

Este projeto representa um sistema de banco de dados para gestão de informações em saúde, estruturado em um modelo de Data Warehouse com esquema estrela, ideal para análises multidimensionais e relatórios gerenciais. Ele integra dados sobre pacientes, doenças, medicamentos, hospitais e planos de saúde, centralizados em uma tabela de fatos.


## 🧬 Estrutura do Modelo Estrela

• 	Tabela Fato (): 

É o núcleo analítico do sistema, conectando todas as dimensões por meio de chaves estrangeiras. Cada registro representa uma ocorrência de tratamento ou atendimento, relacionando:

• 	Pessoa (paciente)

• 	Doença

• 	Medicamento

• 	Hospital

• 	Plano de saúde

## 🧬  Tabelas Dimensionais 

1. 	Pessoa


• 	Armazena dados demográficos e de contato dos pacientes.
• 	Permite análises por localização (estado, cidade, bairro) e perfil do paciente.

2. 	Doença


• 	Contém os nomes das doenças registradas.

• 	Suporta estudos epidemiológicos e estatísticas de incidência.

3. 	Medicamento


• 	Detalha os medicamentos utilizados, incluindo forma de administração, estado físico, dosagem e frequência.

• 	Essencial para análises de prescrição e controle de estoque.

4. 	Hospital


• 	Registra os dados dos hospitais envolvidos nos atendimentos.

• 	Permite avaliar desempenho por unidade de saúde e região.

5. 	Plano


• 	Representa os planos de saúde vinculados aos atendimentos.

• 	Suporta análises de cobertura, rede credenciada e perfil de usuários.

## 🎯 Objetivo do Sistema

O sistema foi projetado para:

• 	Monitorar tratamentos e interações entre pacientes, doenças e medicamentos.

• 	Gerar relatórios gerenciais por região, hospital, plano ou tipo de doença.

• 	Apoiar decisões estratégicas em saúde pública e gestão hospitalar.

• 	Facilitar auditorias e controle de qualidade nos serviços prestados.



# 🤰 Projeto 2: Monitoramento de Diabetes Gestacional na pasta digital innovation one

## 📌 Descrição
Este projeto tem como objetivo **controlar e analisar dados de gestantes com risco de diabetes gestacional**, utilizando indicadores clínicos e demográficos. A solução foi desenvolvida para ser explorada em **Power BI**, permitindo a criação de dashboards interativos e relatórios dinâmicos.

## 🧬 Variáveis Monitoradas
- **IMC (Índice de Massa Corporal)**
- **Glicose**
- **Idade**
- **Insulina**
- **Número de gestações**
- **Diagnóstico de diabetes** (Sim/Não)

## 🎯 Objetivos
- Identificar gestantes com maior risco de desenvolver diabetes.
- Acompanhar indicadores clínicos ao longo da gestação.
- Apoiar profissionais de saúde na tomada de decisão.
- Gerar relatórios visuais e interativos para análise.

## 📊 Power BI
O projeto utiliza **Power BI** para:
- Criar **dashboards interativos** com gráficos de dispersão, histogramas e indicadores.
- Permitir **filtros dinâmicos** por idade, IMC ou número de gestações.
- Exibir **KPIs** como média de glicose, percentual de gestantes com diabetes e distribuição por faixa etária.

## 🚀 Benefícios
- **Prevenção precoce** de complicações gestacionais.
- **Melhoria na qualidade do atendimento** médico.
- **Redução de custos hospitalares** com internações evitáveis.
- **Empoderamento da paciente**, que pode acompanhar seus próprios indicadores.

---

👩‍⚕️ Este projeto é voltado para profissionais de saúde, pesquisadores e gestores hospitalares que desejam **monitorar e analisar dados de diabetes gestacional** de forma prática e visual.


