# ServicesSPPKS
Web services SPPKS menggunakan Yii Framework berbasis REST

Web services ini dipakai untuk aplikasi Android [SPPKS](https://github.com/handita/SPPKS)

Service yang dipakai di `ApiController.php`

Data yang dipakai adalah sql server dengan database di dalam file SPPKS2015.rar

Data yang dikeluarkan dalam bentuk `json` diantaranya ada data `prov`,`kab`,`kec`,`desa`,`bs`,`mnusrt`,`petugas` 

Service url menggunakan

    POST Ke
    `/api/mnusrt`
    data : token,kode_petugas

