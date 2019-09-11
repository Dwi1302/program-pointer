#include <iostream>
using namespace std;

void tambah (int *angka) {
*angka +=44;
}
void kurang (int *angka) {
*angka -=80;
}

int main () {
int nilai = 97;
cout<<""<<nilai<<dec;
tambah(&nilai); //menentukan alamat variabel nilai pada fungsi tambah
cout<<"="<<nilai<<dec;
kurang(&nilai);
cout<<"="<<nilai<<dec;
int biner = 1100001;
cout<<"="<<biner<<dec;

return 0;
}
