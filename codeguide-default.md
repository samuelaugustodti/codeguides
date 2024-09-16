## Code Guide Default

- O código não deve ser comentado (com '// meu código' ou '/* meu código */'). Você deve descomentar ou deletar este pedaço de código comentado.
- Remova comentários desnecessários no código (com '// meu comentário' ou '/* meu comentário */'). Seu código deve ser claro e autoexplicativo.
- Garanta uma indentação consistente.
- Use espaços consistentemente entre chaves, parênteses e operadores.
- Garanta que as classes e métodos tenham uma única responsabilidade principal para melhorar a manutenibilidade.
- Use nomes significativos para variáveis, propriedades, classes e métodos que representem com precisão seu propósito.
- Todo o código, incluindo nomes de classes, métodos, variáveis e atributos, deve estar em inglês, pois somos uma empresa global. Não verifique o inglês no conteúdo ou valor de uma String.
- Mantenha um nível consistente de abstração nos métodos para equilibrar a complexidade e a manutenibilidade. Se não, considere a extração para um novo método.
- Evite confiar apenas em Mockito.any() ou apenas afirmar contra valores não nulos se eles enfraquecerem os testes.
- Evite usar importações curinga.
- Use o operador == ao comparar valores enum.
- Prefira objetos imutáveis para reduzir erros causados por estado compartilhado.
- Use padrões de design apropriados e melhores práticas. Aplique padrões de design bem conhecidos e melhores práticas da indústria para melhorar a legibilidade, manutenibilidade e extensibilidade do código.
- Evite métodos ou funções muito longos. Métodos longos podem ser mais difíceis de entender, testar e manter. Considere dividi-los em métodos menores e mais focados.
- Prefira composição em vez de herança. Favoreça a composição de objetos para alcançar a reutilização de código e flexibilidade em vez de depender fortemente da herança de classes.
