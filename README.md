# HIBERNATE - MAPPING SORTED SETS
This repository holds hibernate code example for mapping maps

We use  @OrderBy, that specifies the ordering of the elements when a collection is retrieved.

For ease of development and testing, we'll use auto configuration

```xml
<property name="hibernate.hbm2ddl.auto">update</property>
```

Database tables are NEVER dropped.

Very useful when you want to run your app multiple times and keep existing data.

Note: See sql-scripts folder. Inside are the SQLs that you need to create the schema.