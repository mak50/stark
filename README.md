fun main()
  //println("o println serve para exibir textos no console")
  //*
    * para
    *fazer
    *comentarios de



//.............................................................................................
/*
fun main() {
   //exercio para fazer um diálogo de no minimo 10 linhas usando a declaração println()
   //
println("Meri_você já viu aquele filme ? ")
println("<Meri> Qual ?")
println(" Aquele com o  ator auto e careca ")
println("<Meri> O Vin Diesel?")
println("Nop_ Ele fez no ano passado o filme Jungle Cruise_ lembra?_ tinha a Emily Blunt ")
println("<Meri> Não me recordo desse_ Mas qual é o nome do filme?")
println("é um filme da DC")
println("<Meri> Ok,é um filme de super herói, mas qual é o nome? ")
println("Vc tem assistir o filmr é perfeito tem uma ótima atuação, o CGI é fantástico, o roteiro super criativo")
println("<Meri> Entendi_mas qual é o filme? ")
println("Ah_ é Adão Negro")
println("<Meri> Sério?")
println("Sim")
println("<Meri> Eu já assisti")
println("Gostou?")
println("<Meri> Eu achei bem chato")

//Variáveis - armazenam valores, dados, informações 
//val - não mutavel - não podemos alterar o seu valor
//var - mutável - podemos mudar o seu valor
//
// Tipos de variáveis: 
// 
//String - 
//Int - 
//Float - 
//Double - 
//Long - 
//Boolean - 
}
*/


//....................................................................................................................................................
/*
fun main() {
    // Tipos de variáveis: 
// 
//String - armazena valores de tipo texto - detro de ""  ==> ex: "abóbora"
//Int - armazena números interiores  ==> 1822
//Float - armazena números reais (no geral) - necessita de um f no valor  ==>72.24f
//Double - armazena números quebrados (de forma arredondada)  ==> 8.9
//Long - armazena números longos 56464656.3572354
//Boolean - verdadeiro ou falso ==> true, false 
/*
var cr7 = "Cristiano Ronaldo"
var numeroChampions = 5
var altura = 1.87 
     
//Concatenação 

println("O nome dele é " + cr7 +", ele tem " + numeroChampions)
print("titulos de Champions Legue e ele tem "+ altura + "de altura")



var laPulga = "Lionel Messi "
var champions = 4 
var alturaDele = 1.02  
print("O nome dele é $laPulga, ele tem $champions títulos de champions, ele tem apenas $alturaDele de altura" )
*/


/*
var ninsay = "iasmin" 
var idade = 16 
var tamanho = 1.65
var gostaDe = "Assistir,ler e desenhar" 
var mj = " eu sou fã do Michael Jackson"
    
print("Meu nome é $ninsay, tenho %idade anos,tenho apenas $tamanho de altura,sou uma pessoa que não fico quieta eu gosto de $gostaDe, e $mj")
*/ 
    
    
//Operadores matemáticos 
//
// + => adição 
// - => subtação 
// / => divisão 
// * => multiplicação 
// % => módulo 

