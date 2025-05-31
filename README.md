# Sanggar-Krakatu
Sanggar Krakatu adalah wadah seni dan budaya yang berdedikasi untuk melestarikan, mengembangkan, dan memperkenalkan kekayaan seni tradisional Indonesia, khususnya seni tari dan musik daerah. Berdiri sejak tahun 2021, Sanggar Krakatu menjadi ruang berkumpulnya para seniman muda yang bersemangat dalam menjaga warisan budaya leluhur.
#include <iostream>
using namespace std;

int main() {
    double angka1, angka2;
    char operasi;

    cout << "=== Kalkulator Sederhana ===" << endl;
    cout << "Masukkan angka pertama: ";
    cin >> angka1;
    cout << "Masukkan operasi (+, -, *, /): ";
    cin >> operasi;
    cout << "Masukkan angka kedua: ";
    cin >> angka2;

    cout << "Hasil: ";
    switch (operasi) {
        case '+':
            cout << angka1 + angka2;
            break;
        case '-':
            cout << angka1 - angka2;
            break;
        case '*':
            cout << angka1 * angka2;
            break;
        case '/':
            if (angka2 != 0)
                cout << angka1 / angka2;
            else
                cout << "Error: Pembagian dengan nol!";
            break;
        default:
            cout << "Operasi tidak valid!";
    }

    cout << endl;
    return 0;
}
