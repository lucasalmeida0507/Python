#While Loops
#While - Enquanto

# Inicializa a variável 'numero' com o valor 1
numero = 1     

# Continua o loop enquanto 'numero' for menor que 5
while numero < 5:
    
    # Imprime o valor atual de 'numero'
    print(numero)
    
    # Incrementa 'numero' em 1 para a próxima iteração
    #numero = numero + 1
    numero += 1


    
"""
Explicação:

    Definindo Variável: A variável numero é inicializada com o valor 1.

    Loop While: A estrutura while cria um loop que continuará executando enquanto 
    a condição especificada for verdadeira. Neste caso, o loop continuará enquanto 
    numero for menor que 5.

    Corpo do Loop: Dentro do loop, há duas instruções:
    
        Imprimir Número: A função print(numero) imprime o valor atual da variável numero.
        
        Incrementar Número: A linha numero += 1 aumenta o valor de numero em 1. Isso é 
        equivalente a numero = numero + 1. É um passo importante para garantir que a condição 
        do loop eventualmente se torne falsa, evitando assim um loop infinito.

    Execução do Loop: O loop será executado enquanto numero for menor que 5. Veja 
    como ele se comporta em cada iteração:
    
        Iteração 1: numero é 1, impresso, e então incrementado para 2.
        Iteração 2: numero é 2, impresso, e então incrementado para 3.
        Iteração 3: numero é 3, impresso, e então incrementado para 4.
        Iteração 4: numero é 4, impresso, e então incrementado para 5.
        
        O loop termina, pois numero agora é 5, o que não satisfaz a condição numero < 5.

Saída:

A saída do programa será:
1
2
3
4

O código demonstra uma utilização básica do loop while para imprimir uma sequência 
de números, incrementando o valor em cada iteração até que uma condição de término seja atingida.

"""

print()

#Contar de 4 a 1
contador = 4

# Enquanto a variável contador for maior ou igual a 1, o loop continuará
while contador >= 1:
    
    # Imprime o valor atual da variável contador
    print(contador)  
    
    # Decrementa o valor da variável contador em 1
    #contador = contador - 1
    contador -= 1
    
    
print()

#Contar de 10 a 1 de 2 em 2

# Inicializa a variável contador com o valor 10
contador = 10

# Enquanto a variável contador for maior ou igual a 1, o loop continuará
while contador >= 1:
    
    # Imprime o valor atual da variável contador
    print(contador)  
    
    # Decrementa o valor da variável contador em 2
    contador -= 2 

"""
1
2
3
4

4
3
2
1

10
8
6
4
2
"""

# Inicializa a variável 'contador' com o valor 0
contador = 0

# Continua o loop enquanto 'contador' for menor que 10
while contador < 10:
    
    # Incrementa 'contador' em 1 a cada iteração do loop
    contador += 1
    
    # Imprime a string "Número " seguida do valor atual de 'contador'
    print("Número ", contador)
    
else:
    
    # Imprime esta mensagem após o término do loop
    print("Números impressos com sucesso!")

    
    
"""
Explicação:

    Inicialização do Contador: A variável contador é inicializada com 
    o valor 0.

    Loop While: A estrutura while cria um loop que continuará executando 
    enquanto a condição especificada for verdadeira. Neste caso, o loop 
    continuará enquanto contador for menor que 10.

    Corpo do Loop: Dentro do loop, há duas instruções:
    
        Incrementar Contador: A linha contador += 1 aumenta o valor 
        de contador em 1.
        
        Imprimir Número: A função print("Número ", contador) imprime a 
        mensagem atual contendo o valor do contador.

    Cláusula Else: A cláusula else após um loop while é executada uma vez 
    após o término do loop, mas apenas se o loop terminou normalmente (ou seja, não 
    foi interrompido por uma instrução break). Neste caso, ela imprimirá a 
    mensagem "Números impressos com sucesso!".

    Execução do Loop:
    
        O loop será executado 10 vezes, incrementando o contador de 1 a 10 e 
        imprimindo cada valor.
        
        Após o loop, a cláusula else imprimirá a mensagem de sucesso.

Saída:

A saída do programa será:

Número  1
Número  2
Número  3
Número  4
Número  5
Número  6
Número  7
Número  8
Número  9
Número  10
Números impressos com sucesso!

O código ilustra o uso de um loop while com uma cláusula else para executar uma 
série de ações repetitivas e uma ação final após o término do loop.
"""

"""
Número: 1
Número: 2
Número: 3
Número: 4
Número: 5
Número: 6
Número: 7
Número: 8
Número: 9
Número: 10
Números impressos com sucesso!
"""

#While Loops
#While = Enquanto

# Inicializa a variável 'numero' com o valor 1
numero = 1

