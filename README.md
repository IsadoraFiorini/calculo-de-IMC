real peso, altura, IMC
    escreva("Digite seu peso: ")
     leia(peso)
      
    escreva("Digite sua altura: ")
    leia(altura)

    IMC= peso/(altura*altura)

    se (IMC<= 18.5){
      escreva("peso baixo!")
      escreva("seu imc é", IMC)
    }
    
    senao se (IMC <= 24.9){
      escreva("Peso normal!")
      escreva("seu imc  é:", IMC)
    }
    
    senao se(IMC <= 29.9){
      escreva("Sobre peso!")
      escreva("seu imc é:", IMC)
    }
    senao se(IMC <= 34.9){
      escreva("Obesidade (grau 1)")
      escreva(" seu imc é:", IMC )
    }
     
     senao se (IMC <= 39.9){
      escreva("Obesidade severa!!!")
      escreva("Seu imc é:",IMC)
     }


     senao se (IMC >= 40.0){
      escreva("Obesidade  Mórbida!!!")
      escreva("seu IMC é:", IMC)
     }
