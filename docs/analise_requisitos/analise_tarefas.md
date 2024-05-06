## Introdução
A análise de tarefas é muito importante para compreender como os usuários realizam suas atividades, os objetivos que buscam alcançar e os desafios enfrentados no processo. Segundo Diaper (2003), ela engloba métodos para coletar, classificar e interpretar dados sobre o desempenho de sistemas que incluem pelo menos uma pessoa como componente. Essa abordagem é essencial tanto para a análise da situação atual quanto para o (re)design de sistemas computacionais, além de ser fundamental na avaliação de intervenções que introduzem novos sistemas.

### Metodologia
Entre os métodos mais comuns de análise de tarefas, destacam-se a Análise Hierárquica de Tarefas (HTA), que descreve as tarefas em uma hierarquia; o GOMS, que desmembra as tarefas em metas, operadores, métodos e regras de seleção; e o ConcurTaskTrees (CTT), que permite representar visualmente as tarefas e as condições de concorrência entre elas.

Para cada funcionalidade analisada, iremos aplicar pelo menos dois métodos. Abaixo, descrevemos brevemente cada um deles:

### Análise Hierárquica de Tarefas (HTA)

### GOMS (Goals, Operators, Methods, and Selection Rules)

### Árvores de Tarefas Concorrentes (ConcurTaskTrees – CTT)

## Análise de Tarefas

### 1. Solicitação de Requerimento Padrão
A Solicitação de Requerimento Padrão refere-se ao processo de regularização legal de edificações junto ao Corpo de Bombeiros do Rio de Janeiro. Isso envolve o preenchimento e submissão de um requerimento padrão.

Para essa análise, foram aplicadas as técnicas de Análise Hierárquica de Tarefas e Árvores de Tarefas Concorrentes.

**Análise Hierárquica de Tarefas:** A figura 1 e a tabela 1 apresentam a análise hierárquica dessa tarefa em sua forma textual e de diagrama, respectivamente.

|    Objetivos/Operações    |    Problemas e recomendações    |
| :-----------------------: | ------------------------------- | 
| 0. Solicitar requerimento padrão 1>2    | **input:** Acessar o menu de cidadão na tela inicial.<br> **feedback:** Carregar formulário para início da solicitação. <br> **plano:** Gerar o requerimento padrão solicitado.<br> **recomendação:** Fazer tratamento de erros do formulário. | 
| 1. Informar dados do requerente e da edificação 1+2  | **plano:** Informar dados do requerente; DAEM, registro do CBMERJ, classificação da edificação, tipos de solicitação e responsável técnico. |
| 1.1 Informar nome, endereço, telefone, cpf e registro do requerente; DAEM e registro do CBMERJ. |
| 1.2 Informar classificação da edificação, tipos de solicitação e responsável técnico 1/2 |
| 2. Confirmar o recebimento das informações | **ação:** Disponibilizar para o contribuinte o requerimento para download.<br> **recomendação:** Retornar mensagens de erro claras quando alguma das informação não é preenchida corretamente. |
<p align="center">Tabela 1: Análise hierárquica da tarefa "Solicitação de Requerimento Padrão" (Fonte: Bruna Lima, 2024). </p>

![](img/hta-diagrama-tarefa-1.png)
<p align="center">Figura 1 - Diagrama da Análise hierárquica da "Solicitação de Requerimento Padrão" (Fonte: Bruna Lima, 2024). </p>

**Árvores de Tarefas Concorrentes:** A figura 2 contém a análise representada em diagrama da tarefa de "Solicitação de Requerimento Padrão" com uso da técnica de Árvores de Tarefas Concorrentes.

![](img/ctt-diagrama-tarefa-1.png)
<p align="center">Figura 2 - Diagrama da Árvores de Tarefas Concorrentes da "Solicitação de Requerimento Padrão" (Fonte: Bruna Lima, 2024). </p>

### 2. Locais certificados
<p style="text-align: justify;">A aba "Locais certificados" é uma funcionalidade que disponibiliza uma relação de locais de Diversões Públicas autorizados a funcionar. Para a análise dessa funcionalidade, foram aplicadas as técnicas de Análise Hierárquica de Tarefas e Árvores de Tarefas Concorrentes. </p>

**Análise Hierárquica de Tarefas:** A tabela 2 apresenta a análise hierárquica dessa tarefa em sua forma textual.

|    Objetivos/Operações    |    Problemas e recomendações    |
| :-----------------------: | ------------------------------- | 
| 0. Acessar a lista de Locais de Diversões Públicas Autorizados a funcionar 1 + 2. | **input:** Acessar o menu de cidadão na tela inicial.<br> **feedback:** Apresentar a lista de locais autorizados. <br> **plano:** Exibir informações atualizadas sobre os locais de diversão pública autorizados.<br> **recomendação:** Implementar filtros de pesquisa para facilitar a localização dos estabelecimentos. | 
| 1. Visualizar dados dos locais e suas autorizações 1 + 2.  | **plano:** Exibir informações detalhadas sobre cada local, incluindo: nome, endereço, capacidade de lotação, validade da autorização, classificação da finalidade da edificação e responsáveis pela edificação. |
| 2. Confirmar a disponibilidade da lista atualizada. | **ação:** Disponibilizar lista para visualização e download. <br>**recomendação:** Garantir que a lista seja regularmente atualizada para refletir as mais recentes autorizações concedidas.  |
| 3. Facilitar o acesso à informação. | **ação:** Disponibilizar uma interface de fácil navegação e busca rápida. <br>**recomendação:** Certificar-se de que a plataforma seja acessível em diferentes dispositivos e navegadores. |
<p align="center">Tabela 2: Análise hierárquica da aba "Locais certificados" (Fonte: Daniela Alarcão, 2024). </p>

**Árvores de Tarefas Concorrentes:** A figura 3 apresenta a análise dessa tarefa representada em diagrama com o uso da técnica de Árvores de Tarefas Concorrentes. 
![](img/ÁrvoreDani.png)
<p align="center">Figura 3 - Diagrama da Árvores de Tarefas Concorrentes de "Locais certificados" (Fonte: Daniela Alarcão, 2024). </p>


### 3. Acesso aos recursos de guia para redes sociais



## Bibliografia
> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. Interação Humano-Computador e Experiência do usuário. (2021)

## Histórico de Versões

| Versão |    Data    | Descrição                                 | Autor(es)                                       | Revisor(es)                                    |
| ------ | :--------: | ----------------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| `1.0`   | 13/04/2024 | Criação da página                         | [Mariana Letícia](https://github.com/Marianannn) |     [Bruna Lima](https://github.com/libruna)     |
| `1.1`   | 20/04/2024 | Adição da introdução, metodologia e da tarefa 1                         | [Bruna Lima](https://github.com/libruna) |     [Genilson Silva](https://github.com/GenilsonJrs)     |
| `1.2`   | 21/04/2024 | Adição da tarefa 2                       | [Genilson Silva](https://github.com/GenilsonJrs) |     [Mariana Letícia](https://github.com/Marianannn)     |

