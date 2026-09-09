Desafio Nível Herói - DIO

Esse é um desafio de lógica de programação da DIO. O desafio original sugeria o uso de JavaScript, mas optei por resolver em Java, como forma de praticar a linguagem que estou estudando no momento.

Sobre o desafio

O programa recebe o nome e a quantidade de XP, experiência, de um herói e retorna o nível correspondente, de acordo com as seguintes faixas: menor que 1.000 é Ferro, entre 1.001 e 2.000 é Bronze, entre 2.001 e 5.000 é Prata, entre 5.001 e 7.000 é Ouro, entre 7.001 e 8.000 é Platina, entre 8.001 e 9.000 é Ascendente, entre 9.001 e 10.000 é Imortal, e maior ou igual a 10.001 é Radiante.

Funcionalidades

Classificação automática do nível do herói com base no XP, usando estrutura condicional if, else if, else. Exibição de uma mensagem final com o nome do herói e o nível atingido. Entrada de dados interativa via Scanner, funcionalidade que decidi adicionar, permitindo que o próprio usuário digite o nome e o XP do herói, em vez de valores fixos no código.

Tecnologias utilizadas

Java

Como executar

Clone o repositório. Abra o arquivo desafio.java no VS Code ou outra IDE de sua preferência. Compile com o comando javac desafio.java. Execute com o comando java desafio.

O que aprendi

Esse desafio foi minha primeira experiência prática com Java, o que me ajudou a entender melhor tipagem de variáveis, estrutura condicional if, else if, else, e concatenação de strings. Também foi o meu primeiro projeto publicado no GitHub, então aprendi na prática o fluxo de versionamento com Git: inicializar um repositório, fazer commits, usar gitignore para excluir arquivos que não fazem parte do projeto, como o JDK, e enviar o código para um repositório remoto. Depois da primeira versão, decidi incrementar o projeto por conta própria, adicionando a classe Scanner para capturar o nome e o XP diretamente do usuário, o que me ajudou a entender melhor como funciona a entrada de dados em Java.

Melhorias futuras

Pretendo continuar evoluindo esse projeto com algumas ideias: adicionar validação de entrada, para garantir que o usuário não digite um XP negativo ou um texto no lugar de número; criar um menu que permita consultar vários heróis em sequência, sem precisar reiniciar o programa toda vez; e futuramente salvar os heróis cadastrados em um arquivo, para não perder os dados quando o programa fechar.