# Continua o loop enquanto 'numero' for menor que 100
while numero < 100:
    
    # Imprime o valor atual de 'numero'
    print(numero)
    
    # Verifica se 'numero' é igual a 5
    if numero == 5: 
        
        # Se 'numero' for 5, sai do loop imediatamente
        break
    
    # Incrementa 'numero' em 1 para a próxima iteração, se a condição acima não for verdadeira
    numero += 1

    
"""
Esse código é um exemplo de um loop while que utiliza a instrução break 
para sair do loop quando uma condição específica é atendida. 

Explicação:

    Definindo Variável: A variável numero é inicializada com o valor 1.

    Loop While: A estrutura while cria um loop que continuará executando 
    enquanto a condição especificada for verdadeira. Neste caso, o loop 
    continuará enquanto numero for menor que 100.

    Corpo do Loop: Dentro do loop, há três instruções:
    
        Imprimir Número: A função print(numero) imprime o valor atual 
        da variável numero.
        
        Condição de Parada (if): A instrução if verifica se numero é 
        igual a 5. Se essa condição for verdadeira, a instrução break é 
        executada, interrompendo o loop imediatamente.
        
        Incrementar Número: A linha numero += 1 aumenta o valor de numero em 1.

    Execução do Loop: Veja como ele se comporta em cada iteração:
    
        Iterações 1 a 4: numero varia de 1 a 4, é impresso, e então incrementado.
        
        Iteração 5: numero é 5, é impresso, e então a condição numero == 5 é 
        verdadeira, o que aciona a instrução break.
        
        O loop é interrompido, e o programa termina sua execução.

Saída:

A saída do programa será:

1
2
3
4
5

O código demonstra como usar um loop while juntamente com uma instrução 
condicional if e a palavra-chave break para controlar a execução do loop. Neste 
exemplo, o loop é interrompido quando a variável numero atinge o valor 5.
"""
print()

"""
1
2
3
4
5
"""

#While Loops
#While = Enquanto

# Inicializa a variável 'linha' com o valor 0
linha = 0

# Continua o loop externo enquanto 'linha' for menor que 3
while linha < 3:
    
    # Inicializa a variável 'coluna' com o valor 0 para cada nova iteração do loop externo
    coluna = 0

    # Continua o loop interno enquanto 'coluna' for menor que 3
    while coluna < 3:
        
        # Imprime os valores atuais de 'linha' e 'coluna'
        print("Linha: ", linha, " - Coluna: ", coluna)
        
        # Incrementa 'coluna' em 1 para a próxima iteração do loop interno
        coluna += 1

    # Incrementa 'linha' em 1 para a próxima iteração do loop externo
    linha += 1

    
"""
Explicação:

    Definindo Variável de Linha: A variável linha é inicializada com o valor 0.

    Loop Externo (Linhas): A estrutura while externa cria um loop que 
    continuará executando enquanto a variável linha for menor que 3. Isso significa 
    que o loop externo será executado três vezes.

    Definindo Variável de Coluna: Dentro do loop externo, a variável 
    coluna é inicializada com o valor 0 em cada iteração.

    Loop Interno (Colunas): A estrutura while interna cria um loop que 
    continuará executando enquanto a variável coluna for menor que 3. Isso 
    significa que o loop interno será executado três vezes para cada iteração do loop externo.

    Corpo do Loop Interno: Dentro do loop interno:
    
        Imprimir Linha e Coluna: A função print imprime a linha e a coluna atuais.
        Incrementar Coluna: A linha coluna += 1 aumenta o valor de coluna em 1.

    Incrementar Linha: Dentro do loop externo, mas fora do loop interno, a 
    linha linha += 1 aumenta o valor de linha em 1.

    Execução dos Loops: O loop interno será executado três vezes para cada 
    iteração do loop externo, resultando em um total de nove iterações.

Saída:

A saída do programa será:

Linha:  0  - Coluna:  0
Linha:  0  - Coluna:  1
Linha:  0  - Coluna:  2
Linha:  1  - Coluna:  0
Linha:  1  - Coluna:  1
Linha:  1  - Coluna:  2
Linha:  2  - Coluna:  0
Linha:  2  - Coluna:  1
Linha:  2  - Coluna:  2

O código demonstra como usar loops while aninhados para iterar através 
de uma estrutura bidimensional (como uma matriz), imprimindo os índices de linha 
e coluna em cada iteração. Isso é comumente usado em programação para trabalhar 
com estruturas de dados bidimensionais.
"""
print()

"""
Linha:  0  - Coluna:  0
Linha:  0  - Coluna:  1
Linha:  0  - Coluna:  2
Linha:  1  - Coluna:  0
Linha:  1  - Coluna:  1
Linha:  1  - Coluna:  2
Linha:  2  - Coluna:  0
Linha:  2  - Coluna:  1
Linha:  2  - Coluna:  2
"""

