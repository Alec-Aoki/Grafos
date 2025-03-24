# Grafos
## Estrutura de Dados
Duas representações possíveis: **matriz de adjacência** e **lista linear de adjacência**.

**Matriz de Adjacência**: sendo $n$ a quantidade de vértices em um grafo, é uma matriz $n \times n$ tal que ```M[i,j] = 1``` se houver aresta entre os vértices $i$ e $j$ e ```M[i,j]=0``` se não houver arestra entre os vértices. Caso o grafo seja *não-direcionado*, a matriz é *simétrica*. 

Armazenamento: $O(n^2)$. 

Acesso a aresta/vértice: $O(1)$.

**Lista de Adjacência**: vetor em que cada espaço aponta para uma lista encadeada que representa um vértice e seus vizinhos.

Armazenamento: $O(n + m)$.

Acesso a aresta/vértice: $O(d)$.

## TAD Grafo
1. Criar um grafo vazio;
2. Inserir uma aresta no grafo;
3. Verificar se determinada aresta existe no grafo;
4. Obter lista de vértices adjacentes a um determinado vértice;
5. Remover uma aresta do grafo;
6. Imprimir um grafo;
7. Obter o número de vértices do grafo;
8. Obter o transposto de um grafo direcionado;
9. Obter a aresta de menor peso de um grafo;