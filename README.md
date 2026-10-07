# kira-takip-data

Kira Takip uygulamasinin calisma zamaninda cektigi TUFE verisi (`cpi_tr.json`).
Kaynak: TUIK TUFE, EVDS TP.FG.J0 endeksinden hesaplanan "12 aylik ortalamalara gore degisim".

Guncelleme (ana repodan):

    EVDS_API_KEY=xxxx dart run tool/update_cpi.dart --out ../kira-takip-data/cpi_tr.json
    cd ../kira-takip-data && git commit -am "TUFE guncelle" && git push

Bu repo kasitli olarak public: uygulama anahtar olmadan okur. Icinde kisisel veri yoktur.