#Vai do 1 até o número que o usuário digitar
#imprime todos os números inteiros a partir de um valor inicial até um valor final, fornecido pelo usuário. 

# Inicializa a variável 'numeroInicial' com o valor 1
numeroInicial = 1

# Pede ao usuário para inserir um número e converte para inteiro
numeroFinal = int(input("Digite um número maior que 1: ") )

# Continua o loop enquanto 'numeroInicial' for menor ou igual a 'numeroFinal'
while numeroInicial <= numeroFinal:
    
    # Imprime o valor atual de 'numeroInicial'
    print(numeroInicial)
    
    # Incrementa 'numeroInicial' em 1 para a próxima iteração
    numeroInicial += 1

    
"""
Explicação:

    Definindo Variável Inicial: A variável numeroInicial é inicializada com o valor 1.

    Entrada do Usuário: A função input solicita ao usuário que digite um número 
    maior que 1. O texto entre parênteses é a mensagem mostrada ao usuário. A função int 
    converte a entrada do usuário (que é uma string) em um número inteiro e armazena 
    na variável numeroFinal.

    Loop While: A estrutura while cria um loop que continuará executando enquanto a 
    condição especificada for verdadeira. Neste caso, o loop continuará enquanto 
    numeroInicial for menor ou igual a numeroFinal.

    Corpo do Loop: Dentro do loop, há duas instruções:
    
        Imprimir Número Atual: A função print(numeroInicial) imprime o 
        valor atual da variável numeroInicial.
        
        Incrementar Número Inicial: A linha numeroInicial += 1 aumenta o valor de 
        numeroInicial em 1. Isso é um passo importante para garantir que a condição do 
        loop eventualmente se torne falsa, evitando assim um loop infinito.

    Execução do Loop: O loop será executado para cada valor de numeroInicial, começando 
    em 1 e indo até numeroFinal, imprimindo cada valor.

Exemplo de Saída:

Suponha que o usuário insira o valor 5. A saída do programa será:

1
2
3
4
5

O código ilustra como usar um loop while para iterar através de uma sequência 
de números, começando de um valor fixo e terminando em um valor fornecido pelo usuário, 
imprimindo cada número na sequência.
"""
print()

"""
Digite um número maior que 1: 5
1
2
3
4
5
"""

#Numeros pares entre 1 e o número que o usuário digitar
#Solicita ao usuário um número inteiro maior que 1 e, em seguida, 
#imprime todos os números pares entre 1 e o número fornecido (inclusive).

# Inicializa a variável 'numero' com o valor 1
numero = 1

# Pede ao usuário para inserir um número inteiro e converte para inteiro
max = int(input("Digite um inteiro maior que 1: ") )

# Imprime uma mensagem indicando o que será mostrado
print("Números pares entre 1 e", max, ":")

# Continua o loop enquanto 'numero' for menor ou igual a 'max'
while numero <= max:
    
    # Verifica se 'numero' é par (divisível por 2)
    if numero % 2 == 0:
        
        # Imprime o valor atual de 'numero' se for par, sem adicionar uma nova linha
        print(numero, end=" ")
        
    # Incrementa 'numero' em 1 para a próxima iteração
    numero += 1

    
"""
Explicação:

    Definindo Variável Inicial: A variável numero é inicializada com o valor 1.

    Entrada do Usuário: A função input solicita ao usuário que digite um 
    número inteiro maior que 1. A entrada do usuário é convertida em um número 
    inteiro e armazenada na variável max.

    Imprimir Mensagem Inicial: A função print é usada para imprimir uma 
    mensagem informando ao usuário que os números pares entre 1 e max serão listados.

    Loop While: A estrutura while cria um loop que continuará executando enquanto 
    numero for menor ou igual a max.

    Corpo do Loop: Dentro do loop:
    
        Verificar Se o Número é Par: A instrução if numero % 2 == 0 verifica 
        se o valor atual de numero é par. Se for, o número é impresso.
        
        Imprimir Número Par: Se a condição acima for verdadeira, a função 
        print(numero, end=" ") imprime o valor atual de numero, seguido por um 
        espaço (em vez de uma nova linha, graças ao argumento end=" ").
        
        Incrementar Número: A linha numero += 1 aumenta o valor de numero em 1.

    Execução do Loop: O loop será executado para cada valor de numero, começando 
    em 1 e indo até max, imprimindo cada número par na sequência.

Exemplo de Saída:

Suponha que o usuário insira o valor 10. A saída do programa será:

Numeros pares entre 1 e 10 :
2 4 6 8 10 

O código ilustra como usar um loop while juntamente com uma instrução 
condicional if para iterar através de uma sequência de números, imprimindo apenas 
aqueles que atendem a uma condição específica (neste caso, sendo números pares).
"""
print()

