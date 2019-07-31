# Magento 2 için Türkiye İlçeleri Import Eklentisi

Romcity modülüne Türkiye ilçelerini ekler ve adres ekranlarında şehir seçilince ilçelerin de açılır menü olarak gelmesini sağlar.

# Kurulum
 - Zip içinden çıkan dosyaları `/app/code/Grinet/RomcityImportTurkeyCities` klasörüne yükleyin

( Unix/Linux/MacOSX için ) 
Magento ana klasörünüze girip aşağıdaki komutları çalıştırın :a
```bash
php bin/magento module:enable Grinet_RomcityImportTurkeyCities
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Composer ile kurulum
```bash
composer require grinet/Grinet_RomcityImportTurkeyCities
php bin/magento module:enable Grinet_RomcityImportTurkeyCities
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Hata bildirimi

Gördüğünüz hataları info@grinet.com.tr adresimize iletebilirsiniz...

-----------------------------------------------------------------

# Import Turkey Cities to Romcity extension

This extension adds Turkey Cities to your Magento2.

# Installation
 - Copy all files to `/app/code/Grinet/RomcityImportTurkeyCities` directory

( For Unix/Linux/MacOSX ) 
Go to your root folder of your magento site and run these commands :
```bash
php bin/magento module:enable Grinet_RomcityImportTurkeyCities
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Installation with composer
```bash
composer require grinet/Grinet_RomcityImportTurkeyCities
php bin/magento module:enable Grinet_RomcityImportTurkeyCities
php bin/magento setup:upgrade
php bin/magento cache:clean
```

# Error reporting

Please send errors to info@grinet.com.tr ...

------------------------------------------------------------------
# Ekran Görüntüleri / Screenshots
<img src="http://grinet.com.tr/images/magento2_regions/frontend_addres_cities.png">
