principal()
{
      entera opcion; //Variable y la estoy declarando"
      en pantalla ("1. Tortillas");
      en pantalla ("2. Manzanas");
      en pantalla ("3. Refresco");
      en pantalla ("4. Garrafón de agua");
      en pantalla ("5. Verdura");
     ("%i", &opcion); capturarespuesta//La "i" es para indicar que esperas un número//

    caso (opcion)
   {
       caso 1:
            enpantalla ("el Kg de tortilla vale $21");
            rompe;
        caso 2:
            enpantalla ("el Kg de manzana vale $50");
            rompe;
        caso 3:
            enpantalla ("el refresco de litro $18");
            rompe;
        caso 4:
            enpantalla ("el garrafón de 20lt vale $40");
            rompe;
        caso 5:
            enpantalla ("el Kg de verdura mixta vale $30");
            rompe;
   } 
   enpantalla ("Gracias por usar mi menu");
}
