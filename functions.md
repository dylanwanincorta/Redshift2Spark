
SQL written against Redshift database may use some functions that are only supported in redshfit, but those functions may or may not have an equivalent function is Apach Spark SQL.

Here is the mapping of the redshift SQL function to Spark SQL function

| Category |Redshift function        | Spark function           | Comments  |
| :-----|:-------------------: |:-------------:| -----:|
|  | [REPLACE](http://docs.aws.amazon.com/redshift/latest/dg/r_REPLACE.html)     | translate | Oracle also uses translate |
|  | function 2     | TBD      |    |
|  | function 3| TBD     |    |
