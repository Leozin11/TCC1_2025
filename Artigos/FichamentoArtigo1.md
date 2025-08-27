
Título: An Empirical Evaluation of GitHub Copilot’s Code Suggestions

Referência completa:  
Nguyen, N., & Nadi, S. (2022). An Empirical Evaluation of GitHub Copilot’s Code Suggestions. In *Proceedings of the 19th International Conference on Mining Software Repositories (MSR ’22)*, May 23–24, 2022, Pittsburgh, PA, USA. ACM. https://doi.org/10.1145/3524842.3528470

Fichamento de Conteúdo

Este artigo realiza um estudo empírico sobre a correção e compreensibilidade do código gerado pelo GitHub Copilot. Utilizando 33 problemas do LeetCode e quatro linguagens de programação (Java, Python, JavaScript e C), os autores analisaram 132 sugestões da ferramenta. A correção foi avaliada por meio da execução dos testes do LeetCode, enquanto a legibilidade foi verificada com métricas de complexidade cognitiva e ciclomática via SonarQube. Os resultados mostram que as sugestões em Java têm a maior taxa de acerto (57%) e JavaScript a menor (27%). O estudo conclui que, apesar da utilidade prática da ferramenta, o código gerado pode conter erros, ser redundante ou depender de funções não definidas.

Fichamento Bibliográfico

1. Correção funcional: taxa com que as sugestões passam todos os testes do LeetCode. No caso do Java, 57% foram corretas (p. 3).
2. Complexidade Ciclomática: métrica de controle de fluxo que indica o número de caminhos independentes no código, usada para medir legibilidade e testabilidade (p. 2).
3. Complexidade Cognitiva: métrica que avalia a dificuldade de compreensão do código com base na estrutura lógica, também extraída via SonarQube (p. 2).
4. LeetCode: plataforma de testes usada para validar as soluções de Copilot em múltiplas linguagens (p. 3).
5. SonarQube: ferramenta usada para calcular métricas estáticas e comparar compreensibilidade entre as soluções geradas (p. 3).
6. Avaliação empírica baseada em execução real e análise estática, com uso de scripts em Python para extração automatizada dos resultados (p. 4).

Fichamento de Citações

1. “Copilot’s Java suggestions have the highest correctness score (57%) while JavaScript is the lowest (27%).” (p. 3)  
2. “Copilot’s suggestions have low complexity with no notable differences between the programming languages.” (p. 3)  
3. “Copilot may generate code that relies on non-existing helper functions.” (p. 4)  
4. “Copilot’s first solution is often fully correct at least 27% of the time for JavaScript, and as high as 57% of the time for Java.” (p. 4)  
5. “The median cognitive complexity and cyclomatic complexity of Copilot solutions is 6 and 5, respectively.” (p. 5)

