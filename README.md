# 📊 Analise-Estoque-DATA-Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Plotly](https://img.shields.io/badge/Plotly-5.3.1-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-violet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-lightblue)
![Dash](https://img.shields.io/badge/Dash-2.0.0-yellowgreen)

## 🌟 Introdução

O repositório **Analise-Estoque-DATA-Analysis** contém um projeto voltado para a análise de dados de estoque de uma empresa fictícia. O objetivo principal é **otimizar o gerenciamento de estoque** utilizando a metodologia da curva ABC. Essa abordagem ajuda a categorizar produtos com base em sua importância e valor, permitindo decisões mais estratégicas sobre o controle de inventário. 📦

## 🔍 Objetivos do Projeto

- **Identificar produtos críticos:** Classificar os itens de acordo com sua importância no estoque.
- **Otimizar o inventário:** Reduzir custos associados ao excesso de estoque e garantir que itens essenciais estejam sempre disponíveis.
- **Visualizar dados:** Criar dashboards e gráficos interativos para melhor entendimento e apresentação dos dados.

## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para a análise de dados.
- **Pandas**: Para manipulação e análise de dados.
- **Plotly & Seaborn**: Para visualização de dados e criação de gráficos informativos.
- **Matplotlib**: Para visualizações estáticas e detalhadas.
- **Dash**: Para criação de dashboards interativos que facilitam a análise em tempo real.

## 📈 Metodologia da Curva ABC

A curva ABC é uma técnica de categorização que classifica produtos em três categorias:
- **A:** Itens de alto valor, mas baixo volume de consumo (geralmente 20% dos itens representam 80% do valor).
- **B:** Itens de valor médio e consumo moderado.
- **C:** Itens de baixo valor e alto volume de consumo.

### 🧮 Como Funciona?

1. **Coleta de Dados:** Os dados de estoque são coletados e armazenados em um DataFrame do Pandas.
2. **Classificação:** Os produtos são classificados nas categorias A, B ou C com base em seu valor total e quantidade.
3. **Visualização:** Gráficos são gerados para ilustrar a distribuição dos produtos e auxiliar na tomada de decisões.

## 📊 Visualizações

As seguintes visualizações foram criadas para ilustrar os dados do estoque:

- **Gráfico de Barras**: Mostrando a quantidade de itens em cada categoria (A, B, C).
- **Mapa de Calor**: Para identificar rapidamente as categorias de estoque com maior concentração.
- **Gráficos de Dispersão**: Para visualizar a relação entre o valor e a quantidade dos produtos.

  
![distribuicao_curva_abc_013fbeca158780ba8918317c72d6acbc](https://github.com/user-attachments/assets/cb0a806f-3fed-4423-96fd-db1df366614f)
![histograma_vendas_totais_produto_a1b586847a268dfa535cd9be8e10327d](https://github.com/user-attachments/assets/dfce0648-4b14-4a95-b25a-d5ed4712b15d)
![vendas_por_categoria_fa866b48b53f8f17804280cf3413180e](https://github.com/user-attachments/assets/82f9d68c-4ce7-4354-8db6-1e8ba46ae536)
![vendas_por_loja_19f5574771407e5d216d2f57ab62ac4a](https://github.com/user-attachments/assets/68352eb1-0fb3-4d7e-b941-c1f310c0a715)
![vendas_diarias_loja_08b722827a8874da04fd49e751f89eb6](https://github.com/user-attachments/assets/0dbbf0e6-552e-4215-8aff-403627198b0f)
![vendas_diarias_categoria_9a41823f19d279b83e5c8ed60bb7b8fe](https://github.com/user-attachments/assets/85a0d931-73a5-48ed-a5b4-7df8231958a8)
![preco_vs_quantidade_2931a7dafcc329c7f94ceed96ad3ff9f](https://github.com/user-attachments/assets/156a6207-40ff-47c3-93c6-524d31b76b9e)
![valor_transacao_vs_categoria_5ba1f514fed11c68df3f4dae33584637](https://github.com/user-attachments/assets/ec189358-cb87-4b3b-80e3-b98988c5edcb)
![distribuicao_vendas_categoria_8ebbb118f86a372f7630f74704628378](https://github.com/user-attachments/assets/5a5c71c2-0d22-46ca-9029-9b78aa9211b4)
![distribuicao_vendas_loja_6eaf622866ee8200b03be74a05aa0d49](https://github.com/user-attachments/assets/4b78241e-73e9-4448-8e46-769fcaf21778)
![distribuicao_vendas_loja_box_ea117de39a42a66e52bbaa7aadfce6d9](https://github.com/user-attachments/assets/ea6c0f59-801a-4192-ba48-f36b8cf0512f)
![vendas_categoria_data_empilhadas_12a466375e24ae7223215fd47df07fb1](https://github.com/user-attachments/assets/c9c8235d-5cc3-4efd-a057-b3e78763b114)
![evolucao_vendas_categoria_area_c0b0a0d02372affd5a062fcf188cca6b](https://github.com/user-attachments/assets/46171b33-8723-4ad7-bedf-2f8fd1ee6cb1)
![evolucao_vendas_loja_area_5dd29b0f071eba527808ab903d831d42](https://github.com/user-attachments/assets/82f1c41d-4fb4-492f-9e58-40784ad4fb96)
![evolucao_estoque_categoria_7c51780f34c509e9fe027520b08b53c5](https://github.com/user-attachments/assets/52e43d04-268a-4d09-be21-e3c63629f7ea)
![evolucao_estoque_loja_a4c6f7f4d01218bc88185c796729802e](https://github.com/user-attachments/assets/9be4d9fc-12dd-4fe3-8fa5-ca857c69103e)
![produtos_mais_vendidos_291749263b37050c8b025cbdf6ac954a](https://github.com/user-attachments/assets/03c56860-96ec-499b-a423-206532f1ee5f)
![produtos_curva_abc_a0656fa9f19f255d92d9b0d766ae6ea3](https://github.com/user-attachments/assets/9bec3b3f-739a-4c46-9d6f-6fd14b689bcd)
![produtos_maior_valor_transacao_a80836f1f254f2224a4de56d654a850c](https://github.com/user-attachments/assets/a592f428-cd5e-4d61-b47b-62c06e728b0e)
![quantidade_vs_valor_transacao_curva_a_6b198b7a2943cfa8524a4ce03fe09544](https://github.com/user-attachments/assets/259f1a2e-a760-42de-bef6-86642c14ea7b)
![distribuicao_vendas_categoria_box_fd7cd8b537c9a61e604b4a61cf3f309d](https://github.com/user-attachments/assets/223a343b-2d3b-499d-b332-032f59c56161)
![vendas_categoria_loja_empilhadas_939db59372448b722de59c31c8a11355](https://github.com/user-attachments/assets/7db902af-2b79-4f58-b996-5beb76e3448b)
![curva_abc_estoque_f98812b6ad](https://github.com/user-attachments/assets/d647fdc4-dc15-4ece-9538-244d767d8c79)
![curva_abc_estoque_45c81f26e2](https://github.com/user-attachments/assets/f0baa516-490d-407f-ad3c-f5ad73439a78)
![produtos_parados_19b673fedc](https://github.com/user-attachments/assets/579e9b07-d633-49cd-8981-1d753e769a95)
![curva_abc_estoque_d1797bca19](https://github.com/user-attachments/assets/b791421a-072d-4655-a51d-628f690e7a44)
![produtos_parados_41d7185cd2](https://github.com/user-attachments/assets/1b34eb17-0b51-446d-9646-b306c4bf0032)
![maior_movimentacao_47c3e30186](https://github.com/user-attachments/assets/341baa24-d942-4d0b-b665-d00ed70f611a)
![estoque_tempo_ff1ab080a5](https://github.com/user-attachments/assets/0077c001-6d84-40b7-a90f-083fd9ac6127)
![valor_estoque_mes_2c14308d81](https://github.com/user-attachments/assets/00461f34-3e6e-4fea-94a3-0b4b1a92e752)
![categorias_comparacao_072fb572f4](https://github.com/user-attachments/assets/d4e901ed-4860-4b55-9172-ba97f8df3c69)
![maior_valor_movimentacao_01f48e283a](https://github.com/user-attachments/assets/33027557-04e5-4901-8355-05895bf95d8c)
![tendencia_entrada_saida_a2e9e550de](https://github.com/user-attachments/assets/62066413-5273-4038-9d21-153da10e9785)
![contribuicao_categoria_c6446eba77](https://github.com/user-attachments/assets/c9e62994-678b-4aa7-8ac5-974e382cb784)
![produtos_criticos_dcb83f1ae3](https://github.com/user-attachments/assets/2b165519-fd50-4f4b-b551-950dd8f1d0e5)
![produtos_reposicao_f78af5d5ba](https://github.com/user-attachments/assets/f959f78f-749d-49aa-89cb-89cd5c01731b)


## 📨 Envio de Relatórios

Os resultados das análises podem ser exportados em formatos como PDF ou Excel para facilitar o compartilhamento com a equipe de gestão. Relatórios detalhados são gerados automaticamente utilizando as bibliotecas de visualização.


