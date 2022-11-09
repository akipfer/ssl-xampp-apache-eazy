# ssl-xampp-apache-eazy
Software usado para ssl + auto renewal win-acme -> https://www.win-acme.com/
Seguir tutorial, porém, para instalações apache windows, não usar senha(pass phrase) pois não é suportado win32

Restart.bat -> 'net stop "Apache2.4" & sc start "Apache2.4"' sem aspas simples

arg para usar para renovação quando pedir -> '{StoreType} {StorePath} {RenewalId}' sem aspas
