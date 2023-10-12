# DesafioControleFluxo
Controle de Fluxo - Desafio.


O código faz o seguinte:

O método main() recebe dois parâmetros do usuário, que representam dois números inteiros.
O método contar() valida se o primeiro parâmetro é maior que o segundo parâmetro. Se for, ele lança uma exceção ParametrosInvalidosException.
Se o primeiro parâmetro não for maior que o segundo parâmetro, o método contar() calcula a quantidade de interações do loop for, que será igual à diferença entre os dois parâmetros.
O loop for imprime os números de 1 até o número máximo, incrementado em 1 a cada iteração.

Uuma explicação mais detalhada do código:

O método main() recebe dois parâmetros do usuário, que representam dois números inteiros. Os parâmetros são recebidos usando um objeto Scanner.
O método contar() é um método estático, o que significa que ele pode ser chamado sem instanciar um objeto da classe Contador.
O método contar() valida se o primeiro parâmetro é maior que o segundo parâmetro usando a expressão parametroUm > parametroDois.
Se a expressão for verdadeira, o método contar() lança uma exceção ParametrosInvalidosException.
A exceção ParametrosInvalidosException é uma classe de exceção personalizada que representa uma exceção de negócio no sistema.
Se a expressão for falsa, o método contar() calcula a quantidade de interações do loop for usando a expressão parametroDois - parametroUm.
O loop for imprime os números de 1 até o número máximo, incrementado em 1 a cada iteração.
