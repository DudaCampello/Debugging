# debugging
Aprendendo Debugging Java 

### Pilha de Execução de um Programa Java/Stack Trace

###Pilha de Execução:

Toda invocação de método é empilhada em uma estrutura de dados que isola a área de memória de cada um. Quando um método termina (retorna), ele volta para o método que o invocou.

###Stack Trace:

É a matriz onde encontramos a pilha de excecução da exceção. Em outras palavras, podemos dizer que o rastreamento da pilha busca (rastreio) para a próxima linha onde a exceção pode surgir.

####Método dumpStack

thread.dumpStack é recomendado para fazer a depuração do código.

🔗 Links Úteis

https://github.com/cami-la/debugging-java/blob/master/README.md
