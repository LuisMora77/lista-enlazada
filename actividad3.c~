#include <stdio.h>
#include <stdlib.h>
#include <string.h> 
#include "header.h"
 
   
    
int main()
{
printf("datoscargados%d",cargarDatos());
printf("los datos fueron cargados con exito, mostrando: %d",leerDatos());
    return 0;
    }

int cargarDartos(){
alien *lista;
lista=malloc(sizeof(alien));
strcpy(lista->nombre,"Esternolfo ");
lista->id = 777889;

lista->idiomas = malloc(sizeof(idiomas));
strcpy(lista->idiomas->nombre, "Reguliano");
strcpy(lista->idiomas->tipo, " normal");
lista->idiomas->simbolos = 1234567890;
lista->planetas=malloc(sizeof(planetas));
strcpy(lista->planetas->nombre,"Regulus");
lista->planetas->starwars_code=12245;
strcpy(lista->planetas->agua,"si");
strcpy(lista->planetas->oxigeno,"si");

return 0;
}

int leerDatos(){
printf("Nombre del primer alien es: %s",lista->nombre);
printf("\n\nEl id de %s es %d\n",lista->nombre,lista->id);
printf("\n\nEl alien %s con id %d habla un idioma llamado: %s\n",lista->nombre,lista->id,lista->idiomas->nombre);
printf("\n\nEl alien %s con id %d que habla %s habla un tipo %s de idioma ",lista->nombre,lista->id,lista->idiomas->nombre,lista->idiomas->tipo);
printf("\n\nEl alien %s con id %d que habla %s habla un tipo %s de idioma, el cual posee simbolos como: %d ",lista->nombre,lista->id,lista->idiomas->nombre,lista->idiomas->tipo,lista->idiomas->simbolos);
printf("\n\nEl planeta en el que vive %s se llama %s, posee el codigo %d,%s posee agua y %s posee oxigeno",lista->nombre,lista->planetas->nombre,lista->planetas->starwars_code,lista->planetas->agua,lista->planetas->oxigeno);
return 0;
}
	

