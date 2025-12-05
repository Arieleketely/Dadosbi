# Controle de saúde
Projeto banco de dados:

 Descrição do Projeto: Sistema de Gestão de Saúde
Este projeto representa um sistema de banco de dados para gestão de informações em saúde, estruturado em um modelo de Data Warehouse com esquema estrela, ideal para análises multidimensionais e relatórios gerenciais. Ele integra dados sobre pacientes, doenças, medicamentos, hospitais e planos de saúde, centralizados em uma tabela de fatos.


Estrutura do Modelo Estrela

• 	Tabela Fato (): É o núcleo analítico do sistema, conectando todas as dimensões por meio de chaves estrangeiras. Cada registro representa uma ocorrência de tratamento ou atendimento, relacionando:

• 	Pessoa (paciente)

• 	Doença

• 	Medicamento

• 	Hospital

• 	Plano de saúde

 Tabelas Dimensionais

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

Objetivo do Sistema

O sistema foi projetado para:

• 	Monitorar tratamentos e interações entre pacientes, doenças e medicamentos.
• 	Gerar relatórios gerenciais por região, hospital, plano ou tipo de doença.
• 	Apoiar decisões estratégicas em saúde pública e gestão hospitalar.
• 	Facilitar auditorias e controle de qualidade nos serviços prestados.
