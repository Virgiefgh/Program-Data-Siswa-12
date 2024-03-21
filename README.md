# Program-Data-Siswa-12
# include <stdio.h>
# include <conio.h>
# include <iostream.h>
main()
{

int nilai,ipa,ips,mtk,nilaiawal,pilihan;
char nama [200] ;
clrscr();

cout<<"Selamat Datang Di Aplkasi Penghitung Nilai Siswa :)\n";
pilihan=1;
while(pilihan == 1){

cout<<"Masukkan Nama Siswa : ";
cin>>nama;

cout<<"Masukkan Nilai IPA : ";
cin>>ipa;

cout<<"Masukkan Nilai IPS : ";
cin>>ips;

cout<<"Masukkan Nilai Matematika : ";
cin>>mtk;

nilaiawal=ipa+ips+mtk;
cout<<"-----------------------------\n";
cout<<"Total Nilai : "<<nilaiawal<<endl;
cout<<"-----------------------------\n";
nilai=nilaiawal/3;
cout<<"Rata-Rata Nilai : "<<nilai<<endl;

if (nilai>=75)
{
  cout<<"-----------------------------\n";
  cout<<"Nama Siswa : " <<nama<<endl;
  cout<<"Nilai Kamu Di Atas KKM ! \n";
  cout<<"-----------------------------";
}

else if (nilai<75)

{
 cout<<"-----------------------------\n";
 cout<<"Nama Siswa : " <<nama<<endl;
 cout<<"Nilai Kamu Di Bawah KKM ! \n";
 cout<<"----------------------------- \n ";

}

cout<<"Ingin Lanjut?\n";
cout<<"1. Ya \n";
cout<<"2. Tidak\n";
cin>>pilihan;


}

cout<<"Terima Kasih";
getch();


}
