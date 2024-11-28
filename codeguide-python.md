## Guia de Código Python:

**REGRA 0: O código deve SEMPRE estar usando tipagem estática com mypy para melhorar a segurança do código.**

1. O código não deve ser comentado (com '# meu código'). Você deve descomentar ou deletar este pedaço de código comentado.
2. Remova comentários desnecessários no código (com '# meu comentário'). Seu código deve ser claro e autoexplicativo.
3. Garanta uma indentação consistente usando 4 espaços para cada nível de indentação.
4. Use espaços consistentemente entre operadores e após vírgulas para melhorar a legibilidade.
5. As funções e classes devem ter uma única responsabilidade principal para melhorar a manutenibilidade.
6. Use nomes significativos para variáveis, funções, classes e métodos que representem com precisão seu propósito.
7. Mantenha um nível consistente de abstração nas funções para equilibrar a complexidade e a manutenibilidade. Se não, considere a extração para uma nova função.
8. Evite usar importações curinga. Importe apenas as funções e classes necessárias.
9. Prefira objetos imutáveis (como tuplas) para reduzir erros causados por estado compartilhado.
10. Use padrões de design apropriados e melhores práticas. Aplique padrões de design bem conhecidos e melhores práticas da indústria para melhorar a legibilidade, manutenibilidade e extensibilidade do código.
11. Evite funções muito longas. Funções longas podem ser mais difíceis de entender, testar e manter. Considere dividi-las em funções menores e mais focadas.
12. Prefira composição em vez de herança. Favoreça a composição de objetos para alcançar a reutilização de código e flexibilidade em vez de depender fortemente da herança de classes.
13. Use docstrings para documentar suas funções, classes e módulos. Eles devem descrever o que eles fazem, não como.
14. Siga a PEP 8, o guia de estilo oficial para Python, sempre que possível. Ele contém muitas dicas úteis sobre como formatar seu código.
