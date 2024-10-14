#include <iostream>
using namespace std;

int main() {
    int jumlahData, angka;
    int jumlahGenap = 0, jumlahGanjil = 0;

    cout << "Masukkan jumlah data: ";
    cin >> jumlahData;

    for (int i = 0; i < jumlahData; i++) {
        cout << "Masukkan angka ke-" << (i + 1) << ": ";
        cin >> angka;

        if (angka % 2 == 0) {
            jumlahGenap += angka;
        }
        else {
            jumlahGanjil += angka;
        }
    }

    cout << "Jumlah total bilangan ganjil: " << jumlahGanjil << endl;
    cout << "Jumlah total bilangan genap: " << jumlahGenap << endl;

    return 0;
}
