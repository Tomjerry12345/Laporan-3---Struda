#include <iostream>
#include<windows.h>
#include <string.h>

using namespace std;

struct barang {
	int ultraMilk;
	int tehKotak;
	int aqua;
	int tehGelas;
	int aleAle;
	
}; struct barang *jumlah , *harga  , jumlah_barang , harga_barang;
int jumlah1 , pil , total[100];
string jenis[100];
int counter = -1 , j;

void clrscr(){
 system("cls");
}

void jumlahBarang()
{

	jumlah_barang.ultraMilk = 5;
	jumlah_barang.tehKotak = 5;
	jumlah_barang.aqua = 5;
	jumlah_barang.tehGelas = 5;
	jumlah_barang.aleAle = 5;
	
	harga_barang.ultraMilk = 6000;
	harga_barang.tehKotak = 4000;
	harga_barang.aqua = 3500;
	harga_barang.tehGelas = 1000;
	harga_barang.aleAle = 1000;
	
}

void tampil()
{
	if (counter == -1)
	{
		cout << "Data Belum Ada\n\n";
	} else {
		
		for (int a = counter;a >= 0;a--)
		  	 {
		  	 	cout << "Barang " << j << endl;
		  	 	cout << "total : " << total[a]<< endl;
		  	 	cout << "jenis barang : " << jenis[a] << endl;
		  	 	j++;
		  	 	
			 }
			 cout << endl;
		
	}
	
}


int main()
{
	int stokUltra;
	jumlah = &jumlah_barang;
	harga = &harga_barang;
	jumlahBarang();
	stokUltra = jumlah->ultraMilk;
		 do{
		 	
		  	j = 1;
		  	cout << "counter = " << counter << endl;
		  	cout << endl;
		 	 
			 cout << "1.Ultramilk " << "jumlah : " << jumlah->ultraMilk << "\n"
			 << "2.Teh Kotak " << "jumlah : " <<  jumlah->tehKotak << "\n"
			 << "3.Aqua " << "jumlah : " << jumlah->aqua << "\n"
			 << "4.Teh Gelas " << "jumlah : " << jumlah->tehGelas << "\n"
			 << "5.Ale-Ale " << "jumlah : " << jumlah->aleAle << "\n\n";
			 tampil();
			
			 cout << "Input Pilihan : ";
			 cin>>pil;
			 counter++;
		  	 if(pil==1){
			 	cout << "Input jumlah Barang : ";
				cin >> jumlah1;
				if (jumlah->ultraMilk < 0)
				{
					cout << "Stok Ultramilk sudah habis";
					
				} else {
					total[counter] = harga->ultraMilk * jumlah1;
			 		jenis[counter] = "ultramilk";
			 		jumlah->ultraMilk = jumlah->ultraMilk - jumlah1;
					
				}
			 	
			  
			 }
			 
			 
			 
		  	clrscr(); 
		 }while (pil!=6);
		 return 0;
	
	
	
	
}
