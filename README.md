# programacionc
#include <stdio.h>
int main(){
	int CodigoDeBarras, CodigoDelAlmacen;
	
	printf("ingrese el codigo de barras del producto (10 digitos alfanumericos):");
	scanf("%d",&CodigoDeBarras);
	printf("ingrese el codigo del almacen (debe empezar con'20' seguido de 3 digitos alfanumericos): ");
	scanf("%d",&CodigoDelAlmacen);
	int tamanocodigo= sizeof(CodigoDelAlmacen);
	if(tamanocodigo==10){
		if(CodigoDelAlmacen==8949899430||CodigoDelAlmacen==7653512593||CodigoDelAlmacen==9383867373||CodigoDelAlmacen==88392904209){
		}
	}
}
