# zadaca-2
#include <iostream>
namespace std;
int main () {

int mjesec;
cout<< "Unesi brojeve od 1-12";
cin>> mjesec;
if (mjesec > 0 && mjesec < 13)
{
if(mjesec == 1 || mjesec == 2)
{
cout<< "Godisnje doba kojem mjesec pripada je zima.";
} else if (mjesec == 3)
{
cout<< "Kraj zime, a pocetak proljeca je: 20.03"
} else if (mjesec == 4) (mjesec == 5)
{
cout<< "Godisnje doba kojem mjesec pripada je Proljece.";
} else if (mjesec == 6) {
cout<< "Kraj proljeca a pocetak ljeta je 21.06.";
} else if (mjesec == 7 || mjesec == 8) {
cout<< "Godisnje doba kojem mjesec pripada je ljeto.";
} else if(mjesec == 10 || mjesec == 11) {
cout<< "Godisnje doba kojem mjesec pripada jejesen.";
} else if (mjesec == 12) {
cout<< "Kraj jeseni, a pocetak zimeje: 21.12.";
}

} else {
cout<< "Niste unijeli odgovarajuci broj";
}

return 0;
}



#include <iostream>
namespace std;
int main ()

int mjesec = 9;
int godina = 2021;
int mjesecRodjenja, godinaRodjenja;
cout<< "Unesite godinu i mjesec rodjenja.";
cin>> godinaRodjenja >> mjesec Rodjenja;
if (mjesec-mjesecRodjenja == 0) {
cout<< "Imate" << godina-godinaRodjenja << "godina.";
} else if (mjesec-mjesecRodjenja>0) {
cout<< "Imate"<< godina-godinaRodjenja<< "godina i" << mjesec-mjesecRodjenja<< "mjeseci.";
} else {
cout<< "Imate"<<godina-godinarodjenja-1<< "godina i"<< mjesecRodjenja<<"mjeseci.";
return 0;
}



#include <iostream>
namespace std;
int main ()

int a;
cout<< "Unesi neki broj";
cin>> a;
if (a%3 == 0 && a%5 == 0) {
cout<< "Broj<< a << "je djeljiv i sa 3 i 5";
else if
}
else if ( a%3 == 0)
{
cout<< "Broj" << a << " je djeljiv samo sa 3";
else if (a%5 == 0)
{
cout<< "Broj" << a << " je djeljiv samo sa 5";
}
return 0;
}
