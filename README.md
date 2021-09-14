# dmflex_tests

```
docker run -p 54321:5432 -e POSTGRES_DB=edit -e POSTGRES_PASSWORD=mysecretpassword edigonzales/postgis:13-3.1
```

```
java -jar /Users/stefan/apps/ili2pg-4.6.0/ili2pg-4.6.0.jar --setupPgExt	--dbhost localhost --dbport 54321 --dbdatabase edit --dbusr postgres --dbpwd mysecretpassword --dbschema dmflex --nameByTopic --strokeArcs --defaultSrsCode 2056 --createEnumTabs --modeldir ".;http://models.geo.admin.ch" --models DM_Flex_AV_CH_Grundstuecke_V1_0 --schemaimport
```