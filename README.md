# appterms.site sayfa kaynakları

Bu klasör statik sitenin kök dizinidir. Yayınlandığında oyun yolları:

- `https://appterms.site/number-run/privacy/`
- `https://appterms.site/number-run/terms/`
- `https://appterms.site/number-run/support/`

Yeni oyun için `/<oyun-slug>/privacy/`, `/terms/`, `/support/` yapısını kullanın. Her oyunun gizlilik metnini gerçek veri kullanımı ve SDK'larına göre ayrı yazın. Ortak iletişim adresi `lokman782782@gmail.com`.

Yayın için alan adının DNS kayıtları bir statik barındırmaya bağlanmalı, `www` yönlendirmesi döngü oluşturmayacak şekilde ayarlanmalı ve HTTPS sertifikası etkin olmalıdır. Namecheap ekranındaki URL yönlendirmesi tek başına bu dosyaları barındırmaz. Yayından sonra üç sayfanın da dış ağdan `200` döndüğü doğrulanmalıdır.
