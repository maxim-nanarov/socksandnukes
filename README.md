# Nuclear/Socks project

The year is 1989. You are Russian, living in the USSR.

You have recently been enlisted to the Red Army. You love your country and are very patriotic. Every day, you listen to this song and dance:
 https://www.youtube.com/watch?v=oCc7ySI9YMw

Your job in the army is a software developer. This is you in [basic training](https://www.reckontalk.com/wp-content/uploads/2017/04/russian-army-funny-7.jpg). Your favorite food is [вишня](https://www.google.com/search?q=%D0%B2%D0%B8%D1%88%D0%BD%D1%8F&tbm=isch). This is what your computer [looks like](https://thumbs.dreamstime.com/b/red-computer-15853424.jpg).

The army has decided it is time to rewrite its `[nuclear bombs / socks]` management system. This system is very important as it keeps track of all the `[nuclear bombs / socks]` in all of the storage locations in the army, some of them top-secret.

Your job is to write a CRUD webapp + server that organizes all of this inventory.

Each `[nuclear bomb / socks]` has the following fields:
* Model
* Quantity
* Size
* Location - lat, lon, name of base, nearest city.
* Manufacturing year
* Location history - a list of prior arrival + departure dates and locations
* Officer in charge, including name, army id, email and phone number

Your system should include an SQL database, and the database should be normalized. That means, that there shouldn't be data duplications. For example, if an officer is in charge of 2 `[nuclear bombs / socks]`, their name shouldn't be stored twice in the DB.

The webapp should allow for all CRUD operations. So overall, you should have an SQL DB + server + webapp.

Bonus - support search and pagination.

Just so you know `[nuclear bombs / socks]` are of strategic importance to the Red Army. We have faith in your coding abilities.

Удачи, товарищ!
