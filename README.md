# MongoDB desde Cero: Agregación

En esta entrada vemos como utilizar el **Aggregation Framework** de MongoDB. 

Hemos generado un serie de ordenes para que puedas trabajar en esta entrada, para importarla a tu base de datos haz lo siguiente:

```sh
$ mongoimport -d codehero -c ordenes ordenes.json
```

Esto tomará el archivo `ordenes.json`, *parseará* cada registro y lo convertirá en un documento de la colección `ordenes` en la base de datos `codehero` en tu instancia de mongo.  
