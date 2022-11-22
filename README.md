# Portugol (SOMA_INTERVALO)
programa {
  funcao inicio() {
    inteiro x, y
    
escreva("Digite os números para executar a soma do intervalor ")
leia(x)
leia(y)

escreva(soma_intervalo(x,y))
  }

  funcao inteiro soma_intervado(inteiro x, inteiro y){
    inteiro total, resultado_parcial
    total = y/2
    resultado_parcial = y+x

    inteiro resultado = total * resultado_parcial
    retorne resultado
      }
