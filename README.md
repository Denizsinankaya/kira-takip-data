# kira-takip-data

Kira Takip uygulamasinin calisma zamaninda cektigi TUFE verisi (`cpi_tr.json`).
Kaynak: TUIK TUFE, EVDS TP.FG.J0 endeksinden hesaplanan "12 aylik ortalamalara gore degisim".

Guncelleme (ana repodan):

    EVDS_API_KEY=xxxx dart run tool/update_cpi.dart --out ../kira-takip-data/cpi_tr.json
    cd ../kira-takip-data && git commit -am "TUFE guncelle" && git push

Bu repo kasitli olarak public: uygulama anahtar olmadan okur. Icinde kisisel veri yoktur.

## meta bolumu (elle)

- `meta.revaluation.<yil>`: yeniden degerleme orani (%). Kaynak: Resmi Gazete / GIB genel tebligi. Aidat artis tavani icin.
- `meta.rentExemption.<yil>`: konut kira geliri istisnasi (TL), gelir yili bazinda. Kaynak: GIB. Beyanname yardimcisi icin.

Bos birakilan yil icin uygulama o ozelligi sessizce gizler; uydurma rakam yazma.
