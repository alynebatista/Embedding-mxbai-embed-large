# Notebook para calculo de Embedding com mxbai-embed-large

Este Notebook traz um script capaz de calcular Embedding de palavras, frases ou textos a partir do uso do modelo mxbai-embed-large.

De acordo com a página do modelo no Ollama, Mxbai-embed-large é um modelo de embedding de última geração para grandes redes, da mixedbread.ai.

Neste exemplo, geramos embeddings de uma frase clássica da linguagem de programação python "Bonito é melhor que feio. Explícito é melhor que implícito.". Contudo, podemos substitui-la por outros textos.

Para utiliza-lo, siga os seguintes passos:

1º Baixe o modelo em sua máquina na página do Ollama https://ollama.com/library/mxbai-embed-large

2º Instale o Langchain atravez do comando !pip install langchain_community

3º Substitua o texto da variável query no código pelo texto desejado. A variável query será usado pela variável query_embedding para o calculo do embedding pelo modelo.

4º O embedding será exibido por completo, incluindo o tamanho. Neste modelo, são gerados 1024 embeddings por padrão.

