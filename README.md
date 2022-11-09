# ssl-xampp-apache-eazy
Software usado para ssl + auto renewal win-acme -> https://www.win-acme.com/
Seguir tutorial, porém, para instalações apache windows, não usar senha(pass phrase) pois não é suportado win32

Restart.bat -> dentro pasta scripts do app win-acme, pref na raiz do c:\win-acme\Scripts\RestartApache.bat  com conteúdo -> 
'net stop "Apache2.4" & sc start "Apache2.4"' sem aspas simples

Para auto renovação, o arg para usar  quando pedir -> '{StoreType} {StorePath} {RenewalId}' sem aspas
