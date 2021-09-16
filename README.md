# AluraChalengeBI---Semana-2
Repositório destinado ao Challenge Semana 2 de Power BI

# AluraShop
____________________________________________________________________________________________________________________________________________________________________

Na semana 2 de desafio foram passadas algumas métricas para o desenvolvimento do Dashboard, sendo elas:
CPC
Ticket Médio por dispositivo
ROAS
Total de compras
Valor investido na campanha total
Total de valor convertido em compras
Valor convertido em compras por dia

# Base de Dados
____________________________________________________________________________________________________________________________________________________________________

Na semana 2 utilizamos duas cargas de dados em formato json.
Analisando com um leitor json, podemos ver que existem vários valores nulos. Esses valores vão ser definidos como zero, pois analisando a base de dados chega-se a conclusão que os valores numéricos desta base de dados, como compras no facebook por exemplo ao não estar preenchida, entende-se como zero.

![image](https://user-images.githubusercontent.com/81394440/133661857-ac02e839-71d3-4652-aa1b-472e651151e0.png)

Vemos que por exemplo o dado de quantidade adicionada ao carrinho que antes era nula.

![image](https://user-images.githubusercontent.com/81394440/133661931-e8e5a186-08e9-4f64-acee-f95cec0b2929.png)

Agora está como zero, o que é a maneira mais correta nesse caso.

![image](https://user-images.githubusercontent.com/81394440/133661957-69fc0083-c0db-42cc-9a65-59d5ac202aa6.png)

Outro tratamento dado, foi em realização de atualização dos dados, sendo solicitado que todo dia as 9 horas da manhã a base se atualiza-se sozinha. Para isso configuramos através do Data Gateway, disponibilizado pelo Power BI para configurarmos está atualização.

![AgendamentoAtualizacaoBI](https://user-images.githubusercontent.com/81394440/133662194-f99e0599-49e1-4e26-af6f-631616af2c07.PNG)

# Link do Dashboard
____________________________________________________________________________________________________________________________________________________________________

