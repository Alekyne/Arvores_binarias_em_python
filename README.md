🧬 Crossover em Árvores Binárias de Expressões Matemáticas
Este projeto demonstra como realizar operações de crossover entre duas árvores binárias que representam expressões matemáticas. O objetivo é manipular as árvores para gerar novas expressões e visualizar a estrutura de cada uma, antes e depois da operação de crossover.

📋 Objetivo
O código tem como objetivo construir árvores binárias a partir de expressões matemáticas, permitir a realização de crossover (troca de subárvores) entre essas árvores e visualizar os resultados. O algoritmo de crossover seleciona um nó aleatório de cada árvore e troca suas subárvores correspondentes, gerando duas novas árvores.

🛠️ Tecnologias Utilizadas
Linguagem: Python
Bibliotecas:
matplotlib: Para plotar as árvores.
networkx: Para criar e visualizar grafos (representando as árvores binárias).
random: Para selecionar nós aleatórios nas árvores.
📖 Como Funciona
1. Construção das Árvores
A função build_tree recebe uma expressão matemática como string e constrói uma árvore binária. Para isso, ela utiliza uma pilha para armazenar operadores e operandos enquanto percorre a expressão.

2. Crossover entre Árvores
A função crossover realiza a troca de subárvores entre duas árvores binárias. Ela seleciona um nó aleatório em cada árvore e troca a subárvore de um nó da árvore 1 com a subárvore de um nó da árvore 2. Essa operação cria novas árvores, que podem ser visualizadas após a troca.

3. Visualização das Árvores
As árvores são desenhadas usando a biblioteca networkx. Cada nó da árvore é rotulado com seu valor (operador ou operando) e a estrutura da árvore é representada por um grafo.

📂 Estrutura do Projeto
O código é dividido nas seguintes partes principais:

Node class: Define a estrutura do nó da árvore binária.
build_tree function: Constrói a árvore binária a partir de uma expressão matemática.
Funções auxiliares: Funções para encontrar nós, realizar o crossover e desenhar as árvores.
plot_tree function: Desenha e plota as árvores utilizando networkx e matplotlib.
🚀 Como Executar
1. Clone o repositório:

2. Instale as dependências:
Se você ainda não tem as dependências instaladas, execute:

bash
Copiar código
pip install matplotlib networkx
3. Execute o script:
bash
Copiar código
python crossover_arvore.py
📈 Exemplo de Saída
O código cria e exibe as seguintes imagens:

Árvore 1 (Original)
Árvore 2 (Original)
Árvore 1 (Após Crossover)
Árvore 2 (Após Crossover)
Cada imagem mostra a estrutura das árvores antes e depois da operação de crossover.

🧠 Explicação da Lógica de Crossover
O crossover é realizado da seguinte forma:

Dois nós aleatórios são escolhidos, um em cada árvore.
As subárvores correspondentes a esses nós são trocadas.
As novas árvores resultantes são exibidas.
📝 Conclusão
Este projeto demonstra como usar árvores binárias para manipular expressões matemáticas e realizar operações de crossover. Esse processo é comumente utilizado em algoritmos genéticos e pode ser expandido para manipulação de árvores mais complexas.

