# Prompts utilizados

Prompts usados no chatgpt, anexando as 3 bases de dados separadamente.

## 1. Para onde seguir?

Utilizei o seguinte prompt para definir o que é mais relevante ser analisado na minha base de dados


**Prompt**
```
Baseado nesses dados da mesma empresa, em que pontos eu deveria focar para aumentar as vendas
```

**Resposta**

```
Para aumentar as vendas, vou focar em:

Produtos mais vendidos – Identificar quais SKUs vendem mais e em quais marketplaces.
Tendências de preços e descontos – Verificar o impacto dos preços e dos cupons nas vendas.
Mercados mais fortes – Analisar quais países mais compram cada produto.
Padrões sazonais – Verificar meses de maior e menor volume de vendas.
Agora, vou calcular esses insights com base nos dados disponíveis. ​​

Insights para Aumentar as Vendas
Produtos Mais Vendidos

O NEW MEGANIUM RG 40XXV lidera as vendas (41 unidades), seguido por NEW MEGANIUM RG CubeXX, RG28XX e RG35XX (36 unidades cada).
O MEGANIUM RG353M tem a menor quantidade vendida (29 unidades).
🔹 Oportunidade: Investir em marketing para os produtos menos vendidos e destacar os best-sellers nos marketplaces.

Impacto de Preços e Descontos

O MEGANIUM RG353M tem o maior preço médio unitário (110) e também o maior preço final médio (263.79), o que pode estar reduzindo seu volume de vendas.
O NEW MEGANIUM RG28XX tem o menor preço médio (70), mas seu preço final médio é 175.52, indicando que os descontos não são tão expressivos.
🔹 Oportunidade: Avaliar se a estratégia de descontos está funcionando ou se produtos mais caros precisam de promoções mais agressivas.

Mercados Mais Fortes

Canadá é o maior mercado (46 unidades vendidas), seguido de França (36), Austrália (28), Japão (27) e Alemanha (23).
EUA e Reino Unido têm vendas mais fracas.
🔹 Oportunidade: Investir em publicidade nos países de maior volume e explorar estratégias para aumentar as vendas nos EUA e Reino Unido.

Padrões Sazonais

O pico de vendas foi em agosto (47 unidades), seguido de outubro (38) e setembro (37).
As vendas aumentaram gradativamente desde maio, sugerindo uma alta sazonal.
🔹 Oportunidade: Preparar promoções para os meses de pico e ações para evitar quedas nos meses mais fracos.
```

**Conclusão**: Com apenas um prompt, já é muita informação


## 2. Definindo melhores e piores produtos


**Prompt**
```
me mostre a lista dos itens vendidos e o numero de vendas totais de cada
```

**Resposta**
```
Total de Vendas por Produto:
NEW MEGANIUM RG 40XXV → 41 unidades
NEW MEGANIUM RG CubeXX → 36 unidades
NEW MEGANIUM RG28XX → 36 unidades
NEW MEGANIUM RG35XX → 36 unidades
MEGANIUM RG353M → 29 unidades
```

**Conclusão:** Verifica-se que o item MEGANIUM RG353M foi o menos vendido


**Prompt**
```
Baseando-se nos dados, como me mostre como eu posso calcular qual é o melhor preço de venda de cada produto? crie uma função que calcule o meu custo beneficio, baseando-se no custo e quantidade de cada produto
```

**Resposta**
```
Cálculo do Custo-Benefício
O custo-benefício foi calculado como preço final médio dividido pela quantidade média vendida. Quanto menor esse valor, melhor o custo-benefício.

Ranking de Custo-Benefício (do melhor para o pior):
NEW MEGANIUM RG28XX → 58.51
NEW MEGANIUM RG CubeXX → 66.82
NEW MEGANIUM RG35XX → 72.31
NEW MEGANIUM RG 40XXV → 83.58
MEGANIUM RG353M → 90.96
Como Usar Esses Dados para Definir o Melhor Preço de Venda?
O RG28XX tem o melhor custo-benefício, indicando que é um dos mais rentáveis por unidade vendida.
O RG353M tem o pior custo-benefício, sugerindo que seu preço pode estar alto demais para a quantidade que vende.
```

**Conclusão:** Posso facilmente encontrar informação sobre itens da loja que precisam ser viabilizados para o mercado, seja melhorando suas vendas, seja diminuindo sua produção. 

Além disso, o item pode ser pouco vendido globalmente mas ser bem vendido em locais específicos. Como exemplo, o item MEGANIUM RG353M foi o menos vendido e tem o menor custo benefício, mas é o segundo mais vendido no japão. O chatGPT analisou isso respondendo ao seguinte:


**Prompt**
```
me mostre os itens mais vendidos no japao
```

**Resposta**
```
Os itens mais vendidos no Japão foram:

NEW MEGANIUM RG 40XXV → 11 unidades
MEGANIUM RG353M → 6 unidades
NEW MEGANIUM RG CubeXX → 5 unidades
NEW MEGANIUM RG28XX → 5 unidades
```

Isso mostra que esse item pode ser melhor aproveitado pelo japão e que uma análise mais profunda sobre a região pode permitir um boost nas vendas desse produto.

Considerando também a seguinte sequência:

**Prompt**
```
Analise os dados e me mostre em qual pais o MEGANIUM RG353M é menos vendido?
```

**Resposta**
```
Os arquivos foram reenviados. Vou recarregar os dados e refazer a análise para verificar em qual país o MEGANIUM RG353M foi menos vendido.

O MEGANIUM RG353M foi menos vendido na Alemanha, com apenas 3 unidades vendidas.

Se quiser estratégias para aumentar as vendas nesse mercado, me avise!
```

É possível perceber que o item MEGANIUM RG353M não recebe muita atenção da alemanha. Isso gera a oportunidade de analisar a Alemanha, verificar porque esse produto não é comprado e possivelmente melhorar seu marketing ou retirá-lo do país.


## Conclusão

Mesmo lidando com uma base de dados pequena e a versão gratuita do ChatGPT, é possível notar que a IA é extremamente útil para analisar dados e que qualquer pessoa pode realizar essa tarefa usando a ferramenta, desde que saiba utilizar adequadamente os prompts. 