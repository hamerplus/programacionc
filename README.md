#include <stdio.h> 
int main(){
    int CodigoDeBarras, CodigoDelAlmacen;
    printf("ingrese el codigo de barras del producto (10 digitos alfanumericos):");
    scanf("%d",&CodigoDeBarras);
    printf("ingrese el codigo del almacen (debe empezar con'20' seguido de 3 digitos alfanumericos): ");
    scanf("%d",&CodigoDelAlmacen);

    if(CodigoDeBarras>=1000000000 && CodigoDeBarras>=9999999999){
	    if(CodigoDelAlmacen==8949899430||CodigoDelAlmacen==7653512593||CodigoDelAlmacen==9383867373||CodigoDelAlmacen==88392904209){
		printf("codigos validos.\n");
	    } else {
		printf("el codigo del almacen no es valido.\n");
		} 
	} else{
		printf("el codigo de barrras debe tener Exactamente 10 digitos alfanumericos.\n");
	}
	
	
	return 0;
}