"""
Digite um inteiro maior que 1: 30
Números pares entre 1 e 30 :
2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 
"""

"""

Exercício:

Crie um algoritmo que solicite ao usuário uma senha, e só sai do
looping do While quando for digitado a senha corretamente

"""

# Define a senha correta do sistema como "123"
senhaSistema = "123"

# Solicita ao usuário que digite a senha
senhaDigitada = input("Digite sua senha: ")

# Continua o loop enquanto a senha digitada pelo usuário for diferente da senha correta do sistema
while (senhaSistema != senhaDigitada):
    
    # Imprime uma mensagem indicando que a senha está incorreta
    print("Senha incorreta, tente novamente!")
    
    # Solicita ao usuário que digite a senha novamente
    senhaDigitada = input("\nDigite sua senha: ")

# Imprime uma mensagem de sucesso quando o usuário digita a senha correta e o loop termina
print("\nMuito bem! Você digitou a senha correta!")



"""
Explicação:

    Definindo a Senha do Sistema: A variável senhaSistema é inicializada com a 
    string "123", que é a senha correta que o usuário deve inserir.

    Entrada Inicial do Usuário: A função input solicita ao usuário que digite 
    sua senha, e a entrada é armazenada na variável senhaDigitada.

    Loop While: A estrutura while cria um loop que continuará executando enquanto 
    senhaSistema for diferente de senhaDigitada. Ou seja, o loop continuará enquanto a 
    senha digitada pelo usuário for incorreta.

    Corpo do Loop: Dentro do loop:
    
        Imprimir Mensagem de Erro: A função print imprime uma mensagem informando 
        ao usuário que a senha está incorreta.
        
        Pedir Senha Novamente: A função input solicita ao usuário que digite sua 
        senha novamente, e a entrada é novamente armazenada em senhaDigitada.

    Saída do Loop: O loop continuará executando até que o usuário digite a senha 
    correta ("123" neste caso). Uma vez que a senha correta seja inserida, o loop terminará.

    Imprimir Mensagem de Sucesso: Após o término do loop, a função print imprime uma 
    mensagem de sucesso informando ao usuário que ele digitou a senha correta.

Exemplo de Saída:

Suponha que o usuário insira a senha incorreta duas vezes e depois digite a senha 
correta. A interação com o programa seria assim:

Digite sua senha: 999
Senha incorreta, tente novamente!
Digite sua senha: 555
Senha incorreta, tente novamente!
Digite sua senha: 123
Muito bem! Você digitou a senha correta!

O código ilustra um padrão comum em programação para validar uma entrada 
do usuário através de um loop, continuando a pedir a entrada até que ela 
atenda a uma condição específica.

"""
print()

"""
Digite sua senha: 999
Senha incorreta, tente novamente!

Digite sua senha: 555
Senha incorreta, tente novamente!

Digite sua senha: 123

Muito bem! Você digitou a senha correta!
"""

# Inicia um loop infinito, que continuará até que seja explicitamente interrompido
while True:
   
    # Pede ao usuário uma entrada, com a opção de digitar 'sair' para encerrar o loop
    usuario = input("Digite 'sair' para encerrar: ")
   
    # Verifica se a entrada do usuário é igual a 'sair'
    if usuario == 'sair':
       
        # Se a entrada for 'sair', o comando break interrompe o loop, encerrando o programa
        break


"""
Digite 'sair' para encerrar: jk
Digite 'sair' para encerrar: 3983
Digite 'sair' para encerrar: kjdjd
Digite 'sair' para encerrar: dkd
Digite 'sair' para encerrar: sair
"""

import random  # Importa o módulo random para gerar números aleatórios

numero_secreto = random.randint(1, 100)  # Gera um número aleatório entre 1 e 100 e o armazena em numero_secreto
tentativas = 0  # Inicializa o contador de tentativas

#print(numero_secreto)

print("Adivinhe o número secreto entre 1 e 100.")  # Imprime as instruções para o usuário

while True:  # Inicia um loop infinito que continuará até que o número correto seja adivinhado
    
    palpite = int(input("Digite o seu palpite: "))  # Pede ao usuário para inserir um palpite e converte para inteiro
    tentativas += 1  # Incrementa o contador de tentativas

    if palpite < numero_secreto:  # Verifica se o palpite é menor que o número secreto
        
        print("O número secreto é maior. Tente novamente!")  # Informa ao usuário que o número secreto é maior
        
    elif palpite > numero_secreto:  # Verifica se o palpite é maior que o número secreto
        
        print("O número secreto é menor. Tente novamente!")  # Informa ao usuário que o número secreto é menor
        
    else:  # Se o palpite não for nem maior nem menor, ele deve ser igual
        
        print(f"Parabéns! Você acertou o número secreto {numero_secreto} em {tentativas} tentativas.")  # Imprime uma mensagem de sucesso
        
        break  # Sai do loop, já que o número correto foi adivinhado

