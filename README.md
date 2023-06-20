![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) 

link encurtado para compartilhar -> www.bit.ly/gitsenai

# Ajudinha para as aulas
Nome dos arquivos => Datas nos nomes YY-MM-DD




   <summary> Concatenação </summary>
	
	using static System.Console;
	string var = "texto";
	WriteLine($" usando uma variavel direta {var}");
	WriteLine(" usando um operador " + var);


	
## Condicionais


  <summary> If else </summary>
	
	using static System.Console;
	int num = 0;
	if (num == 0)
	{
	    WriteLine("Num é igual a zero");
	}
	else
	{
	    if (num != 0)
	    {
	        WriteLine("Num é diferente de zero");

	    }
	}
	




  <summary> Switch case </summary>

	using static System.Console;

	string frase1 = "esta é a frase 1";
	string frase2 = "aqui escrevo a frase 2";
	string frase3 = "leia aqui a frase 3";
	char opcao;

	WriteLine("escolha uma opcao de 1 - 3");
	opcao = (char)Read();
	switch (opcao)
	{
	    case '1':
	        WriteLine(frase1);
	        break;
	    case '2':
	        WriteLine(frase2);
	        break;
	    case '3':
	        WriteLine(frase3);
	        break;

	    default:
	        WriteLine("Caracter inválido !");
	        break;
	}
	




  <summary> for </summary>

	using static System.Console;

	for (int i = 0; i < 10; i++)
	{
	    WriteLine($"loop atual : {i}");
	}
	

	

  <summary> Foreach </summary>

	string[] nomes = { "cleber", "carol", "Denis", "Roberto" };

	foreach (string item in nomes)
	{
	    WriteLine($"{item}");
	}
	





  <summary> do while </summary>
	
	using static System.Console;
	int i = 0;
	do {
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}while (i< 10);
	




  <summary> while </summary>

	using static System.Console;
	int i = 0;
	while (i < 10)
	{
	    WriteLine($"loop atual : {i+1}");
	    i++;
	}



### Operadores	
	

  <summary> operações logicas </summary>

	a == b	-> A é igual B
	a != b	-> A Diferente de B
	a < b 	-> A menor q B
	a <= b	-> A Menor ou igual a B
	a > b 	-> A maior q B
	a >= b 	-> A maior ou igual q B
	!a	-> negação do A, se A for TRUE, será considerado FALSE

	


  <summary> Operador aritméticos </summary>
	
	+	adição
	-	subtração
	*	multiplicação
	/	divisão
	%	módulo (resto da divisão)
	




  <summary> Operador Logico </summary>

	&&	And = E
	||	OR = OU
	!	NOT = NÃO


### Outros itens
	using static System.Console;
	

  <summary> read line e convert </summary>

	WriteLine("Escreva seu nome");
	nome = ReadLine();
	WriteLine("escreva sua idade");
	idade = Convert.ToInt32(ReadLine());


	

  <summary> Variaveis </summary>
	
	int = numeros inteiro 				-> 1, 2, 5;
	string = texto 					-> "texto texto";
	char = caractere				-> 't','e','x','t','o';
	double = numero racional (com ponto)		-> 1.53 , 8.69
	boolean = se é verdadeiro ou falso 		-> true || false
	

	

  <summary> Arredondamento casas decimais </summary>
	
	double velMS, velKmH;
	int digitos = 2;
	WriteLine($"Escreva a velocidade em m/s");
	velMS = Convert.ToDouble(ReadLine());
	velKmH = (velMS * 3.6);
	WriteLine($"{velMS} m/s => {Math.Round(velKmH,digitos)} Km/h");

