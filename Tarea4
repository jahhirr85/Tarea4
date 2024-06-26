#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
using namespace std;
int main(int argc, char** argv) {
	int datos2[3];
	string datos[3];
	char opcion, nombre, apellido;
	int tipo = 0, x=0, i=0;
	int horas = 0;
	int precio = 0;
	int OP=0;
	int TC=0;
	int PR=0;
	int salario;
	int aumento=0;
	int bruto=0;
	int ccss=0;
	int neto=0;
	int acumuladoOP=0;
	int acumuladoTC=0;
	int acumuladoPR=0;
	int promedioOP=0;
	int promedioTC=0;
	int promedioPR=0;
	do {
		/*system("cls");
		printf("Digite el numero de cedula: ");
		scanf("%i",&cedula);
		printf("\nDigite el nombre del empleado: ");
		scanf("%s", nombre);
		printf("\nDigite el apellido del empleado: ");
		scanf("%s", apellido);
		printf("\nDigite el numero de empleado segun la siguiente tabla:\n 1- Operario\n 2- Tecnico\n 3- Profesional\n Tipo seleccionado: ");
		scanf("%i", &tipo);
		printf("Digite la cantidad de horas laboradas: ");
		scanf("%i", &horas);
		printf("Digite el precio por hora laborada: ");
		scanf("%i", &precio);
		salario = precio * horas;*/
		system("cls");
		x=0;
		i=0;
		cout << "Digite el numero de cedula: " <<endl;
		cin >> datos[x];
		x++;
		cout <<"Digite el nombre del empleado: "<<endl;
		cin >> datos[x];
		x++;
		cout <<"Digite el apellido del empleado: "<<endl;
		cin >> datos[x];

		cout << "\nDigite el numero de empleado segun la siguiente tabla:\n 1- Operario\n 2- Tecnico\n 3- Profesional\n Tipo seleccionado: "<<endl;
		cin >> datos2[i];
		i++;
		cout << "Digite la cantidad de horas laboradas: "<<endl;
		cin >> datos2[i];
		i++;
		cout <<"Digite el precio por hora laborada: "<<endl;
		cin >> datos2[i];
		salario = datos2[1] * datos2[2];
					
			
		if (datos2[0]==1) {
			OP++;
			aumento=salario*0.15;
			bruto=salario+aumento;
			ccss=bruto*0.0917;
			neto=bruto-ccss;
			acumuladoOP=neto+acumuladoOP;
			promedioOP=acumuladoOP/OP;
		}else  if(datos2[0]==2) {
			TC++;
			aumento=salario*0.10;
			bruto=salario+aumento;
			ccss=bruto*0.0917;
			neto=bruto-ccss;
			acumuladoTC=neto+acumuladoTC;
			promedioTC=acumuladoTC/TC;	
		}else {
			PR++;
			aumento=salario*0.05;
			bruto=salario+aumento;
			ccss=bruto*0.0917;
			neto=bruto-ccss;
			acumuladoPR=neto+acumuladoPR;
			promedioPR=acumuladoPR/PR;
		}
		system("cls");
		cout <<"**********Resumen del empleado****************" << endl;
		cout << "Cedula:			" << datos[0]<<endl;
		cout<<"Nombre del empleado: 	" << datos[1];
		cout<<" " << datos[2];
		if (datos2[0]==1) {
			cout <<"\nTipo de empleado:	Operario";
		}else if(datos2[0]==2){
			cout <<"\nTipo de empleado:	Tecnico";
		}else {
			cout << "\nTipo de empleado:	Profesional";
		}
		cout<<"\nSalario por hora: 	"<<datos2[2];
		cout<<"\nCantidad de horas: 	"<<datos2[1];
		cout<<"\nSalario Ordinario: 	" << salario;
		cout<<"\nAumento: 		"<< aumento;
		cout<<"\nSalario Bruto: 		"<< bruto;
		cout<<"\nDeduccion CCSS: 	"<< ccss;
		cout<<"\nSalario Neto: 		"<< neto;
		cout<<"\n";
		cout<<"\nDesea ingresar otro empleado: ";
		
		opcion= getch();
		
	}while (opcion == 's');
	system("cls");
	cout<<"*****************ESTADISTICAS*********************";
	cout<<"\nCantidad Empleados Tipo Operarios:		"<< OP;
	cout<<"\nAcumulado Salario Neto Operarios:		"<< acumuladoOP;
	cout<<"\nPromedio Salario Neto para Operarios:		"<< promedioOP;
	cout<<"\nCantidad Empleados Tipo Tecnico:		"<< TC;
	cout<<"\nAcumulado Salario Neto Tecnico:			"<< acumuladoTC;
	cout<<"\nPromedio Salario Neto para Tecnico:		"<< promedioTC;
	cout<<"\nCantidad Empleados Tipo Profesionales:		"<< PR;
	cout<<"\nAcumulado Salario Neto Profesional:		"<< acumuladoPR;
	cout<<"\nPromedio Salario Neto para Profesional:		"<< promedioPR;
	
	return 0;
}