"""
Digite o seu palpite: 40
O número secreto é maior. Tente novamente!
Digite o seu palpite: 50
O número secreto é maior. Tente novamente!
Digite o seu palpite: 90
O número secreto é menor. Tente novamente!
Digite o seu palpite: 80
O número secreto é menor. Tente novamente!
Digite o seu palpite: 60
O número secreto é menor. Tente novamente!
Digite o seu palpite: 55
O número secreto é menor. Tente novamente!
Digite o seu palpite: 54
O número secreto é menor. Tente novamente!
Digite o seu palpite: 53
O número secreto é menor. Tente novamente!
Digite o seu palpite: 52
Parabéns! Você acertou o número secreto 52 em 9 tentativas.
"""

"""

Exercício:

Crie um algoritmo que leia n números inteiros digitados pelo usuário,
e só pare quando o usuário digite 0.

No final, imprima na tela a soma de todos os números digitados.

"""

# Inicializa a variável para armazenar a soma dos números digitados com 0
somaNumerosDigitados = 0

# Solicita ao usuário que digite um número ou 0 para sair do loop
numero = int(input("Digite um número ou 0 para sair: "))

# Continua o loop enquanto o número digitado for diferente de 0
while numero != 0:
    
    # Adiciona o número digitado à soma total
    #somaNumerosDigitados = somaNumerosDigitados + numero
    somaNumerosDigitados += numero
    
    # Solicita ao usuário que digite um número novamente ou 0 para sair
    numero = int(input("Digite um número ou 0 para sair: "))

# Imprime a soma total dos números digitados depois que o loop termina
print("Total: ", somaNumerosDigitados)



"""
Explicação:

    Definindo a Variável de Soma: A variável somaNumerosDigitados é inicializada 
    com o valor 0. Ela será usada para armazenar a soma dos números digitados pelo usuário.

    Entrada Inicial do Usuário: A função input solicita ao usuário que digite um número 
    inteiro ou 0 para sair. A entrada é convertida em um número inteiro e armazenada 
    na variável numero.

    Loop While: A estrutura while cria um loop que continuará executando enquanto 
    numero for diferente de 0.

    Corpo do Loop: Dentro do loop:
    
        Adicionar Número à Soma: A linha somaNumerosDigitados += numero adiciona 
        o valor de numero à variável somaNumerosDigitados.
        
        Pedir Novo Número: A função input solicita ao usuário que digite um novo 
        número ou 0 para sair, e a entrada é novamente convertida em um número inteiro 
        e armazenada em numero.

    Saída do Loop: O loop continuará executando até que o usuário digite 0. Uma vez 
    que 0 seja inserido, o loop terminará.

    Imprimir Soma Total: Após o término do loop, a função print imprime a mensagem 
    "Total: " seguida pelo valor de somaNumerosDigitados, que é a soma de todos os 
    números digitados pelo usuário.

Exemplo de Saída:

Suponha que o usuário insira os valores 5, 10, 3, e então 0. A interação 
com o programa seria assim:

Digite um número ou 0 para sair: 5
Digite um número ou 0 para sair: 10
Digite um número ou 0 para sair: 3
Digite um número ou 0 para sair: 0
Total:  18

O código ilustra como usar um loop while para continuar solicitando entradas do 
usuário e executar cálculos com essas entradas até que uma condição de saída seja atendida.
"""

"""
Digite um número ou 0 para sair: 5
Digite um número ou 0 para sair: 3
Digite um número ou 0 para sair: 12
Digite um número ou 0 para sair: 40
Digite um número ou 0 para sair: 31
Digite um número ou 0 para sair: 49
Digite um número ou 0 para sair: 0
Total:  140
"""

"""

Exercício:

Crie um algoritmo que leia números inteiros positivos digitados pelo usuário
até que o usuário digite um número menor que 0. No final, imprima o maior número digitado.

"""

# Inicializa a variável 'maiorNumero' com -1 para comparar com os números digitados
maiorNumero = -1

# Solicita ao usuário que digite um número inteiro e maior que zero
numeroDigitado = int(input("Digite um número inteiro e maior que ZERO: "))

# Continua o loop enquanto o número digitado for maior ou igual a 0
while numeroDigitado >= 0:

    # Verifica se o número digitado é maior que o 'maiorNumero' armazenado
    if numeroDigitado > maiorNumero:
        
        # Atualiza 'maiorNumero' se o número digitado for maior
        maiorNumero = numeroDigitado

    # Solicita ao usuário que digite um novo número inteiro e maior que zero
    numeroDigitado = int(input("Digite um número inteiro e maior que ZERO: "))
    
