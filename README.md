HEADER

**Struct
```cpp
void tampilProvinsi(Province &prov){
int total = prov.jumlahKabupaten + prov.jumlahKota;
    cout << "\nNama Provinsi: " << prov.nama << " (" << prov.ibuKota << ")\n";
    cout << "Daerah Terbesar adalah " << prov.terbesar 
         << " dari " << total << " Kota dan Kabupaten" << endl;
}
```
