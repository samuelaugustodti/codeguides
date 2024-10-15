
## Guia de Código: 

**importante**: Foque em revisões que melhoram o entendimento e/ou lógica do código, melhorando a testabilidade e a estrutura do programa. Foque em problemas como long methods, repetições de código desnecessárias, alto acomplamento, etc. Use princípios consolidados como SOLID, DRY, clean code e padrões de projeto para guiar sua revisão, mas não se limite a eles. Utilize as melhores práticas para realizar uma revisão clara, concisa, explicativa e que resolva o(s) problema(s) identificados.

Problemas de desempenho, qualidade de código e segurança devem ser priorizados em relação à problemas de nomeclatura e organização de código. Mas ambos devem ser analisados com o mesmo empenho.

1. O código não deve ser comentado (com '// meu código' ou '/* meu código */'). Você deve descomentar ou deletar este pedaço de código comentado.
2. Remova comentários desnecessários no código (com '// meu comentário' ou '/* meu comentário */'). Seu código deve ser claro e autoexplicativo.
3. Garanta uma indentação consistente.
4. Use espaços consistentemente entre chaves, parênteses e operadores.
5. Garanta que as classes e métodos tenham uma única responsabilidade principal para melhorar a manutenibilidade.
6. Use nomes significativos para variáveis, propriedades, classes e métodos que representem com precisão seu propósito.
7. Mantenha um nível consistente de abstração nos métodos para equilibrar a complexidade e a manutenibilidade. Se não, considere a extração para um novo método.
8. Evite confiar apenas em Mockito.any() ou apenas afirmar contra valores não nulos se eles enfraquecerem os testes.
9. Evite usar importações curinga.
10. Use o operador == ao comparar valores enum.
11. Prefira objetos imutáveis para reduzir erros causados por estado compartilhado.
12. Use padrões de design apropriados e melhores práticas. Aplique padrões de design bem conhecidos e melhores práticas da indústria para melhorar a legibilidade, manutenibilidade e extensibilidade do código.
13. Evite métodos ou funções muito longos. Métodos longos podem ser mais difíceis de entender, testar e manter. Considere dividi-los em métodos menores e mais focados.
14. Prefira composição em vez de herança. Favoreça a composição de objetos para alcançar a reutilização de código e flexibilidade em vez de depender fortemente da herança de classes.
