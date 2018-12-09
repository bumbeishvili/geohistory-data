# geohistory-data




Drive - https://docs.google.com/spreadsheets/d/123zrq8tW1BbXKg27G7LZBZ1HonEMpDeDsCpToemabqY/edit#gid=1362440928



Import collection

`mongoimport -h ds133260.mlab.com:33260 -d geohistory -c ww2persons -u <user> -p <password> --file <input .csv file> --type csv --headerline`


Export collection  

`mongoexport -h ds133260.mlab.com:33260 -d geohistory -c ww2persons -u <user> -p <password> -o ww2persons.csv --csv -f <comma-separated list of field names>`