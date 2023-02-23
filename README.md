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
    
    
    
    
      
    
   
   

}
        
