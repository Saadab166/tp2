# tp2
typedef struct Datel{
char jour[3];
char mois [3] ;
char annee[5];
}date;

typedef struct produit {
char *nom_produit ;
char reference [100]; 
float montant ;
date dateachat ;
}produit ;

typedef struct liste {
produit cellule ;
struct liste* psuiv ;
}liste ;

liste* cree_listepr(){
 return NULL;
}

int vide(liste*tete){
if(tete==NULL){
    return 1;
}
else{return0;}
}

liste *creer_produit(){
liste*nv_liste =(liste*)malloc(sizeof(liste));
printf("nom du produit :");
scanf("%s",nv_liste->nom_produt);
printf("reference du produit ");
scanf("%s",nv_liste->reference);
printf("montant du produit ");
scanf("%f",nv_liste->montant);
printf("date d'achat");
scanf("%s,%s,%s"nv_liste->dateachat->jour,nv_liste->dateachat->mois,nv_liste->dateachat->annee);
}

void afficher_produit (liste*produit ){
liste *ptr=debut ;
while(ptr!=NULL){
printf("%s->",produit->nom_produit )
printf("%s",nv_liste->reference);
printf("%s",nv_liste->reference);
printf("%f",nv_liste->montant);
printf("%s,%s,%s"nv_liste->dateachat->jour,nv_liste->dateachat->mois,nv_liste->dateachat->annee);

liste* ajouter_debut(liste*tete ){
liste*nv_p=(liste*)malloc(sizeof(liste));
nv_p->suiv=debut;
debut = nv-p;} 

liste * ajouter_fin(liste *tete)
{
liste*nv_p=(liste*)malloc(sizeof(liste));
liste*ptr=debut;
while(ptr->suiv !=NULL){
ptr=ptr->suiv;
}
ptr->suiv=null;
}


