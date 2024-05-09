# Desafio de Projeto: Processando e Transformando Dados com Power BI



O objetivo geral do processamento e transformação de dados com o Power BI é preparar os dados para que possam ser usados para análise e geração de relatórios. Os dados brutos geralmente estão em um formato que não pode ser facilmente usado pelo Power BI, portanto, é necessário processá-los e transformá-los para que possam ser usados de forma eficaz. 

## **Objetivos Específicos**

Para atingir o objetivo geral, o processamento e a transformação de dados com o Power BI têm os seguintes objetivos específicos:

- Limpar os dados: Isso envolve remover valores ausentes, corrigir erros e aplicar regras de validação.
- Transformar os dados: Isso envolve aplicar cálculos, fórmulas e outras operações aos dados para criar novos dados.
- Carregar os dados no Power BI: Depois que os dados são processados e transformados, eles podem ser carregados no Power BI para análise e geração de relatórios.

### **Resultados Esperados**

Os resultados esperados do processamento e transformação de dados com o Power BI incluem:

- Dados limpos e transformados que podem ser usados facilmente pelo Power BI.
- Um modelo de dados otimizado para análise e geração de relatórios.
- Insights valiosos obtidos a partir da análise de dados.



### **Requisitos:**

### **Estruturando o Projeto**

- Definir o escopo do projeto
- Criar um cronograma do projeto
- Identificar as partes interessadas do projeto

### **Documentação**

- Criar um documento de requisitos do projeto
- Criar um documento de design do projeto
- Criar um documento de plano de teste

### **Definindo Modelos, Serviços e Lógica de Negócios**

- Identificar os modelos de dados necessários
- Identificar os serviços necessários
- Definir a lógica de negócios necessária

### **Integrando e Testando**

- Integrar os dados das várias fontes
- Testar os dados transformados
- Implantar os dados transformados no Power BI

### **Conclusão com Aprendizado e Aplicabilidade Prática**

- Resumir os resultados do projeto
- Identificar as lições aprendidas
- Descrever como o projeto pode ser aplicado na prática

### **Resultados Esperados:**

- Dados limpos e transformados que podem ser usados facilmente pelo Power BI
- Um modelo de dados otimizado para análise e geração de relatórios
- Insights valiosos obtidos a partir da análise de dados

### **Benefícios:**

- Maior eficiência
- Melhor tomada de decisão
- Aumento das vendas
- Redução de custos
- Maior satisfação do cliente



## **Configuração**



• Configurar o setup de banco de dados na Azure</br>
• Popular o servidor com script fornecido</br>
• Integre o MySQL com Power BI</br>
• Realize as transformações indicadas</br>

### **Processando Dados no Power BI**

O Power BI oferece várias ferramentas para processar dados, incluindo:

- O limpador de dados: O limpador de dados pode ser usado para remover valores ausentes, corrigir erros de dados e aplicar regras de validação.
- O conversor de dados: O conversor de dados pode ser usado para converter dados entre diferentes formatos.
- O agrupador de dados: O agrupador de dados pode ser usado para agrupar dados em intervalos ou por categorias.
- O particionador de dados: O particionador de dados pode ser usado para dividir dados em partes menores para facilitar o processamento.

### Como Executar
1. Criação de uma instância na Azure para MySQL
2. Criar o Banco de dados com base disponível no github
3. Integração do Power BI com MySQL no Azure
4. Verificar problemas na base a fim de realizar a transformação dos
dados

### Diretrizes para transformação dos dados
1.	Verifique os cabeçalhos e tipos de dados
2.	Modifique os valores monetários para o tipo double preciso
3.	Verifique a existência dos nulos e analise a remoção
4.	Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
5.	Verifique se há algum departamento sem gerente
6.	Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
7.	Verifique o número de horas dos projetos
8.	Separar colunas complexas
9.	Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
10.	Neste processo elimine as colunas desnecessárias. 
11.	Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
12.	Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
13.	Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
14.	Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir. 
![Imagem1](https://github.com/elisamaribeiro/my-projects-santander-dev-week-23/assets/125142048/605a14d9-f75b-40bb-b37b-82909faddcee)
![Imagem2](https://github.com/elisamaribeiro/my-projects-santander-dev-week-23/assets/125142048/fd8e6033-178f-4dad-a3a3-dd041734a536)
15.	Agrupe os dados a fim de saber quantos colaboradores existem por gerente
16.	Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela



## **Conclusão**

O processamento e a transformação de dados são processos essenciais para criar relatórios e painéis interativos no Power BI. O Power BI oferece várias ferramentas para processar e transformar dados, tornando-o uma ferramenta poderosa para a análise de dados.

## **Aplicabilidade Prática**

O processamento e a transformação de dados podem ser usados para uma variedade de propósitos, incluindo:

- Análise de dados: O processamento e a transformação de dados podem ser usados para analisar dados e identificar tendências e padrões.
- Relatórios: O processamento e a transformação de dados podem ser usados para criar relatórios interativos e informativos.
- Painéis: O processamento e a transformação de dados podem ser usados para criar painéis interativos que ajudam a visualizar dados.
