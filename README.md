# program-mencari-keliling-luas-dan-Volume-tabung

#include <iostream>

using namespace std;

int main()
{
    /*soal 5 */
  
    const float phi=3.14;
    float luas_alas, keliling_alas, volume,jari_jari, tinggi;
    jari_jari=10;
    tinggi=10;
    keliling_alas=2*phi*jari_jari;
    luas_alas=phi*jari_jari*jari_jari;
    volume=luas_alas*tinggi;
    cout << "program mencari keliling, luas dan Volume tabung" << endl;
    cout << "================================================" << endl;
    cout << "keliling alas" <<keliling_alas<< endl;
    cout << "luas alas" <<luas_alas<< endl;
    cout << "volume=" << volume<< endl;
    return 0;
}
