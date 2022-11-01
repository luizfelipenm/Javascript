# Javascript
Javascript - exercícios
Esta atividade poderá ser feita em grupo de até três pessoas.

A atividade deverá ser entregue em um repositório no Github. O nome dos participantes deve ser informado no arquivo README.md.

Atividade 1:
Escreva o código HTML, CSS e Javascript que solicite duas notas: nota1 e nota2.

A seguir, calcule a média aritmética. Use media = (nota1+nota2)/2; 

Se a media for maior ou igual a seis a situação será APROVADO e deve ser exibida na cor AZUL, senão a situação será REPROVADO e deve ser exibida na cor VERMELHA.

Use uma tag <span> com um id apropriado para marcar o lugar onde exibirá a média e outra tag <span> para exibir a situação. Vamos usar a propriedade innerHTML para alterar o conteúdo dessas tags de acordo com a media das notas informadas.

Atenção: Faça duas versões deste código:

1) os dados serão informados usando a instrução prompt() do Javascript

2) os dados serão informados em campos criados pela tag <input> (será necessário estudar eventos HTML)

Algoritmo:

1. Obter nota1

2. Obter nota2

3. calcular média: media = (nota1 +nota2) / 2

4) se (media >=6) então {

       situacao = "Aprovado";

       cor="azul";

      } senão {

      situacao = "Reprovado";

      cor="vermelho";

     }

5. Mostrar Média e Situacao.

Dica: 

1) O valor digitado pelo usuário será do tipo texto, mesmo que contenha apenas dígitos, será necessário  usar a função "parseFloat()"  para converter para número.

2) Para mostrar a média e a situação use a tag <span> para marcar a posição onde irá aparecer a informação, por exemplo: <p>Média <span id="media"></span></p>

    Depois use altere a propriedade "innerHTML" para alterar a informação que é exibida no navegado.

Atividade 2:
1) Leia o artigo Índice de Massa Corporal (IMC) na Wikipedia. Especialmente a fórmula do cálculo do IMC e a tabela do IMC.
Escreva o código usando HTML, CSS e Javascript para que o usuário informe o peso e a altura.

O programa deve calcular o IMC e mostrar o valor obtido.

Usando a instrução if e a tabela do IMC, mostre qual é a situação do usuário de acordo com o IMC calculado.

Use CSS para mudar a cor da situação para indicar normalidade (verde), alerta (laranja: acima ou abaixo do peso) ou perigo (vermelho: muito abaixo/Obesidade I, Obesidade II, Obesidade III).



Atividade 3:
2)  Estude o exemplo sobre "appendChild" que está no site w3schools https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_node_appendchild

Faça as seguintes alterações:

acrescente uma tag input para informar o texto do item da lista a incluir. Use o atributo 'value' para recuperar o valor digitado.
acrescente três botões de rádio para escolher a cor do item da lista. Fique a vontade para escolher as cores
Para descobrir qual dos botões de rádio está marcado veja o exemplo abaixo: (veja esta referência link do Stackoverflow)

cor = document.querySelector('input[name="cores"]:checked').value;

Use o método "addEventListener()" para substituir a chamada da função "myFunction()" diretamente no atributo "onclick", 
