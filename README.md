# proyecto

## Dada una arquitectura de AWS con una instancia EC2, una base de datos RDS de tipo postgres y un bucket de S3 se desea que se realice lo siguiente:

-Un servicio web que genere logs y los escriba en el bucket de S3.
-Filebeat que lea los logs de s3 y los almacene en Elasticsearch.
-Auditbeat y Packetbeat, que recojan la información correspondiente a cada servicio y la almacenen en Elasticsearch.
-Logstash, que recoja información de S3 y la almacene en Elasticsearch.
-Un servicio web que lea la información de la BBDD RDS.
-Django