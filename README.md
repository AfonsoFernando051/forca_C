Este jogo é feito em C, foi criado em meus estudos na plataforma ALURA, em que treinei minha lógica de programação e aprendi funcionalidades da linguagem C.

Este código se inicia na função principal, que contém as respectivas funções:

Abertura - introdução;

escolhepalavra - Esta, busca no arquivo "palavras.txt" alguma palavra aleatória do banco de dados que será escolhida para ser a palavra da forca;

desenhaforca - Dentro da estrutura de repetição do while, esta função faz o desenho caso o usuário erre a letra;

chuta - Esta função é responsávelo por escanear novas letras quando o usuário "chuta" uma letra nova.

ganhou e enforcou - São as funções/condições do do-while que englobam as funções: desenhaforca e chuta, de modo que enquanto elas retornem
um valor falso, a estrutura se repete, dando continuídade ao jogo.

Todas estas funções, são auxiliadas por alguma outra, como a função "jachutou", que verifica se o usuário já tentou usar a mesma letra, ou estão
interligadas. Ademais, todas elas estão presentes na biblioteca criada "forca.h", para serem compiladas previamente, ajudando o programa.

Caso o usuário ganhe, o programa imprime uma mensagem de parabéns com um troféu, caso contrário, imprime uma caveira e a mensgem dizendo que ele foi
enforcado.

Ao finalizar o jogo, fora da estrutura do-while, tem a função adicionarpalavra, ela oferece a opção de gravar no arquivo externo palavras.txt uma palavra 
nova para o jogo.

Foi um projeto divertido que me trouxe uma expência muito legal com a linguagem C.

Divirta-se!!!

