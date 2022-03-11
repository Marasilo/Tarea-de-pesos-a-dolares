# Tarea-de-pesos-a-dolares
para el profe
#include <stdio.h>

int main(void) {
  int Pesos;
  int Dolares;
  printf("Ingrese el valor en pesos: ");
  scanf("%d" , &Pesos);
  printf("Ingrese el valor en dolares: ");
  scanf("%d" , &Dolares); 
  Dolares = (Dolares * 58);
  if (Pesos >= Dolares)
  {
    printf("Cantidad en pesos: %d", Pesos);
  }  
  else
  {
    printf("Cantidad de Dolares en pesos: %d" , Dolares);
  }

  return 0;
}