# Imprime o 'maiorNumero' após cada entrada; esta linha deve estar fora do loop 'while' para imprimir apenas o resultado final
print("Maior número: ", maiorNumero)

    
"""
Explicação:

    Definindo Variável de Maior Número: A variável maiorNumero é inicializada 
    com o valor -1, uma escolha que garante que qualquer número positivo digitado
    será maior que o valor inicial.

    Entrada Inicial do Usuário: A função input solicita ao usuário que digite 
    um número inteiro e maior que zero. A entrada é convertida em um número inteiro e 
    armazenada na variável numeroDigitado.

    Loop While: A estrutura while cria um loop que continuará executando enquanto 
    numeroDigitado for maior ou igual a 0.

    Corpo do Loop: Dentro do loop:
    
        Verificar se é o Maior Número: A instrução if verifica se numeroDigitado 
        é maior que maiorNumero. Se for, numeroDigitado é atribuído a maiorNumero.
        
        Pedir Novo Número: A função input solicita ao usuário que digite um novo 
        número, e a entrada é convertida em um número inteiro e armazenada em numeroDigitado.
        
        Imprimir Maior Número: A função print imprime a mensagem "Maior número: " seguida 
        pelo valor de maiorNumero. Isso ocorrerá em cada iteração do loop.

    Saída do Loop: O loop continuará executando até que o usuário digite um número 
    negativo. Uma vez que um número negativo seja inserido, o loop terminará.

Exemplo de Saída:

Suponha que o usuário insira os valores 5, 10, 3, e então -1. A interação com o 
programa seria assim:

Digite um número inteiro e maior que ZERO: 5
Maior número:  5
Digite um número inteiro e maior que ZERO: 10
Maior número:  10
Digite um número inteiro e maior que ZERO: 3
Maior número:  10
Digite um número inteiro e maior que ZERO: -1
Maior número:  10

"""
print()

"""
Digite um número inteiro e maior que ZERO: 40
Digite um número inteiro e maior que ZERO: 34
Digite um número inteiro e maior que ZERO: 12
Digite um número inteiro e maior que ZERO: 29
Digite um número inteiro e maior que ZERO: 50
Digite um número inteiro e maior que ZERO: 39
Digite um número inteiro e maior que ZERO: 41
Digite um número inteiro e maior que ZERO: 0
Digite um número inteiro e maior que ZERO: -1
Maior número:  50
"""

"""
Exercício: Simulação de Caixa Eletrônico

Objetivo: Desenvolver um programa em Python que simula as 
operações básicas de um caixa eletrônico. O usuário deve ser capaz de 
verificar o saldo, depositar dinheiro, sacar dinheiro e sair do programa.

Requisitos:

    Verificar Saldo:
    
        - Ao escolher essa opção, o programa deve exibir o saldo atual da conta.

    Depositar Dinheiro:
    
        - O usuário deve ser capaz de inserir uma quantia para depositar na conta.
        - A quantia deve ser positiva.
        - Após um depósito bem-sucedido, o saldo da conta deve ser atualizado e uma 
        mensagem de confirmação deve ser exibida.

    Sacar Dinheiro:
    
        - O usuário deve ser capaz de inserir uma quantia para sacar da conta.
        - A quantia deve ser positiva e não deve exceder o saldo atual.
        - Após um saque bem-sucedido, o saldo da conta deve ser 
        atualizado e uma mensagem de confirmação deve ser exibida.

    Sair:
    
        - O usuário deve ser capaz de sair do programa escolhendo essa opção.

    Validação de Entrada:
    
        - O programa deve lidar com entradas inválidas de forma adequada, exibindo mensagens de erro quando aplicável.

    Interface de Usuário:
    
        - O programa deve exibir um menu de opções para o usuário e permitir 
        a seleção de ações a serem realizadas.
        - As opções do menu devem ser apresentadas em um loop, permitindo 
        múltiplas operações até que o usuário escolha sair.
        
            Caixa Eletrônico
            1 - Verificar Saldo
            2 - Depositar Dinheiro
            3 - Sacar Dinheiro
            4 - Sair
            Escolha uma opção (1-4):

    Saldo Inicial:
    
        - A conta deve começar com um saldo inicial de R$ 1000.00.

Instruções:

    - Comece inicializando o saldo e entrando em um loop que apresente o menu de opções.
    - Implemente cada operação como descrito nos requisitos.
    - Certifique-se de testar todas as opções e cenários possíveis para garantir que 
    o programa funcione corretamente.


Dica: Você pode usar condicionais if, elif, e else juntamente com um loop while 
para gerenciar as seleções do usuário e manter o programa em execução 
até que a opção de sair seja escolhida.

"""

saldo = 1000.00  # Define o saldo inicial da conta

