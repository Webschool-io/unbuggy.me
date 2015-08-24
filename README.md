API para mostrar a solução de todos os erros existentes na programação, para que você possa adicionar a URL da API + a mensagem de erro para que ele leve para um link com a solução. Para ser adicionado na hora do DEGUB!


# A Ideia

Como as mensagens de erro na programação são sempre as mesmas, mudando apenas algumas variáveis, podemos criar uma espécie de FAQ para qualquer tipode erro que possa dar tanto de linguagem como de framework e que o desenvolvedor na hora de debugar possa adicionar o link dessa API antes da mensagem do erro, para que seja mostrado ao desenvolvedor, para que esse possa pegar a URL e ir diretamente para a solução daquele erro. 

# Como fazer?

Bom como sabemos o Stack Overflow tem muitas dessas respostas então podemos fazer tanto uma pesquisa, utilizando a msg de erro como busca, ou criarmos um sisteminha simples parecido com ele. E toda vez que você tiver um erro irá olhar na API a resposta, caso não exista você pode criar a solução quando conseguir resolver seu problema.

Poderíamos até utilizar o github para que cada erro fosse um arquivo em Markdown explicando a solução e o sistema precisaria apenas buscar pela API do Github nesse repositório, deixando assim aberto para que qualquer um possa utilizar as mesmas soluções. 

# Protótipo client-side : 
https://gist.github.com/guisouza/83b415f898b9bd60f080
