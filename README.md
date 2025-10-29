# javascript-fixac-o-2
Exercício de fixação para função gernérica em TypeScript
EXERCÍCIO PRÁTICO RÁPIDO PARA FUNÇÃO GENÉRICA EM TYPESCRIPT
Diego de Araújo Veras
27/10/2025

Complete o código abaixo: 
typescript 

// 1. Crie um tipo literal para cor com: "vermelho", "azul", "verde" 
type Cor = “vermelho”__”azul”  “ verde”; 

// 2. Crie um tipo Carro com: 
// - marca (string, readonly) 
// - modelo (string)  
// - cor (do tipo Cor acima) 
// - ano? (opcional, number) 

type Carro = { 
readonly marca : “Ford” ;
readonly modelo: “Scort” ;
cor: “azul” ;
ano? 1988 ;
}; 
// 3. Crie uma função Generic que retorne o primeiro elemento de um array 
function primeiro<T>(array:  T [ ] ):  T  { 
return  array [0]; 
}

