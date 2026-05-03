# Notebook para calculo de Embedding com mxbai-embed-large

Este Notebook traz um script capaz de gerar embeddings de palavras, frases ou textos a partir do uso do modelo mxbai-embed-large.

De acordo com a página do modelo no Ollama, Mxbai-embed-large é um modelo de embedding de última geração para grandes redes, da mixedbread.ai.

Neste exemplo, geramos embeddings de uma frase clássica da linguagem de programação python "Bonito é melhor que feio. Explícito é melhor que implícito.". Contudo, podemos substitui-la por outros textos.

Para utiliza-lo, siga os seguintes passos:

1º Baixe o modelo em sua máquina na página do Ollama https://ollama.com/library/mxbai-embed-large

2º O arquivo sugere instalar o Langchain atravéz do comando !pip install langchain_community. Isto facilita o uso do código.

3º Substitua o texto da variável query no código pelo texto desejado. A variável query será usado pela variável query_embedding para o calculo do embedding pelo modelo.

4º O embedding será exibido por completo, incluindo o tamanho. Neste modelo, é gerado um embedding com 1024 dimensões por padrão.

