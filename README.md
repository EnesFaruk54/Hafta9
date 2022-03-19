# Hafta9
Hafta 9 Ödevim



#include <iostream>
using namespace std;
class Nokta{
    int x,y;
    public:
    void git(int, int);
    void goster();
    void sifir_mi();
};
void Nokta::git(int yeni_x, int yeni_y)
{
    x = yeni_x;
    y = yeni_y;
}
void Nokta::goster()
{
    cout << "X noktasi: " << x << ", Y noktasi: " << y << endl;
}
void Nokta::sifir_mi()
{
    if ((x == 0) && (y == 0))
        cout << "n1 su anda sifir noktasindadir." << endl;
    else
        cout << "n1 su anda sifir noktasinda degildir." << endl;
}
int main() {
    Nokta n1,n2;
    n1.git(78,34);
    n1.goster();
    n1.git(61,35);
    n1.goster();
    n1.sifir_mi();
    n2.git(0,0);
    n2.sifir_mi();
    return 0;
}
  
  
  
  
  
  
  
  
  
  
 #include <iostream>
 #include <string>
using namespace std;
class Basketbolcu
{
public:
	string ad_soyad;
	int forma_no;
	int basket_sayisi;
	
	Basketbolcu(string x_ad_soyad, int x_forma_no, int x_basket_sayisi){
    	ad_soyad = x_ad_soyad;
    	forma_no = x_forma_no;
    	basket_sayisi = x_basket_sayisi;
	}
};
int main()
{
	Basketbolcu b1("Enes", 5 , 21);
	Basketbolcu b2("Faruk", 9, 15);
	cout << b1.ad_soyad << " " << b1.forma_no << " " << b1.basket_sayisi << "\n";
	cout << b2.ad_soyad << " " << b2.forma_no << " " << b2.basket_sayisi << "\n";
	return 0;
}
