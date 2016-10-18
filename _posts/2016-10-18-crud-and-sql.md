---
title:  "CRUD and SQL"
description: Definitions and examples of CRUD and SQL
---

### CRUD ###

CRUD is an acronym that stands for Create, Read, Update, and Delete. These are the basic functions of persistent storage.

### SQL ###

SQL stands for Structured Query Language. It is a language used to communicate with databases.

### CREATE ###

To create we use the SQL command, INSERT. This creates rows in a table.

{% highlight SQL %}
INSERT INTO "students" (NAME) VALUES ( 'Garry Bernhardt');
{% endhighlight %}

### READ ###

To read we use the SQL command, SELECT. This selects data from a table.

{% highlight SQL %}
SELECT * FROM students;
{% endhighlight %}

### UPDATE ###

To update we use the SQL command, UPDATE. This updates a value in a table.

{% highlight SQL %}
UPDATE "students" SET NAME = 'Garry Bernhardt' WHERE ID = 1;
{% endhighlight %}

### DELETE ###

To delete we use the SQL command, DELETE. This deletes a row from the table.

{% highlight SQL %}
DELETE FROM "students" WHERE ID = 1;
{% endhighlight %}
