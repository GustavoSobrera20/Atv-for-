//ATIVIDADE 1- Implemente uma contagem regressiva de 10 até 0 utilizando um laço de repetição.
 
     for ( cont = 10; cont >= 0; cont--) { 
     console.log (cont)valor
     }
    valor do cont virou 10, e coloquei para diminuir regressivamente com o cont--


//ATIVIDADE 2-Escreva um programa que peça ao usuário para digitar um número e exiba sua tabuada de 1 a 10.

    numero = 0 

    numero = parseInt (prompt ("Digite um numero")) 

    resultado = 0 

    for (tabuada = 0; tabuada <= 10; tabuada = tabuada + 1){ 
    resultado = numero + 'X' + tabuada + '=' + (numero * tabuada) 
    console.log (resultado) 

    fiz a vaiavel do numero fornecido

    foi criado para ser lido como realmente numero por causa do parseint, sem ele o numero nao seria usavel

    varaivel para receber o valor fornecido pela var numero

    criei a var tabuada iniciando do 0, ate o numero vezes 10, e coloquei o tabuada = tabuda + 1 para ir contando de 1 em 1, poderia ser usado     o tabuada++ tambem

    coloquei para que o resultado receba o valor do numero escolhido do usuario da var numero, e fui fazendo as strings no meio da linha para        ficar bonito, e fui adicionando a var tabuada  e depois entere parenteses a minha operação que é vezes.

//ATIVIDADE 3- Calcule a soma de todos os números de 1 a 100 utilizando um laço de repetição.



    soma = 0 //variavel criada para guardar numero 

    for(cont = 1; cont <= 100; cont++){ 
    resultado = soma += cont 
    }
    console.log ('o resultado da soma de 1 a 100 é:'+ resultado)

    
// ATIVIDADE 4- Imprima todos os números pares de 1 a 20 utilizando um laço de repetição

    for (let i = 2; i <= 20; i += 2) {            
    console.log(i) 
    }

  //ATIVIDADE 6- Escreva um programa que peça ao usuário para digitar um número e exiba a soma de todos os números ímpares até esse número.

    resultado = 0 // esta var esta funcionando nas duas variações do mesmo codigo
    soma = 0 // esta var esta funcionando nas duas variações do mesmo codigo

    numero = parseInt (prompt('Digite o numero')) //Esta sendo usado pelos dois codigos, e a variavel numero tambem esta sendo usado 

    for (cont = 1; cont <= numero; cont + 1){ //dei o valor da var numero da linha 187 ao cont, e finalizei com o cont + 1 para ele contar de 1     em 1
    resultado = cont += 2 // coloquei a var resultado = cont e adicionei mais 2 
    soma = soma += resultado - 2 // na linha acima, o meu cont vale 3, e nessa linha eu tirei 2 para ele virar 1, e consequentemente começar   pelo numero impar 1.
    }
    console.log('A soma de todos os numeros impares do numero fornecido é:' + soma)

    soma = 0 // zerei a var soma do codigo acima para começar o novo mesmo codigo abaixo

    // Mesmo codigo mas mais simplificado
    for (cont = 1; cont < numero; cont += 2){ // a var numero esta sendo puxada la na linha 187 que eu adicionei no meu parseint e prompt
    soma += cont // coloquei o valor do cont no soma 
    }
      console.log('A soma de todos os numeros impares do numero fornecido é:' + soma)

atv realizada com a ajuda do @CauaCanale
