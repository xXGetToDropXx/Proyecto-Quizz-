#include "iostream"
#include "windows.h"
#include "conio.h"
using namespace std;
int main()
{
char r;
int a=0, rep, opcion; 

system("color F0");
Sleep(500);
	cout<<"  ___ _   _  ___  ___| |_(_) ___  _ __   __ _ _ __(_) ___"<<endl; 
	Sleep(500);
	cout<<" / __| | | |/ _ \\/ __| __| |/ _ \\| '_ \\ / _` | '__| |/ _ \\"<<endl;
	Sleep(500);
	cout<<"| (__| |_| |  __/\\__ \\ |_| | (_) | | | | (_| | |  | | (_)|"<<endl;
	Sleep(500);
	cout<<" \\___|\\__,_|\\___||___/\\__|_|v\___/|_| |_|\\__,_|_|  |_|\\___/"<<endl<<endl;

do
{
cout<<endl<<"1.CULTURA GENERAL "<<endl;
cout<<"2. MATEMÁTICAS"<<endl;
cout<<"3. SERIES"<<endl;
cout<<"ELIGE UN TEMA DE LOS TRES: ";
cin>>opcion; 

switch(opcion)
{
case 1:
system("color F0");
getch();
system("cls");
a=0;
cout<<endl<<"Cultura GENERAL "<<endl;
cout<<endl<<"1.¿En qué a año llegó el hombre a la Luna? "<<endl;
cout<<"a)1969"<<endl;
cout<<"b)1978"<<endl;
cout<<"c)1949"<<endl;
cin>>r;
if(r=='a')
{
system("color 15");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"2.¿Cómo se conocía la primera guerra mundial? "<<endl;
cout<<"a)La Gran Guerra "<<endl;
cout<<"b)La Guerra Mundial "<<endl;
cout<<"c)Ninguna de las anteriores "<<endl;
cin>>r;
if(r=='a')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls"); 

cout<<endl<<"3.¿Qué país está entre Perú y Colombia? "<<endl;
cout<<"a) México "<<endl;
cout<<"b) Venezuela "<<endl;
cout<<"c) Ecuador "<<endl;
cin>>r;
if(r=='c')
{
system("color 15");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"4.¿Quién escribió las aventuras de sandokan? "<<endl;
cout<<"a) Jorge Luis Borges"<<endl;
cout<<"b) Emilio Salgari "<<endl;
cout<<"c) Silvina Ocampo"<<endl;
cin>>r;
if(r=='c')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"5.¿Quién es el precedente actual en México? "<<endl;
cout<<"a)Amlo"<<endl;
cout<<"b)Peña Nieto"<<endl;
cout<<"c)Ninguna de las Anteriores "<<endl;
cin>>r;
if(r=='a')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}

getch();
system("cls");
cout<<endl<<"6.¿Quién es el artista de música latino más grande sin palabras obscenas? "<<endl;
cout<<"a)Duki"<<endl;
cout<<"b)Paulo Londra "<<endl;
cout<<"c)Lit Killah"<<endl;
cin>>r;
if(r=='b')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"7.¿Quién es el actor #1 de la televisión humuristica? "<<endl;
cout<<"a)Cantiflas "<<endl;
cout<<"b)Roberto Gomez"<<endl;
cout<<"c)Pedro Infante"<<endl;
cin>>r;
if(r=='b')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"8.¿Qué es lo que come más el mexicano? "<<endl;
cout<<"a) Chile"<<endl;
cout<<"b) Tortilla"<<endl;
cout<<"c) Las 2 anteriores"<<endl;
cin>>r;
if(r=='c')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"9.¿Cómo se le dice el aguacate?"<<endl;
cout<<"a)Aguacate "<<endl;
cout<<"b)Palta"<<endl;
cout<<"c)Depende de la Región "<<endl;
cin>>r;
if(r=='c')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
getch();
system("cls");
cout<<endl<<"10. ¿Cual es la mejor preparatoria de México? "<<endl;
cout<<"a)Conalep "<<endl;
cout<<"b)Itace"<<endl;
cout<<"c)Atlantico"<<endl;
cin>>r;
if(r=='c')
{
system("color 30");
cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl; 

a=a+10;
}
else
{
system("color C0");
cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
}
 
cout<<"Los puntos obtenidos son: "<<a<<endl;
break;

	
	case 2:
	a=0;

system("color F0");
	getch();
	system("cls");
	a=0;
	cout<<endl<<"MATEMÁTICAS"<<endl;
	cout<<endl<<"1.¿Cuánto es 7 + 2?"<<endl;
	cout<<"a)11"<<endl;
	cout<<"b) 9"<<endl;
	cout<<"c)12"<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 15");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	a=a+10;
	}
	else 
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"2.¿Cuánto es 25 + 25?"<<endl;
	cout<<"a)64"<<endl;
	cout<<"b)50"<<endl;
	cout<<"c)60"<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");

	cout<<endl<<"3.¿Cuánto es 30 + 30?"<<endl;
	cout<<"a)60"<<endl;
	cout<<"b)95"<<endl;
	cout<<"c)50"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 15");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"4.¿Cuánto es 150 + 100?"<<endl;
	cout<<"a)300"<<endl;
	cout<<"b)250"<<endl;
	cout<<"c)355"<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"5.¿Cuánto es 10 - 5?"<<endl;
	cout<<"a) 5"<<endl;
	cout<<"b) 0"<<endl;
	cout<<"c)15"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	
	
	
	getch();
	system("cls");
	cout<<endl<<"6.¿Cuánto es 3 * 3?"<<endl;
	cout<<"a)10"<<endl;
	cout<<"b)12"<<endl;
	cout<<"c) 9"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"7.¿Cuánto es 5 * 5?"<<endl;
	cout<<"a)30"<<endl;
	cout<<"b)15"<<endl;
	cout<<"c)25"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"8.¿Cuanto es 10 * 5?"<<endl;
	cout<<"a)25"<<endl;
	cout<<"b)50"<<endl;
	cout<<"c)80"<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"9.¿Cuánto es 100 - 75?"<<endl;
	cout<<"a)40"<<endl;
	cout<<"b)13"<<endl;
	cout<<"c)25"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"10.¿Cuánto es 150 / 50?"<<endl;
	cout<<"a) 3"<<endl;
	cout<<"b)70"<<endl;
	cout<<"c) 7"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	
	
	cout<<"Los puntos obtenidos son: "<<a<<endl;
	break;
	
	

case 3:
	
	system("color F0");
	getch();
	system("cls");
	a=0;
	cout<<endl<<"SERIES"<<endl;
	cout<<endl<<"1. ¿Cuál de estos no es un el título de un capítulo de Black Mirror?"<<endl;
	cout<<"a)Shut up and dance "<<endl;
	cout<<"b) Broken Crystal"<<endl;
	cout<<"c) White Bear"<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 15");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"2.¿Qué organización dirige Claire Underwood en la primera temporada de la serie house of cards?"<<endl;
	cout<<"a) Saving the artic"<<endl;
	cout<<"b) Clean water initiative"<<endl;
	cout<<"c) Saving clean water"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");

	cout<<endl<<"3. ¿Qué serie original de netflix protagoniza Miguel Ángel Silvestre? "<<endl;
	cout<<"a) Narcos"<<endl;
	cout<<"b) Las chicas del cable"<<endl;
	cout<<"c) Sense8"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 15");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"4. ¿Quiénes son los creadores de Stranger Things?"<<endl;
	cout<<"a) Hermanas Wachowski."<<endl;
	cout<<"b) Hermanos Duffer."<<endl;
	cout<<"c) Chris Chibnall y Louise Fox."<<endl;
	cin>>r;
	if(r=='b')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"5. ¿Quién fue el amor de la infancia de Alba en las chicas del cable?"<<endl;
	cout<<"a) Carlos"<<endl;
	cout<<"b) Juan"<<endl;
	cout<<"c) Francisco"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	
	
	
	getch();
	system("cls");
	cout<<endl<<"6. ¿En la historia de quien está basada la serie Orange is the new black?"<<endl;
	cout<<"a) Piper kerman"<<endl;
	cout<<"b) Piper chapman"<<endl;
	cout<<"c) En la de ninguna, es totalmente original"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"7. ¿A que se dedica la madre clay en 13 reasons why?"<<endl;
	cout<<"a) Profesora"<<endl;
	cout<<"b) Periodista"<<endl;
	cout<<"c) Abogada"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
	getch();
	system("cls");
	cout<<endl<<"8. ¿Qué número de cinta es jessica davis en 13 reasons why?"<<endl;
	cout<<"a) Numero 2"<<endl;
	cout<<"b) Numero 3"<<endl;
	cout<<"c) Numero 8"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"9. ¿Cómo se llamó la mansión donde encarcelaron a Escobar en Narcos?"<<endl;
	cout<<"a) La catedral"<<endl;
	cout<<"b) El palacio"<<endl;
	cout<<"c) Notenia nombre"<<endl;
	cin>>r;
	if(r=='a')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	}
		getch();
	system("cls");
	cout<<endl<<"10. ¿que serie acaba de terminar de grabar su tercera temporada?"<<endl;
	cout<<"a) Vis a Vis"<<endl;
	cout<<"b) Paquita Salas"<<endl;
	cout<<"c) Las chicas del cable"<<endl;
	cin>>r;
	if(r=='c')
	{
	system("color 30");
	cout<<" ####   ####  #####  #####  ######  ####  #####  ####"<<endl;
	cout<<"#    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"#      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"#      #    # #####  #####  #      #        #   #    #" <<endl;
	cout<<"#    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<" ####   ####  #    # #    # ######  ####    #    ####  "<<endl;

	a=a+10;
	}
	else
	{
	system("color C0");
	cout<<"# #    #  ####   ####  #####  #####  ######  ####  #####  #### "<<endl;
	cout<<"# ##   # #    # #    # #    # #    # #      #    #   #   #    # "<<endl;
	cout<<"# # #  # #      #    # #    # #    # #####  #        #   #    # "<<endl;
	cout<<"# #  # # #      #    # #####  #####  #      #        #   #    # "<<endl;
	cout<<"# #   ## #    # #    # #   #  #   #  #      #    #   #   #    # "<<endl;
	cout<<"# #    #  ####   ####  #    # #    # ######  ####    #    ####  "<<endl;
	
	}
	
	
	cout<<"Los puntos obtenidos son: "<<a<<endl;
	break;
	}
	cout<<endl<<"Elige 1 para regresar al menu de opciones 2 para salir ";
	cin>>rep;
	}while(rep==1);
	   cout<<"###### # #    # "<<endl;
       cout<<"#      # ##   # "<<endl;
       cout<<"#####  # # #  # "<<endl;
       cout<<"#      # #  # # "<<endl;
       cout<<"#      # #   ## "<<endl;
       cout<<"#      # #    # "<<endl;
getch();
return 0;
}
