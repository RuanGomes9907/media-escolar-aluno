programa {

  funcao inicio() {
    real a1, b1, c1, d1, a2, b2, c2, d2

    escreva ("Comparação entre a Media de 2 alunos\n")
    escreva ("ALUNO 1\n\n")


    escreva ("Nota P1: ")
    leia (a1)
    escreva ("Nota P2: ")
    leia (b1)
    escreva ("Nota P3: ")
    leia (c1)
    escreva ("Nota P4: ")
    leia (d1)
    escreva ("\n")
    escreva ("A Média do aluno 1 será: ", media_aluno1(a1, b1, c1, d1))

    escreva ("\n\n")
    escreva ("ALUNO 2\n\n")
    escreva ("Nota P1: ")
    leia (a2)
    escreva ("Nota P1: ")
    leia (b2)
    escreva ("Nota P1: ")
    leia (c2)
    escreva ("Nota P1: ")
    leia (d2)

    escreva ("A Média do aluno será: ", media_aluno2(a2, b2, c2, d2))
    escreva("\n\n")


    se (media_aluno1(a1, b1, c1, d1) >= 7) {
      escreva ("Aluno 1 APROVADO - Média Final: ", media_aluno1(a1, b1, c1, d1))
      escreva("\n")
    } senao {
     escreva ("Aluno 1 REPROVADO - Média Final: ", media_aluno1(a1, b1, c1, d1))
     escreva("\n")
     }

    se ( media_aluno2(a2, b2, c2, d2) >= 7) {
      escreva ("Aluno 2 APROVADO - Média Final: ",  media_aluno2(a2, b2, c2, d2))
      escreva("\n")
    } senao {
      escreva ("Aluno 2 REPROVADO - Média Final: ",  media_aluno2(a2, b2, c2, d2))
      escreva("\n")
      }


  }


  funcao real media_aluno1 (real a1, real b1, real c1, real d1){
    retorne (a1 + b1 + c1 + d1)/4

  }
  
  funcao real media_aluno2 (real a2, real b2, real c2, real d2){
    retorne (a2 + b2 + c2 + d2)/4

  }

}