# Inicia um loop infinito que continuará até que o usuário escolha a opção de sair
while True:
    
    # Imprime as opções do menu disponíveis para o usuário
    print("\nCaixa Eletrônico")
    print("1 - Verificar Saldo")
    print("2 - Depositar Dinheiro")
    print("3 - Sacar Dinheiro")
    print("4 - Sair")
    
    opcao = input("Escolha uma opção (1-4): ")  # Solicita que o usuário escolha uma opção

    # Verifica a opção escolhida pelo usuário e executa a ação correspondente
    if opcao == '1':
        
        print(f"Seu saldo é: R$ {saldo:.2f}")  # Imprime o saldo atual da conta
        
    elif opcao == '2':
        
        deposito = float(input("Digite o valor do depósito: R$ "))  # Solicita o valor do depósito
        
        if deposito > 0:  # Verifica se o valor do depósito é positivo
            
            #saldo = saldo + deposito
            saldo += deposito  # Adiciona o valor do depósito ao saldo
            print(f"Depósito de R$ {deposito:.2f} realizado com sucesso!")  # Confirma o depósito
            
        else:
            
            print("Valor de depósito inválido.")  # Informa que o valor do depósito é inválido
            
    elif opcao == '3':
        
        saque = float(input("Digite o valor do saque: R$ "))  # Solicita o valor do saque
        
        if saque > 0 and saque <= saldo:  # Verifica se o valor do saque é válido e se há saldo suficiente
            
            saldo -= saque  # Subtrai o valor do saque do saldo
            
            print(f"Saque de R$ {saque:.2f} realizado com sucesso!")  # Confirma o saque
            
        else:
            
            print("Valor de saque inválido ou saldo insuficiente.")  # Informa que o valor do saque é inválido ou que não há saldo suficiente
    
    elif opcao == '4':
    
        print("Obrigado por utilizar o nosso caixa eletrônico. Até mais!")  # Agradece o usuário e prepara-se para sair do loop
        
        break  # Sai do loop, terminando o programa
    
    else:
    
        print("Opção inválida. Por favor, tente novamente.")  # Informa ao usuário que ele escolheu uma opção inválida e continua o loop
            

"""
Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 1000.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 2
Digite o valor do depósito: R$ 500
Depósito de R$ 500.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 1500.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 3
Digite o valor do saque: R$ 200
Saque de R$ 200.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 1300.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 3
Digite o valor do saque: R$ 1200
Saque de R$ 1200.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 100.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 3
Digite o valor do saque: R$ 150
Valor de saque inválido ou saldo insuficiente.

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 3
Digite o valor do saque: R$ 100
Saque de R$ 100.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 0.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 2
Digite o valor do depósito: R$ 3000
Depósito de R$ 3000.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 3000.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 3
Digite o valor do saque: R$ 500
Saque de R$ 500.00 realizado com sucesso!

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 1
Seu saldo é: R$ 2500.00

Caixa Eletrônico
1 - Verificar Saldo
2 - Depositar Dinheiro
3 - Sacar Dinheiro
4 - Sair
Escolha uma opção (1-4): 4
Obrigado por utilizar o nosso caixa eletrônico. Até mais!
"""

"""
Exercício: Calculadora Simples

Desenvolva uma calculadora simples que permite ao usuário realizar operações 
básicas de adição, subtração, multiplicação e divisão.

Objetivos:

    Mostrar um Menu ao Usuário:
    
        - A calculadora deve exibir um menu com cinco opções: 
            - adição
            - subtração
            - multiplicação
            - divisão
            - sair
            
        O usuário deve ser capaz de selecionar a operação desejada através da entrada de um número correspondente.

    Receber Dois Números:
    
        - Após selecionar a operação, o usuário deve inserir dois números
        que serão utilizados na operação.

    Realizar a Operação Selecionada:
    
        - A calculadora deve realizar a operação selecionada com os números 
        inseridos e exibir o resultado.
        
    Repetir ou Encerrar:
    
        - Após cada operação, o menu deve ser exibido novamente, permitindo que 
        o usuário realize outra operação ou saia do programa.
        - O programa deve continuar funcionando até que o usuário escolha sair.


Boa sorte e divirta-se programando!
"""

#Incinia loop para manter o programa rodando até o usuário decidir sair
while True:
    
    #Mostra o menu de operações
    print("\nCalculadora Simples:")
    print("1 - Adição")
    print("2 - Subtração")
    print("3 - Multiplicação")
    print("4 - Divisão")
    print("5 - Sair")
    
    #Receber a escolha do usuário
    escolha = input("Escolha uma operação: ")
    
    #Condição para sair do programa
    if escolha == "5":
        
        print("Até mais!")
        
        break
        
    #Receber os dois números para a operação
    num1 = float(input("Digite o primeiro número: "))
    num2 = float(input("Digite o segundo número: "))
    
    # Condição para Adição
    if escolha == "1":
        
        resultado = num1 + num2
        print("Resultado:", resultado)
        
    # Condição para subtração
    elif escolha == "2":
        
        resultado = num1 - num2
        print("Resultado:", resultado)
        
    # Condição para multiplicação
    elif escolha == "3":
        
        resultado = num1 * num2
        print("Resultado:", resultado)
        
    # Condição para divisão
    elif escolha == "4":
        
        #Verificar se o divisor é zero para evitar erro de divisão por zero
        if num2 != 0:
                        
            resultado = num1 / num2
            print("Resultado:", resultado)
            
        else:
            
            #Mensagem de erro para divisão por zero
            print("Erro: Divisão por zero.")
       
    #Condição para opção inválida
    else:
        
        print("Opção inválida! Tente novamente.")