//println( 100 *100 ) 
//
//
//== => igual 
//!= => diferente 
// >=> maior que ..... 
// <=> menor que ...... 
// >= -> maior or igual a ..... 
// <= -> menor ou igual a ..... 
// 
*/
    
 var y = 5
 var rdj = 50 
    
 println("~~~~~~~~~~~~~~~~~~~~~~~~~~~")   
 println("  (: CALCULADORA :)      " )  
 println("~~~~~~~~~~~~~~~~~~~~~~~~~~~")
 println("$y + $rdj =                ")
 println(y+rdj                        )
 
 println("---------------------------")
 
 println("$y - $rdj =                ")
 println(y-rdj                        )  
 
 println("---------------------------")
 
 println("$y * $rdj =                ")
 println(y*rdj                        )
 
 println("---------------------------")
 
 println("$rdj / $y =                ")
 println(rdj/y                        )
 
 println("~~~~~~~~~~~~~~~~~~~~~~~~~~~")  

}
  
  
  //................................................................................................

  
  fun main() {  
    
    //Condições 
    //
    //condição simples 
    //
    //if  --> se... 
    //else --> senão... 
    /*
    var lembreidochocolate ="sim"     
    
    if(lembreidochocolate == "sim"){
        println("Vou entregar o chocolate para você") 
    }else{ 
        println("Chocolate pra todo mundo")           
    }      
    //se a condição for verdadeira, a sua ação será executada, senão,  outra ação será 
    //executada 
    // 
   
   
   var mjfezaturnethisisit = "não" 
    
   if (mjfezaturnethisisit == "não"){
   println("Não ele não fez" ) 
   }else{
   println("isso é tudo" ) 
   } 
   
   //condições compostas  
   
   var coracoes = 1 
    
    if(coracoes == 5){ 
        println("Você está ótimo!! Bom para vc") 
    }else if(coracoes == 4){ 
        println("Ce ta bem") 
    }else if(coracoes == 3)      
    println("ce tá ok") 
    
    */ 
    
    var idade = 18
    
    if(idade<=3){ 
        println("Você é um bebe") 
    }else if(idade <=12){ 
        println("Você é muito infantil!!") 
    }else if(idade <=18){ 
        println("tu é jovem!! aproveite a vida") 
    }else if (idade <=60){
        println("Tu é adulto!! pague a conta!!!!") 
    }else if(idade > 60){ 
        println("Que que há velhinho?") 
    }else{ 
        println("Você não existe!!:)") 
    }   
//------------------------------------------------------------------------------------------------    
    
  fun main() {
 
    //Operadores Lógicos 
    //
    //são usados quando queremos comparar mais de uma coisa na mesma condição 
    //
    // && => e 
    // || => ou (shift + barra invertida) 
    // 
    // TABELA VERDADE (com E e OU ) 
    // 
    // && - a determinada ação só acontecerá se e somente se todas as 
    // condições forem verdadeiras 
    // 
    // VV => verdadeiro 
    // VF => falso 
    // FV => falso 
    // FF => falso 
    // 
    // || - a determinada ação será executada se pelo menos uma das 
    // condições forem verdadeiras 
    // 
    // VV => verdadeiro 
    // VF => verdadeiro 
    // FV => verdadeiro 
    // FF => falso 
    //
    // Show do Péricles  
    /*
    var idade = 14
    var acompanhadoDosPais = false
    
    
    if(idade >= 14 || acompanhadoDosPais == true){
        println("Pode entrar, curta o show")
    }else{
        println(" A entrada não é permitida para você ")
    }   
  */ 
    //Exercício ~~ A seleção brasileira está correndo risco de ser eliminada na fase de grupos 
    //da copa, o Brasil, só pode se classificar se o México perder, e se o próprio Brasil 
    //ganhar.As partidas já passaram, quero saber se o Brasil se classificou ou não.
    //
    // detalhe: use os operadores lógicos. 
    // 
    // ----- COPA---- 
    
   
    var aPERDEU = true 
    var bGANHOU = true
    
    if(aPERDEU == true || bGANHOU == false){
        println("ae México perdeu!!")
    }else{ 
        println("No próximo ano talvez")
    }    
//-----------------------------------------------------------------------------------------------------------------    
    
fun main() {
    
   //Exercício ~~ A seleção brasileira está correndo risco de ser eliminada na fase de grupos 
    //da copa, o Brasil, só pode se classificar se o México perder, e se o próprio Brasil 
    //ganhar.As partidas já passaram, quero saber se o Brasil se classificou ou não. 
    // detalhe: use os operadores lógicos.  
    
    /*
    var brasil = false 
    var alemanha = true 
    var marrocos = true 
    
    if(!alemanha && brasil && !marrocos ){ 
        println("Pode isso Arnaldo, Brasil classificado!! Rumo ao hexa! Haja coração") 
    }else{ 
        println("Acabou, só queria dar alegria ao meu povo") 
    }     
   */ 
    
 // WHEN = Quando 
 // 
 // Quando uma determinada condição for verdadeira, outra determinada 
 // ação será executada. 
 // 
 //  Estrutura Do When: 
 //  
 // when(var){ 
 // valor -> ação a ser executada 
 // outroValor -> ação
 // maisUm -> ação 
 // outro -> ação 
 // else -> ação 
 //  
 // 
     
 var mes = 2    
    
 when(mes){ 
     1 -> println("Acapulco - Mex") 
     2 -> println("Paris - Fra" )
     3 -> println("Berlim - Ale" )
     4 -> println("Monaco - Mon" )
     5 -> println("Pequim - Chi" )
     6 -> println("Acre - Bra" )
     7 -> println("Roma - Itá")
     8 -> println("Atena - Gre ")
     9 -> println("Madrid - Esp")
     10 -> println("Manchester - Ing")
     11 -> println("Dubai - Eau")
     else -> println("São Paulo - Bra") 
 } 
 
//===================================================================================================================== 
 
   
fun main() { 
    
    // laços de Repetição 
    // 
    // while => enquanto 
    // for => para... 
    // do...while => faça...enquanto
    // repeat => repita 
    
    
    // Laço while 
    // enquanto uma determinada condição for verdadeira, outra determinada 
    // ação será executada 
    // 
    // Estrutura do while 
    // 
    // while(condição){ 
    // ação 
    // } 
   /*
    var number = 0  
    
    while(number < 47){ 
        println(number) 
        number++ 
    } 
    // Ex - 2
    
    var idade = 1 
     
    while(idade < 17){ 
        println( "$idade anos? Cresça, sério") 
        idade++ 
    }   
        println("Divirta-se, vc chegou até aqui, vc merece") 
   */   
   
    // Laço do...while 
    // 
    // Uma determinada ação será executada, enquanto outra determinada condição for 
    // verdadeira 
    //  
    // Estrutura do...while 
    // 
    // do{ 
    // ação 
    // }while(condição) 
    /*
    var idade = 1 
    
    do{ 
        println("$idade anos? Cresça, sério") 
        idade++ 
    }while(idade < 17)  
    
    //Exercício -> O ano não é ano bissexto, portanto o ano possui 365 dias, precisa ser exibido no console 
    //os números de 1 a 365, usando no minímo uma variável, usando os laços while e 
    //do...while 
    */
   
    var dia = 1  
    
    while(dia <= 365){ 
        println(dia) 
        dia++ 
    }    
    
    
    
    var passado = 1 
    do{ 
        println("$passado,mas um dia se passou")
        passado++ 
    }while(passado <= 365)  
}  
        
 //==================================================================================================================   
    
    
    fun main() { 
    
  // for => para... 
  // 
  // for - para cada item em uma lista ou qualquer tipo de coleção, será executado uma 
  // determinada ação 
  // 
  // Estrutura do for : 
  // for (item in list/collection/intervalo){ 
  // ação 
  // } 
  // 
  /*
  for(item in 1..10){ 
      println(item) 
  }   
  
  //Exercicío: faça a tabuada de um número de sua escolha(não pode ser a do 0,1,2 e 10) 
  //.OBS: precisa utilizar o laço for 
  //
  
   for(item in 1..10){ 
      println(item * 5 )     
  }   
  */
  // Repeat => Repita... 
  // 
  // Uma determinada ação será repetida um determinado número de vezes 
  //  
   
  repeat(5*1+5){ 
      println("||-----tartaruga-----||") 
  }    
  
  //**********************************************************************************************************************************


fun main() {
    
    //Collections - Coleções 
    //
    //<> ---> tags = servem para especificar o tipo de valor a ser listado
    //
    //São determinados conjuntos de itens/valores  que podem ser modelados e utilizados 
    //em determinados métodos e operações. 
    //
    //list - listas 
    //
    //listOf --->listam itens de variados tipos 
    // 
    
    //var genericlist = mutableListOf("São Paulo, arroz e pamonha",25.7f, 23.974,'$', false)   
    //println(genericlist) 
    
    var specificlist = listOf<String>("cruzeiro do Roberto Carlos","Calleri","5" ) 
    println(specificlist) 
    
    
    //Index - uma posição da collection  
    
    //Propriedades - list 
    //
    // .lastIndex 
    // .size 
    // 
    // 
    //println(specificlist.lastIndex) 
    //println(specificlist.first()) 
    //println(specificlist.size) 
    //println(specificlist.get(2)) 
    //println(specificlist[2]) 
    //println(specificList.indexOf("Cruzeiro do Roberto Carlos"))
    
    /*
    //Métodos --> listOf 
    genericlist.add(2,"mak") 
    println(genericlist) 
    genericlist.remove(23.974) 
    println(genericlist) 
    genericlist.removeAt(3) 
    println(genericlist) 
    genericlist.set(0, "tartaruga") 
    println(genericlist) 
    
    genericlist.clear() 
    println(genericlist) 
    */
    var anotherlist = setOf("Pedro","Diniz", "Pelé", "Ronaldinho", "Marília Mendonça", "Diniz")   
     println(anotherlist) 
     
    var animal = mutableMapOf("tartaruga" to 0, "jabuti" to 1, "tucano"   to 2, "hiena"to 3, "macaco"  to 4, ) 
    println(animal)
   
//---------------------------------------------------------------------------------------------------------------------------
    
}    
    
fun main() { 
    /*
    /Métodos --> listOf 
    genericlist.add(2,"mak") 
    println(genericlist) 
    genericlist.remove(23.974) 
    println(genericlist) 
    genericlist.removeAt(3) 
    println(genericlist) 
    genericlist.set(0, "tartaruga") 
    println(genericlist) 
    
    genericlist.clear() 
    println(genericlist) 
    */
   //var anotherlist = setOf("Pedro","Diniz", "Pelé", "Ronaldinho", "Marília Mendonça", "Diniz")   
  // println(anotherlist) 
     /*
    var animal = mutableMapOf("tartaruga" to 0, "jabuti" to 1, "tucano"   to 2, "hiena" to 3, "macaco"  to 4, ) 
    println(animal) 
    
    animal.put("capivara",5) 
    println(animal) 
    animal.put("leopardo",9)
    println(animal) 
    animal.replace("tatu",3) 
    println(animal) 
   */ 
    
    //POO 
    //
    // Programação Orientada a objetos 
    //
    // Objetos = estados (características: nome, idade, cpf )
    //
    // Comportamentos - (andar, comer, dormir, conversar,programar)
    //
    // Classes - Modelos que servem para construção de objetos derivados
    // 
    val pessoa1 = Pessoa() 
    pessoa1.nome = "Ninsay Pierre" 
    println(pessoa1.nome) 
    println(pessoa1.idade) 
    println(pessoa1.altura)  
    println(pessoa1.resultado) 
    println(pessoa1.recomendações)

        
} 

class Pessoa(){ 
    // Declarações de atributos para a classe Pessoa 
    var nome = "Ninsay Pierre"  
    var idade = 23 
    var altura = 1.60 
    var resultado = "A paciente apresentou intolerância lactose " 
    var recomendações = " É recomendado evitar leite e seus derivados. "
    
// Exercício - Faça uma ficha médica apontando os resultados do último checkup de um cliente. 
// Permitido usar a mesma classe pessoa()   
    
    
//-----------------------------------------------------------------------------------------------------------------    
    
}    
    fun main() { 
   
// Exercício - Faça uma ficha médica apontando os resultados do último checkup de um cliente. 
// Permitido usar a mesma classe pessoa()    

    var paciente007 = Paciente()
    paciente007.nome = "James Bond" 
    paciente007.idade = 12 
    paciente007.altura = 1.70 
    paciente007.alergia = "Manteiga de Amendoim" 
    paciente007.tiposanguineo = "O+" 
    paciente007.medicamento = "Dipirona" 
    paciente007.peso = 70.0 
    paciente007.dependentequimico = true 
        
    println("==========Ficha Médica==========")  
    
    println("nome"+ paciente007.nome) 
    println("idade"+ paciente007.idade) 
    println("altura"+ paciente007.altura) 
    println("peso "+ paciente007.peso) 
    println("alergia"+ paciente007.alergia) 
    println("Tipo Sanguineo"+ paciente007.tiposanguineo) 
    println("Dependente Químico?"+ paciente007.dependentequimico) 
    println("medicamento"+ paciente007.medicamento)         
}
   class Paciente(){ 
       
    var nome = ""
    var idade = 0
    var altura = 0.0 
    var alergia = "string"
    var tiposanguineo = "string"
    var medicamento = "string"
    var peso = 00.00
    var dependentequimico = true
    
   } 
 //-----------------------------------------------------------------------------------------------------------   
    
    
fun main() { 
    
  /*
    var jogador1 = JogadorDeFutebol("Neymar","PSG",10,"Brasileiro","Puma","Meio-Atacante",222.0 )
      
    println(jogador1.nome) 
    
// Exercício - Faça a escalação do seu time exibindo nome, número da camisa e posição 
// no minímo 11 jogadores.
  */
  var jogador = Time("Suga",1,"Goleiro") 
   println(jogador.nome)
   
  var jogador1 = Time("J",2,"Atacante") 
  println(jogador1.nome)
  
  var jogador2 = Time("V",3,"Meio-Atacante") 
  println(jogador2.nome)
  
  var jogador3 = Time ("Jin",4,"Volante")
  println(jogador3.nome)
  
  var jogador4 = Time ("Mick",5,"Centroavante")
  println(jogador4.nome)
  
  var jogador5 = Time ("Jack",6,"Goleiro Reserva")
  println(jogador5.nome)
  
  var jogador6 = Time("Farrokh",7,"Zagueiro")
  println(jogador6.nome)
  
  var jogador7 = Time("Bulsara",8," Lateral Direita")
  println(jogador7.nome)
  var jogador8 = Time("Brian",9,"Lateral Esquerda ")
  println(jogador8.nome)
  var jogador9 = Time("Taylor",10,"Meio-Armador")
  println(jogador9.nome)
  var jogador10 = Time("Adam",11,"Ponta")
  println(jogador10.nome)


  
  println(jogador.nome: )
  println(jogador.numero)
  
} 
/*
class JogadorDeFutebol(var nome: String,
                      var time: String,
                      var numero:Int,
                      var nacionalidade:String,
                      var patrociio:String,
                      var posicao:String,
                      var preco: Double){ 
 */  
    
   class Time(var nome: String, 
             var numero: Int,
             var posicao: String){ 
       
    //------------------------------------------------------------------------------------   
       
   }     
       
   fun main() { 
    /*
 println("----- Escalação Ninsys-----")   
 var jogador1 = Time("J",2,"Atacante") 
  println(jogador1.nome +"-" + jogador1.numero + "-" + jogador1.posicao) 
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~")

  
  var jogador2 = Time("V",3,"Meio-Atacante") 
  println(jogador2.nome)
  println(jogador2.numero)
  println(jogador2.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")

    
  var jogador3 = Time ("Jin",4,"Volante")
  println(jogador3.nome)
  println(jogador3.numero)
  println(jogador3.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")


  
  var jogador4 = Time ("Mick",5,"Centroavante")
  println(jogador4.nome)
  println(jogador4.numero)
  println(jogador4.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")

  
  var jogador5 = Time ("Jack",6,"Goleiro Reserva")
  println(jogador5.nome)
  println(jogador5.numero)
  println(jogador5.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")


  
  var jogador6 = Time("Farrokh",7,"Zagueiro")
  println(jogador6.nome)
  println(jogador6.numero) 
  println(jogador6.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")


 
  var jogador7 = Time("Bulsara",8," Lateral Direita")
  println(jogador7.nome)
  println(jogador7.numero)
  println(jogador7.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")

  
  var jogador8 = Time("Brian",9,"Lateral Esquerda ")
  println(jogador8.nome)
  println(jogador8.numero) 
  println(jogador8.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")

  
  var jogador9 = Time("Taylor",10,"Meio-Armador")
  println(jogador9.nome)  
  println(jogador9.numero) 
  println(jogador9.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")


  
  var jogador10 = Time("Adam",11,"Ponta")
  println(jogador10.nome) 
  println(jogador10.numero) 
  println(jogador10.posicao)
  println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~")
*/

    
    //Métodos/ Funções -> são um grupo de ações que representam uma determinada atividade de um 
    //determinado objeto. 
    //Estrutura de um método no Kotlin
    //
    //fun nomeDela (parametros -> se tiver){
    //ações 
    //}
    //
    //var nomeDoObjeto = ClassDeLe ()
    //nomeDoObjeto.nomeDela()
    
}
 
   class Time(var nome: String, 
             var numero: Int,
             var posicao: String){ 
   }
 
    //-----------------------------------------------------------------------------------------------------
       
       
   fun main() { 
 
    //Métodos/ Funções -> são um grupo de ações que representam uma determinada atividade de um 
    //determinado objeto. 
    //Estrutura de um método no Kotlin
    //
    //fun nomeDela (parametros -> se tiver){
    //ações 
    //}
    //
    //var nomeDoObjeto = ClassDeLe ()
    //nomeDoObjeto.nomeDela()
    
    val contaCorrente =  ContaBanco(1742537894002,0.5, "Rogers")
    contaCorrente.consultarSaldo()
    contaCorrente.Saque(0.3,2984)
    
    
    
    
}
 
   class ContaBanco(var num: Long, var saldo: Double, var dono: String){ 
        
      // Consultar saldo, saque e deposito
      // 
      
      fun consultarSaldo(){
       println("O saldo da sua conta é R$$saldo")   
      }    
        
      fun Saque(valor: Double, senha: Int){
          
          if(senha == 2984){
              if(saldo >= valor){
                  saldo -= // vai subtrair o valor do saldo 
                  println("Saque de R$$valor realizado com sucesso ")
              }else if(valor <= 0){
               println("Impossível sacar R$$valor  ") 
              }else{
                println("Saldo Insuficiente.")
              }            
      }else{
         println("senha INCORRETA!! Tente Novamente")           
          }
      
      }
    //--------------------------------------------------------------------------------------------------------------------------------    
       
       
       
       
       
    













    
        




    
      

   
    

    
    
    
    
      
    
   
   

}
        
