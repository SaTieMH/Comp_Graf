Semana 4

coordenadas dos vértices
cores dos vértyices
topologia (conexão) da malha


o interior é preenchido via interpolação

Quando quero acessa algum buffer da placa de vídeo eu tenho como retorno um inteiro.

Crio 4 vetores (vector) - vértice, color, indice
- Vector tem tamanho variado, enquanto que array tem tamanho fixo

Shaders são compilados e linkados com a aplicação em tempod e execução - compilados em tempo de xecução - por que a capacidade de rederização depende da capacidade da placa de vídeo da máquina que está executando o programa. Sendo assim é necessário enviar junto o código do shader e o ponteiro para o arquivo .char
arquivos shaders são programados separados para depois serem integrados.
Esses arquivos são ocultados utilizando resourses para encapsular todas as informações que não são compiladas.

pasta resoruses vai tudo o que não for cpp.

---------
Criando shader Program
- destroy shaders antigos antes de começar a criar novos.
- lê arquivos vshader e fshader - importante colocar ':' para que ele busque nos arquivos do resourses
- converte para uma classe texto do qt
- converte para uma classe texto do C++ (cadeia de caracteres)
- cria ponteiros para acesso do texto para o c++
- fecha os dois arquivos que eu abri
- começa a entrar no opengl

- crie um vertexshader - retorna um inteiro para me que eu possa acessar/utilizar
- associo o código fonte do shader que acabei de ler com o índice 
- compilo o que acabei de carregar na váriável

-----------
Criando buffer objects
- 6 índices (2*3 pois são 2 triângulos)

