#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include "fonction.h"
#include "structures.h"

//CETTE FONCTION PERMET D'OBTENIR L'ETAT D'UNE VOITURE DE NOTRE PARC
void etat_voiture()
{
    int i,test;
    char matriculesaisi[20];//IL S'AGIT DU MATRICULE SAISI PAR L'UTLISATEUR

    printf("\nVeillez entrer le matricule de la voiture que vous desirez connaitre l'etat: ");
    scanf("%s",matriculesaisi);
    printf("\n\n");

    for(i=0;i<10;i++)
    {
         test=strcmpi(matriculesaisi,voiture[i].matricule);

               if(test==0)
                {
                    printf("\n                Les informations de la Voiture: \n\n");
                    printf("\n                Modele: %s\n",voiture[i].modele);
                    printf("\n                Matricule: %s\n",voiture[i].matricule);
                    printf("\n                Kilometrage: %d Km\n",voiture[i].kilometrage);
                    printf("\n                Etat : %s\n",voiture[i].etat);
                    break;

                }
    }

    for(i=0;i<10;i++)
    {
        if(test!=0)
           printf("\nDesoler cette voiture n'existe pas,reesayez avec un matricule correct \n\n");
           break;
    }
    retour_au_menu();

}





