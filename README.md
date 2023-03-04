# Programas-em-C
Código que fiz para minha namorada quanto precisa para passar



    #include <stdio.h>

     int main(void)  {

     float x1, x2, resultado, x3;

      printf("\n\t\t--Calculadora para saber quantos pontos precisa para passar no 3 "
            "trimestre.--\n");
      printf("\n\t\t--Basta colocar as suas notas do 1 e 2 trimestre e ver quanto "
            "precisa para o último.--\n");

      printf("\n\nDigite sua primeira nota (ex: 6.8): ");
              scanf("%f", &x1);

      printf("Digite sua segunda nota (ex: 5.9): ");
              scanf("%f", &x2);

      resultado = 60 - 3 * x1 - 3 * x2;

      x3 = resultado / 4;

      if (x3 >= 6)
          printf("\nVocê precisa de >> %.2f << para passar!", x3);

       if (x3 < 6)
           printf("\nVocê precisa de >> %.2f << já passou!! Só estudar mais um pouco "
              "pra confirmar!",
                x3);
       }
  
