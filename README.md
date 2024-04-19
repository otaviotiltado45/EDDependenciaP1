# EDDependenciaP1

**Relatório: Funcionalidades do Labirinto**

---

**1. Descrição do Problema**
O código em questão implementa a resolução de um labirinto bidimensional em Java. O labirinto é representado por uma matriz de caracteres, onde cada célula pode ser um caminho livre (0), um obstáculo (1), o ponto de partida (S), ou o destino (D).

**2. Funcionalidades Principais**
- **Definição Manual do Labirinto**: O código define manualmente o labirinto de exemplo com suas características, incluindo tamanho, posição inicial e destino.
- **Impressão do Labirinto**: A classe `labirinto` possui um método para imprimir o labirinto atual, mostrando as paredes, caminhos e as posições inicial (S) e destino (D).
- **Resolução do Labirinto**: Utilizando um algoritmo de busca em profundidade, o código encontra um caminho válido do ponto de partida ao destino, marcando o caminho percorrido com '*' na impressão final.

**3. Funcionamento do Código**
- **Inicialização do Labirinto**: Ao criar uma instância da classe `labirinto`, o labirinto é definido com suas características.
- **Impressão Inicial**: O programa imprime o labirinto inicialmente, mostrando a disposição das paredes, caminhos, ponto de partida e destino.
- **Resolução do Labirinto**: O método `resolverLabirinto` utiliza recursão para encontrar um caminho válido do ponto de partida ao destino. Ele marca o caminho percorrido com '*' na impressão final.
- **Impressão do Caminho**: Após resolver o labirinto, o programa imprime o labirinto novamente, destacando o caminho percorrido com '*' e mantendo as paredes e posições iniciais/destino.

**4. Resultados**
- **Caminho Encontrado**: Se um caminho do ponto de partida ao destino for encontrado, o programa exibe o caminho percorrido.
- **Caminho Não Encontrado**: Caso não seja possível encontrar um caminho válido, o programa informa que não foi possível encontrar um caminho até o destino.

**5. Conclusão**
O código apresenta uma solução eficiente para resolver labirintos em Java, utilizando uma abordagem de busca em profundidade. Ele é capaz de encontrar caminhos válidos em labirintos definidos manualmente, mostrando a trajetória percorrida de forma clara na impressão final.

---