"""
Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 1
Digite o primeiro número: 10
Digite o segundo número: 5
Resultado: 15.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 2
Digite o primeiro número: 30
Digite o segundo número: 25
Resultado: 5.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 3
Digite o primeiro número: 20
Digite o segundo número: 8
Resultado: 160.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 4
Digite o primeiro número: 10
Digite o segundo número: 2
Resultado: 5.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 4
Digite o primeiro número: 10
Digite o segundo número: 0
Erro: Divisão por zero.

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 4
Digite o primeiro número: 100
Digite o segundo número: 4
Resultado: 25.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 4
Digite o primeiro número: 10
Digite o segundo número: 2
Resultado: 5.0

Calculadora Simples:
1 - Adição
2 - Subtração
3 - Multiplicação
4 - Divisão
5 - Sair
Escolha uma operação: 5
Até mais!
"""

#While Usando uma Condição Complexa

# O exemplo abaixo demonstra um programa que continua incrementando x e decrementando y 
#enquanto x for menor que 10 e y for maior que 10.

# Inicializando duas variáveis, x e y
x, y = 5, 15

# O loop continuará enquanto ambas as condições forem verdadeiras: x < 10 e y > 10
while x < 10 and y > 10:
    
    print(f"x: {x}, y: {y}")  # Imprimindo os valores atuais de x e y
    
    #x = x + 1
    x += 1  # Incrementando x em 1
    
    #y = y - 1
    y -= 1  # Decrementando y em 1
    
# Quando a condição do loop não for mais satisfeita, esta linha será executada
print("Loop concluído")
print(f"Valores finais - x: {x}, y: {y}")

"""
Neste exemplo, a condição complexa x < 10 and y > 10 é usada para 
controlar o loop. Ambas as partes da condição devem ser verdadeiras para 
que o loop continue. Se qualquer uma das partes se tornar falsa, o loop será interrompido. 
Isso ilustra como você pode usar condições complexas para controlar o fluxo de 
execução em um loop while.
"""

"""
x: 5, y: 15
x: 6, y: 14
x: 7, y: 13
x: 8, y: 12
x: 9, y: 11
Loop concluído
Valores finais - x: 10, y: 10
"""

#While Usando uma Condição Complexa

# Definindo dois números secretos
numero_secreto1 = 7
numero_secreto2 = 3

# Definindo o número de tentativas
tentativas = 5

# Variáveis para rastrear se os números foram adivinhados
adivinhou1 = False
adivinhou2 = False

# O loop continuará enquanto ambas as condições forem verdadeiras: 
#tentativas restantes e pelo menos um número não adivinhado
while tentantivas > 0 and (not adivinhou1 == True or not adivinhou2 == True):
    
    print(f"Tentantivas restantes: {tentantivas}")
    
    palpite1 = int(input("Adivinhe o primeiro número secreto (1-10): "))
    palpite2 = int(input("Adivinhe o segundo número secreto (1-10): "))
    
    # Se palpite1 é igual ao numero_secreto1 imprime a mensagem
    if palpite1 == numero_secreto1:
        
        print("Você adivinhou o primeiro número!")
        
        adivinhou1 = True
        
    # Se palpite1 é igual ao numero_secreto1 imprime a mensagem
    if palpite2 == numero_secreto2:
        
        print("Você adivinhou o segundo número!")
        
        adivinhou2 = True
        
    # Se não adivinhou  exibe tente novamente
    if not adivinhou1 == True or not adivinhou2 == True:
        
        print("Tente novamente.")
        
        #Reduzindo as tentantivas restantes
        tentantivas -= 1
        
if adivinhou1 == True and adivinhou2 == True:
    
    print("Parabéns! Você adivinhou ambos os números!")
    
else:
    
    print(f"Você não conseguiu adivinhar os números. Eles eram {numero_secreto1} e {numero_secreto2}")
    

"""
Tentantivas restantes: 5
Adivinhe o primeiro número secreto (1-10): 7
Adivinhe o segundo número secreto (1-10): 3
Você adivinhou o primeiro número!
Você adivinhou o segundo número!
Parabéns! Você adivinhou ambos os números!
"""
