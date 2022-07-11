# self-driving-car
 Este é um projeto que faz o uso de JavaScript puro para simular uma rede neural que é capaz de dirigir um carrinho. Este é um dos projetos que fiz com base nos estudos feitos pelo canal do YouTube da freeCodeCamp.org.
 
 <h3>Rodando o projeto pela primeira vez:</h3>
 <p>Se você desejar testar este projeto em sua máquina, é bem simples: basta fazer o download da pasta e abrir o arquivo <strong>Index.html</strong> em seu navegador (eu usei o Google Chrome).</p>
 <p>No entanto, provavelmente nenhum carrinho irá passar e conseguir desviar de todos os obstáculos. Isso acontece porque os cérebros da rede neural nesse caso são gerados aleatóriamente. Então, para conseguir fazer um carrinho com um cérebro inteligente, recomendo que você vá 'salvando' (no botão de salvar) sempre o carrinho que conseguiu chegar mais longe.</p>
 <p>Com o melhor carrinho salvo, o algoritmo genético entrará em ação, mutando a Rede Neural aleatóriamente com base no seu carrinho salvo. Ou seja, se o seu melhor carrinho escolhe ir para a direite e você o salva desta forma, na próxima vez que recarregar a página, muitos outros carrinhos escolherão ir para a direita. Por padrão, o algoritmo de mutação está mutando 20% do carrinho original, ou seja, todos os outros carrinhos tentarão se diferenciar 20% do seu carrinho original. Isto é muito útil para o caso de ainda não ter achado o cérero ideial.O valor de mutação pode ser alterado no arquivo <strong>main.js</strong>, no método 'mutate(valor de 0 até 1)'.</p>
 Para que este processo seja mais rápido, você pode alterar o valor de carros gerados no começo da simulação: vá até 'main.js' e altere o valor que a variável N recebe. Desta forma, as chances de um carrinho com uma rede neural superior aparecer serão maiores (o máximo que eu usei foram 1000 carrinhos, mas se o seu computador for muito bom, pode aumtar este valor) <p>Por padrão, são gerados 100 carros por simulação (uma simulação é iniciada toda vez que a página é carregada).</p> 
 <p>Depois de fazer este passo algumas vezes, você provavelmente terá um carrinho que já consegue desviar de todos os outros. Você pode adicionar mais obstáculos, aumentar a velocidade do veículo, aumentar a quantidade de faixas na pista, mudar os controles de "AI" para "KEYS" para que você mesmo(a) possa dirigir, entre outras funcionalidades. Tudo isso pode ser feito no arquivo "main.js".</p>
 <p>De forma geral, este foi um projeto muito divertido de estudar e me deixou muito interessado na área de IA.</p>
 
 
 
 
