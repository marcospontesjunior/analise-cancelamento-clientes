# Análise de Perfil de Cancelamento dos Clientes

###
[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](https://opensource.org/licenses/MIT) 

### Sobre:

Este projeto visa analisar uma base de dados para verificar o perfil de cancelamento dos clientes.

### Proposta:

A proposta do projeto é extrair informações de uma base de dados em formato .csv para realizar uma análise e identificar o perfil de cancelamento dos clientes. Com base nessa análise, serão propostas soluções efetivas para diminuir a quantidade de cancelamentos.

### Estrutura do Repositório:
- <strong>data:</strong> Encontrará o arquivo **.csv** com os dados utilizados para a análise.
- <strong>img:</strong> Aqui você encontrará os prints obtidos na análise.
- <strong>notebook:</strong> Este diretório contém o notebook Jupyter onde a análise foi realizada e os resultados obtidos.
- <strong>readme_translated:</strong> This repository contains the **PDF** with the **report** translated into English.

### Linguagem Utilizada:
###
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=white&color=black)

### Bibliotecas Utilizadas:
###
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white&color=black) 	![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white&color=black)

### Metodologia:

Inicialmente, utilizamos a biblioteca Pandas para importar e ler a base de dados.

img

O próximo passo foi realizar o tratamento e a limpeza dos dados. Utilizamos o método .info para verificar o tipo de dados com o qual estávamos trabalhando. Removemos as linhas que continham valores nulos e a coluna “CustomerID”. 

img

Em seguida, realizamos uma análise para verificar a taxa de cancelamento. Utilizamos o método .value_counts() para obter a quantidade de cancelamentos e em seguida aplicamos o método .apply junto da função lambda parar formatar os valores e verificar os números em porcentagem. Para a identificação do “Cancelou” e “Não Cancelou” foi usado o tipo de dados booleano onde 1 corresponde a “Cancelou” e 0 corresponde a “Não Cancelou”. 

img

Verificamos que houve um total de 56.71% de cancelamento.

Para ajudar na análise vamos para a criação de gráficos para melhor visualização. Foi utilizado a biblioteca Plotly com o método de repetição for.

### Análise:

A partir dos gráficos gerados, a análise destacou quatro fatores que podem ser relacionados ao cancelamento de clientes:

- Idade:

img

  Clientes com idade acima de 50 anos apresentam uma taxa de cancelamento mais elevada, sugerindo um desafio especifico em relação à retenção nessa faixa etária.

- Ligação ao Call Center:

Observou-se que clientes que realizam mais de 5 ligações ao call center tem maior probabilidade de cancelar suas assinaturas. Isso pode sugerir que a insatisfação ou dificuldades enfrentadas pelos clientes ao entrar em contato com o suporte estão levando ao     cancelamento.

- Dias de Atraso:

img

Clientes que acumulam mais de 20 dias de atraso no pagamento estão inclinados a cancelar suas assinaturas. Esse padrão sugere que a inadimplência pode estar relacionada ao aumento do cancelamento de clientes.

- Duração do Contrato:

img

Os clientes que optam pelo plano mensal têm uma tendencia mais forte de cancelamento em comparação com os planos anuais e trimestrais. Isso pode indicar que clientes com panos mais curtos podem ser mais propensos a desistir do serviço.

### Conclusão:

Após uma a análise, constatou-se que clientes com idade superior a 50 anos apresentam uma taxa de cancelamento mais significativa. Além disso, verificou-se que os clientes que realizam mais de 5 ligações ao call center têm uma probabilidade maior de optar pelo cancelamento. Adicionalmente, aqueles que acumulam mais de 20 dias de atraso no pagamento demonstram uma propensão maior para cancelar suas assinaturas. Por fim, os clientes que escolhem o plano mensal mostram uma tendência mais acentuada em relação ao cancelamento.

É possível propor algumas soluções para diminuir a quantidade de cancelamentos e melhorar a retenção de clientes. Entre elas:

- Certificar-se de que os serviços e produtos sejam de fácil uso e compreensão, especialmente para clientes mais velhos como interfaces intuitivas, suporte técnico acessível e matérias de comunicação claros.

- Aperfeiçoar o atendimento ao cliente no call center, buscando resolver os problemas e dúvidas dos clientes de forma mais rápida e eficiente.

- Implementar medidas para reduzir a inadimplência, como lembretes de pagamento e opções de parcelamento.

- Oferecer incentivos para clientes que optam por contratos de longo prazo, como descontos ou benefícios exclusivos para aumentar a fidelidade.

- Realizar pesquisas de satisfação para entender melhor a necessidades e expectativas dos clientes, buscando melhorar a qualidade dos serviços oferecidos.


---
### Contato:

<div>
  <a href="https://linkedin.com/in/marcospontesjunior" target="_blank"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white&color=black" target="_blank"></a>  
  <a href = "mailto:marcospntsjunior@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=black" target="_blank"></a>
</div>
