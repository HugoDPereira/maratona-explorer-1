# HTML
  - HyperText Markup Language

  - HiperTexto ?
    É uma linguagem de marcação para computadores/servidores da web sendo o estilo e a estrutura de um documento.

  - Marcação
    - tags
    - atributos

  - Linguagem
    - maneira de escrever

# CSS
  - Cascading Style Sheets (Folha de Estilo em Cascata)
  - Apresentação visual para o cliente
  - Estilos para o HTML
  
  - Declaração
    - Seletor
    - Propriedade e Valor

  - Conceitos
    - Cascata
    - Especificidade
    - Box Model
    - Display block vs inline


# JavaScript

  - Variáveis
    - let estaChovendo = true
    - const meuNome = "Hugo"


  - Tipos de Dados 
    - String
    - ""
    - ''
  
  - Number
  - 12 - Integer (+ -)
  - 3.2 - Float (+ - )

  - Boolean
  - true ou false
  - const maiorDeDezoito = false

  - undefined - indefinido


  - Operadores
    - Atribuição (ex: =)
    - atribui valor
    - let n1 = 12
    - let n2 = 3 

    - Aritméticos (ex: * / + - )
    - calculos matemáticos simples

    - Concatenação de String (+)

    - Comparação (ex: > < == )
    - transforma a expressão em true ou false
    - const maiorQue = 1 > 2 // false
    - const igualA = 1 == 1 // true

  - Condicional (if/else)
    - const idade = 18
    - const maiorDeDezoito = idade >= 18 

    - if(maiorDeDezoito) {
    -   alert("Pode tirar carteira de motorista")
    - } else {
    -   alert("Não pode tirar")
    - }

  - Estrutura de dados
    - Array - Vetor - Lista
    - Array -----             0    1   2   3
    - const temperaturas = [23.3, 32.2, 1, 5]

    - Object
    - const pessoa = {
    -   nome: "Hugo",
    -   idade: 25,
    -   filhos: ["J", "L", "B", "H", "Y"]
    - }
    - console.log(pessoa.filhos[3])

  - Function
    - 1. Criação 
    - function nomeDaFuncao() {
    -   console.log('código da função')
    - }

    - 2. Execução
    - nomeDaFuncao()


    - Parâmetros
    - function soma(a, b) {
    -   console.log(a + b)
    - }
    - soma(34, 45)
    - soma(90, 54)

    - Retorno
    - function soma(a, b) {
    -   return a + b
    - }

    - const multiplica = soma(2, 2) * 4
    - console.log(multiplica)

    - console.log(soma(2, 2))


  - Extensões da linguagem (ex.: Math, Date ...)
    - Math.random()
    - Math.floor(1.2)
    - Math.ceil(1.2)

  - DOM - Document Object Model 
    - window
    - window.alert("alerta")
    - document
    - document.write("texto")
    - manipular elementos
    - document.documentElement.style.background = "black"
  ```
