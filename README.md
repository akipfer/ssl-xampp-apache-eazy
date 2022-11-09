# ssl-xampp-apache-eazy
LER TUDO Antes de proseguir(p/ Windows) 
Software usado para ssl + auto renewal win-acme -> https://www.win-acme.com/

Link do post do tutorial na integra no site -> https://www.snel.com/support/install-lets-encrypt-with-apache-on-windows-server-2019/

Se site estiver offline, abrir o PDF(Print completo da página feito com GoFullPage)

Seguir tutorial, porém, para instalações apache windows, não usar senha(pass phrase) pois não é suportado win32

Restart.bat -> dentro pasta scripts do app win-acme, pref na raiz do c:\win-acme\Scripts\RestartApache.bat  com conteúdo -> 
'net stop "Apache2.4" & sc start "Apache2.4"' sem aspas simples

Para auto renovação, o arg para usar  quando pedir -> '{StoreType} {StorePath} {RenewalId}' sem aspas
