cd  C:\Users\%USERNAME%
mkdir CAMINHO_SQL_TERMINAL
cd  C:\Users\%USERNAME%\CAMINHO_SQL_TERMINAL
echo cd C:\Program Files\MySQL\MySQL Server 8.0\bin>Comandos_Para_Usar_SQL_Terminal.bat
echo mysql -h localhost -u root -p >> Comandos_Para_Usar_SQL_Terminal.bat
setx PATH "%PATH%;C:\Users\%USERNAME%\CAMINHO_SQL_TERMINAL" /M

